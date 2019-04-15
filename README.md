# adguardhome-filters
Hosts lists from Steven Black (https://github.com/StevenBlack/hosts)

	Cleaned-up from "localhost" records.
	127.0.0.1 replaced to 0.0.0.0
	Extensions are left unmerged.

Files are used for AdGuard Home DNS filtering.

P.S. Looking for the way to translate easily multiple hostname records
to one line accordingly to general AdBlock rules set, i.e.

	www.abc.com
	abc.com
	external.www.abc.com.site
	
to

	||abc.com*^

or similar.

Need to build the following algorithm:
1. grab original file;
2. mirror each string and sort ( like 'cat ./file1 | rev | sort > file2' );
3. moving down, remember each string and compare it with all the rest, deleting all longer ones ( "moc.cba||" -> delete all "moc.cba\.*" );
4. revert strings back and sort;
5. done.

Better to be written in bash/sed/awk or python or Go.
