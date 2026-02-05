# adguardhome-filters

> [!NOTE]
> **UPDATES FOR THIS REPOSITORY HAS BEEN RESTORED. AS USUAL, CHANGES WILL BE PUSHED EVERY MONDAY, WEDNESDAY, AND FRIDAY. ENJOY!**

This repository contains filter lists specifically prepared for use with the AdGuard Home DNS filtering system.

## Sources

**StevenBlack's repository**: includes filters for Adware+Malware, FakeNews, Gambling, Social, and more.

**Schakal's repository**: includes RU AdList+EasyList.<br><br>

All filter lists in this repository are automatically generated using a script that incorporates sources supported by their respective authors and contributors. These lists are cleaned and reformatted from the `hosts` file format as follows:
   *  removed unnecessary lines (e.g., "local/localhost/broadcast/etc.");
   *  cleaned of IPv4 and IPv6 addresses as specified in RFC952;
   *  replaced `127.0.0.1` and `0.0.0.0` with `||` to match AdGuard Home’s subdomain-blocking logic;
   *  maintained separate extension files for independent use (e.g., Fake News, Social, Gambling, etc.);
   *  removed subdomains if the top-level domain is already listed, as AdGuard blocks all subdomains automatically;
   *  fully blocked adult-related TLDs;
   *  improved domain lists with additional enhancements;
   *  combined RU AdList+EasyList with StevenBlack's Adware+Malware file, removing all duplicates;
   *  compared all files with AdGuard’s Simplified Domain Names filter to ensure deduplication.

## Important notes

Please ensure that you add the AdGuard Simplified Domain Names filter as a primary source in your AdGuard Home setup.

If legitimate domains are mistakenly blocked using these filter lists, it is likely due to their inclusion in the source repositories (StevenBlack or Schakal). If you believe such domains should be excluded, please review the respective source repositories and open an issue there.

Due to the automated nature of the list generation, no manual corrections are made to these filter lists. Any changes made by the original authors to their source files will automatically reflect in the generated AdGuard Home filter lists.

As a workaround, you can always unblock domains locally via the AdGuard Home GUI.


## Useful links

* [StevenBlack's repository on GitHub](https://github.com/StevenBlack "StevenBlack's repository on GitHub")
* [Schakal's HOSTS file](https://schakal.ru/hosts/alive_hosts.txt "Schakal's HOSTS file")
* [Schakal's post about the repo](https://4pda.to/forum/index.php?showtopic=275091&st=7980#entry89665467)
* [MMotti's repository on GitHub](https://github.com/mmotti "MMotti's repository on GitHub")
