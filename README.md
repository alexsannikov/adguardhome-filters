# adguardhome-filters

> [!WARNING]
> **THIS REPOSITORY IS PLANNED TO BE BACK SOON. PLEASE WAIT FUTURE UPDATES**

Filter lists prepared for use with AdGuard Home.

All the lists are generated automatically with the script and use other sources supported by their autors and contributors.
If you see any error in the list (like disabled valid URL, banned legitimate service, etc.) please create issue in the Steven's repo (https://github.com/StevenBlack/hosts). Due to the automatic nature of the AdGuard Home lists generation, I do not correct these lists manually. All changes appled to the source hosts files by their authors to be reflected in AdGuard Home filter lists.

Please also remember, that it is possible to create your own local filter with `important` markers and override any incorrect or unnecessary filters defined in lists from this repo.

Use AdGuard Simplified Domain Names filter as a primary source for your AdGuard home.

## Sources:

   1.  StevenBlack repo (https://github.com/StevenBlack/hosts)
   2.  RuAdList + EasyList repo by Schakal (https://schakal.ru/hosts/alive_hosts.txt)

All filter lists are cleaned up and re-formatted from the 'hosts' file format:
   *  cleaned-up from "local/localhost/broadcast/etc." lines;
   *  cleaned-up from IPv4 and IPv6 addresses only as per RFC952;
   *  127.0.0.1 and 0.0.0.0 are replaced to || (any sub-domains, supported by AdGuard Home);
   *  extensions files are left unmerged for independent use (fakenews, social, gambling etc.);
   *  all sub-domains are removed if upper-level domain is in the list. AdGuard will block all sub-domains;
   *  adult TLDs are fully blocked;
   *  some improvements added to domains lists;
   *  RuAdList file added to StevenBlack's Adware+Malware file, all duplicates removed;
   *  all files from this repo compared with AdGuard Simplified Domain Names filter, and duplicates removed.

Files are compatible with AdGuard Home DNS filtering system.
