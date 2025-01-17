# adguardhome-filters

> [!NOTE]
> **UPDATES FOR THIS REPOSITORY ARE RESTORED. AS USUAL, CHANGES WILL BE PUSHED EVERY MON, TUE, FRI. ENJOY!**

Filter lists are prepared for use with AdGuard Home DNS filtering system.

## Sources:

   1.  StevenBlack's repository (Adware+Malware, Fakenews, Gambling, Social etc.)
   2.  Schakal's repository (RU AdList+EasyList)

All filter lists in this repo are generated automatically with the script using sources supported by their autors and contributors.
Files are cleaned up and re-formatted from the 'hosts' file format:
   *  cleaned-up from "local/localhost/broadcast/etc." lines;
   *  cleaned-up from IPv4 and IPv6 addresses only as per RFC952;
   *  127.0.0.1 and 0.0.0.0 are replaced to || (any sub-domains, this is supported by AdGuard Home logic);
   *  extensions' files are left unmerged for independent use (fakenews, social, gambling etc.);
   *  all sub-domains are removed if upper-level domain is in the list. AdGuard will block all sub-domains automatically;
   *  adult TLDs are fully blocked;
   *  some improvements added to domains lists;
   *  RU AdList+Easylist file added to StevenBlack's Adware+Malware file, all duplicates removed;
   *  all files from this repo compared with AdGuard Simplified Domain Names filter, and de-duplicated.

Please don't forget to add AdGuard Simplified Domain Names filter as a primary source into your AdGuard Home.

If legitimate domain names are banned with these lists, it may be because StevenBlack's repo or Schakal's repo included them into their sources. In this case if you think they must be excluded, please check these repos and open the issue. Due to the automatic nature of the AdGuard Home filter lists generation, I do not correct these lists manually. All changes applied to the source hosts files by their authors to be reflected in AdGuard Home filter lists. 
As a workaround, please remember that you can always unblock any domain locally from the AdGuard home GUI.

## Links:

* [StevenBlack's repository on GitHub](https://github.com/StevenBlack "StevenBlack's repository on GitHub")
* [Schakal's HOSTS file](https://schakal.ru/hosts/alive_hosts.txt "Schakal's HOSTS file")
* [Schakal's post about the repo](https://4pda.to/forum/index.php?showtopic=275091&st=7980#entry89665467)
