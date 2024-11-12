# adguardhome-filters

> [!CAUTION]
> **THIS REPOSITORY TEMPORARILY OUT OF ORDER. THE UPDATES WILL BE RESTORED SOON**

Filter lists prepared for use with AdGuard Home.

All the lists are generated automatically with the script and use other sources supported by their autors and contributors.
If you found any error in the list (like disabled valid URL, banned legitimate service, etc.) please create issue in the Steven's repo (https://github.com/StevenBlack/hosts). Due to the automatic nature of the AdGuard Home lists generation, I do not correct these lists manually. All appled changes in the source hosts files to be applied to the AdGuard Home filter lists.

Please also remember, that you can create your own local filter with importance markers and override any incorrect or unnecessary filters defined in lists from this repo.

Use AdGuard Simplified Domain Names filter as a primary source for your AdGuard home.

## Sources:

   1.  StevenBlack repo (https://github.com/StevenBlack/hosts);
   2.  RuAdList + EasyList repo by Schakal (https://schakal.ru/hosts/alive_hosts.txt).

All filter lists are cleaned up and re-formatted from the 'hosts' file format:
   *  cleaned-up from "local/localhost/broadcast/etc." lines;
   *  cleaned-up from IPv4 and IPv6 addresses only as per RFC952;
   *  127.0.0.1 and 0.0.0.0 are replaced to || (any sub-domains, supported by AdGuard Home);
   *  extensions files are left unmerged for independent use;
   *  all sub-domains are removed if upper-level domain is already presented;
   *  adult TLDs are fully blocked;
   *  some improvements added to domains lists;
   *  RuAdList file compared with all StevenBlack files, duplicates removed;
   *  all files are compared with AdGuard Simplified Domain Names filter, duplicates removed.

Files are compatible with AdGuard Home DNS filtering system.
