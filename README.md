# adguardhome-filters
Filters lists revised for usage with Adguard Home:

	- cleaned-up from "localhost/broadcast" records;
	- 127.0.0.1 and 0.0.0.0 replaced to ||;
	- extensions are left unmerged to use independently;
	- all sub-domains are removed if top-level domain presented;
	- adult TLDs fully blocked;
	- some improvements added to domains lists.

Files are compatible with AdGuard Home DNS filtering.

Sources:
1. StevenBlack repo (https://github.com/StevenBlack/hosts);
2. RuAdList + EasyList repo by raletag (http://cdn.raletag.gq/rueasyhosts.txt).

RuAdList file compared with all StevenBlack files. All matching lines are removed.
