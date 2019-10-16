# adguardhome-filters
Filter lists revised for use with AdGuard Home:

	- cleaned-up from "localhost/broadcast" lines;
	- cleaned-up from pure IP-addresses records as per RFC952;
	- 127.0.0.1 and 0.0.0.0 replaced to || (supported by AdGuard Home);
	- extensions are left unmerged for independent use;
	- all sub-domains are removed if upper-level domain already presented;
	- adult TLDs are fully blocked;
	- some improvements added to domains lists.

Files are compatible with AdGuard Home DNS filtering system.

Sources:
1. StevenBlack repo (https://github.com/StevenBlack/hosts);
2. RuAdList + EasyList repo by raletag (http://cdn.raletag.gq/rueasyhosts.txt).

RuAdList file compared with all StevenBlack files. All matching lines removed.

2019-Oct-15

WARNING! raletag's resource is currently unavailable!
RuAdlist + EasyList file left as it was on 2019 September 25th.

I am planning to move all files from "extensions" folder to root one.
For some migration time (~1 month roughly) extension files will be in both directories.
Please don't forget to update filters' sources.
After that period files will be in their permanent place only.
