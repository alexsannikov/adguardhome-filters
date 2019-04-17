# adguardhome-filters
Hosts lists from Steven Black (https://github.com/StevenBlack/hosts)

	cleaned-up from "localhost" records;
	127.0.0.1 and 0.0.0.0 replaced to ||;
	extensions are left unmerged;
	left most top-domain only;

Files are used for AdGuard Home DNS filtering.

P.S. Looking for the intellectual algorithm to translate easily multiple hostname records
to one line accordingly to general AdBlock rules set, i.e.

	www1.abc.com
	extra.abc.com
	external.www.abc.com
	pictures.domain.com
	pictures1.domain.co.nz
	pic-tures.domain.net.site
	
to

	||abc.com*^
	||domain.*^

or similar.
