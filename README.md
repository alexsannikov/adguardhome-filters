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
