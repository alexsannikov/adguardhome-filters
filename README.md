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
2. RuAdList + EasyList repo by Schakal (https://schakal.ru/hosts/alive_hosts.txt).

RuAdList file compared with all StevenBlack files. All matching lines removed.
