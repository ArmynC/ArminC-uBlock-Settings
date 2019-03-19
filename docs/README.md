<h1 align="center">
  <br>
  <a href="https://github.com/ArmynC/ArminC-uBlock-Settings/archive/master.zip"><img src="https://arminc.tk/resources/ublock_settings/arminc_ublock_settings.png" alt="ArminC uBlock Settings"></a>
</h1>

<h4 align="center">A high-quality uBlock₀ config built for all types of people.</h4>

<p align="center">
    <a href="https://github.com/ArmynC/ArminC-uBlock-Settings/commits/master">
    <img src="https://img.shields.io/github/last-commit/ArmynC/ArminC-uBlock-Settings.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub last commit">
    <a href="https://github.com/ArmynC/ArminC-uBlock-Settings/issues">
    <img src="https://img.shields.io/github/issues-raw/ArmynC/ArminC-uBlock-Settings.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub issues">
    <a href="https://github.com/ArmynC/ArminC-uBlock-Settings/pulls">
    <img src="https://img.shields.io/github/issues-pr-raw/ArmynC/ArminC-uBlock-Settings.svg?style=flat-square&logo=github&logoColor=white"
         alt="GitHub pull requests">
    <a href="https://twitter.com/intent/tweet?text=Try this uBlock Origin config:&url=https%3A%2F%2Fgithub.com%2FArmynC%2FArminC-uBlock-Settings">
    <img src="https://img.shields.io/twitter/url/https/github.com/ArmynC/ArminC-uBlock-Settings.svg?style=flat-square&logo=twitter"
         alt="GitHub tweet">
</p>
      
<p align="center">
  <a href="#about">About</a> •
  <a href="#installation">Installation</a> •
  <a href="#updating">Updating</a> •
  <a href="#features">Features</a> •
  <a href="#sources">Sources</a> •
  <a href="#wiki">Wiki</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#author">Author</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

---

## About

<table>
<tr>
<td>
  
**ArminC uBlock Settings** is a _configuration_ file  for _uBlock Origin_ which consist of several **high-quality** _cherry picked_ *filters* that aim to **block** **ads**, **pop-ups**, **trackers**, **malicious adresses**, and at the same time **decreases** the number of loaded **elements**, thus **loading** the pages **faster**.

</td>
</tr>
</table>

## Installation

##### Downloading and installing steps:
* **[Download](https://github.com/ArmynC/ArminC-uBlock-Settings/archive/master.zip)** the latest version of the settings.
  * Make sure that you got **[uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)** extension.
* Open _uBlock₀_ **dashboard**.
  * See **[how to open the dashboard](https://github.com/gorhill/uBlock/wiki/Dashboard)**.
* At the bottom, in _Backup/Restore_ section, press `Restore from file...`
  * See **[the dashboard settings](https://github.com/gorhill/uBlock/wiki/Dashboard:-Settings)**.
* Select the `arminc-ublock-backup.txt` (from .zip) and press **OK**.

## Updating

When a **new version** is out, you have **two methods** to _update_:

##### 1. You have edited the settings based on your preference:
* Check the new [commits](https://github.com/ArmynC/ArminC-uBlock-Settings/commits/master) and **update** the settings **manually** by relying on the _commits_.

##### 2. You haven't edited the settings (or at least not so much):
* **Delete everything** (or make sure to **replace the files** when it asks).
* **Redo** the [installation](https://github.com/ArmynC/ArminC-uBlock-Settings#installation) steps.
* _After setup_, **change your preference** settings back (if it is the case).

The _settings_ are **updated** (at a random time), so make sure you **come back** here to **check** for **updates**.

## Features

|            |  🔰 ArminC uBlock₀ Settings | ◾ Default uBlock₀ settings |
| --------------------------  | :----------------: | :-------------: |
| Block most of the ads       |         ✔️         |        ❌        |
| Block most of the pop-ups   |         ✔️         |        ❌        |
| Block most of the trackers  |         ✔️         |        ❌        |
| Block most of the annoyances|         ✔️         |        ❌        |
| Block coin miners           |         ✔️         |        ❌        |
| Block +18                   |         ✔️         |        ❌        |
| Block ransomware, malware   |         ✔️         |        ❌        |

## Sources

#### Built-in
|            **Source**           |            **Author**            |                                                                           **Description**                                                                           |                                      **Location**                                             |
|:-------------------------------:|:--------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|
| uBlock Filters (uAssets)        | Raymond Hill                     | Default uBlock resources.                                                                                                                                           | [LINK](https://github.com/uBlockOrigin/uAssets/tree/master/filters)                           |
| Adblock Warning Removal List    | Fanboy                           | Removes obtrusive messages and warnings targeted to users who use an adblocker.                                                                                     | [LINK](https://easylist.to/pages/other-supplementary-filter-lists-and-easylist-variants.html) |
| Adguard English filter          | AdGuard Team                     | English ad blocking.                                                                                                                                                | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/EnglishFilter/sections)      |
| AdGuard Tracking Protection     | AdGuard Team                     | List of various online counters and web analytics tools.                                                                                                            | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/SpywareFilter/sections)      |
| EasyPrivacy                     | Fanboy, MonztA, Famlam and Khrin | Completely removes all forms of tracking from the internet, including web bugs, tracking scripts and information collectors, thereby protecting your personal data. | [LINK](https://github.com/easylist/easylist/tree/master/easyprivacy)                          |
| Fanboy's Enhanced Tracking List | Fanboy                           | Blocks common tracking scripts.                                                                                                                                     | [LINK](https://fanboy.co.nz/filters.html)                                                     |
| Malware Domain List             | Malware Domain List Community    | Blocks malware domains.                                                                                                                                             | [LINK](http://www.malwaredomainlist.com/forums/index.php?topic=3270.0)                        |
| Malware Domains                 | RiskAnalytics                    | A list of domains that are known to be used to propagate malware.                                                                                                   | [LINK](https://www.malwaredomains.com/?page_id=66)                                            |
| Spam404                         | Spam404                          | Protects you from online scams.                                                                                                                                     | [LINK](https://github.com/Spam404/lists)                                                      |
| AdGuard Annoyances filter       | AdGuard Team                     | Blocks irritating elements on web pages including cookie notices, third-party widgets and in-page pop-ups.                                                          | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/AnnoyancesFilter/sections)   |
| Fanboy's Cookie List            | Fanboy                           | Remove cookie and privacy warnings.                                                                                                                                 | [LINK](https://fanboy.co.nz/index.html)                                                       |
| hpHost's ATS                    | Malwarebytes                     | Block ad/tracking sites/servers.                                                                                                                                    | [LINK](https://hosts-file.net/?s=Download)                                                    |
| MVPS HOSTS                      | Mike                             | Entries for most major parasites, hijackers and unwanted adware/spyware programs.                                                                                   | [LINK](http://winhelp2002.mvps.org/hosts.htm)                                                 |

#### Custom
|                         **Source**                         |    **Author**    |                                                                  **Description**                                                                 |                                       **Location**                                               |
|:----------------------------------------------------------:|:----------------:|:------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------------------:|
| Toxic Domains                                              | StopForumSpam    | Domains used to abuse.                                                                                                                           | [LINK](https://www.stopforumspam.com/downloads)                                                  |
| SomeoneWhoCares                                            | Dan Pollock      | Protect you from many types of spyware, reduces bandwidth use, blocks certain pop-up traps, prevents user tracking, and blocks most advertising. | [LINK](http://someonewhocares.org/hosts/zero/)                                                   |
| Badd Boyz Hosts                                            | Mitchell Krog    | Protect you from many types of spyware, adware, malware, click-jacking and porn sites and reduces bandwidth use.                                 | [LINK](https://github.com/mitchellkrogza/Badd-Boyz-Hosts)                                        |
| Chad Mayfield Porn Blocklist Light                         | Chad Mayfield    | Block porn sites that appear on Alex Top 1M site list.                                                                                           | [LINK](https://github.com/chadmayfield/my-pihole-blocklists/tree/master/lists)                   |
| Steven Black's ad-hoc list                                 | Steven Black     | Additional sketch domains.                                                                                                                       | [LINK](https://github.com/StevenBlack/hosts/tree/master/data/StevenBlack)                        |
| add.Spam                                                   | FadeMind         | Spam websites.                                                                                                                                   | [LINK](https://github.com/FadeMind/hosts.extras/tree/master/add.Spam)                            |
| add.Risk                                                   | FadeMind         | Websites with risk content, malwares.                                                                                                            | [LINK](https://github.com/FadeMind/hosts.extras/tree/master/add.Risk)                            |
| UncheckyAds                                                | FadeMind         | Windows installers ads sources.                                                                                                                  | [LINK](https://github.com/FadeMind/hosts.extras/tree/master/UncheckyAds)                         |
| Ransomware Domain Blocklist                                | Abuse.Ch         | Block Ransomware botnet C&C traffic.                                                                                                             | [LINK](https://ransomwaretracker.abuse.ch/blocklist/)                                            |
| Better                                                     | Ind.ie           | Blocking rules.                                                                                                                                  | [LINK](https://better.fyi)                                                                       |
| Malware Domains Immortal                                   | RiskAnalytics    | A list of domains that are known to be used to propagate malware.                                                                                | [LINK](https://www.malwaredomains.com/?page_id=66)                                               |
| Anti-'Notification pre-prompt banners' List                | DandelionSprout  | Blocks browser notifications.                                                                                                                    | [LINK](https://github.com/DandelionSprout/adfilt/)                                               |
| I Don't Want to Download Your Browser                      | DandelionSprout  | Block browser upgrade notifications.                                                                                                             | [LINK](https://github.com/DandelionSprout/adfilt/)                                               |
| Browse websites without logging in                         | DandelionSprout  | Block log-in notifications.                                                                                                                      | [LINK](https://github.com/DandelionSprout/adfilt/)                                               |
| CHEF-KOCH's CoinMiner Filter List                          | CHEF-KOCH        | Block all crypto coin miners.                                                                                                                    | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's Cookie & GDPR Warning Removal Filter List      | CHEF-KOCH        | Block Cookie, GDPR warnings.                                                                                                                     | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's Google Filter List                             | CHEF-KOCH        | Block all Google & services traffic                                                                                                              | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's iframe Filter List                             | CHEF-KOCH        | Block iframe elements.                                                                                                                           | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's Malware Filter List                            | CHEF-KOCH        | Block Malware & Phising Domains.                                                                                                                 | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's NSABlocklist FilterList                        | CHEF-KOCH        | Block all known NSA / GCHQ / C.I.A. / F.B.I. spying servers.                                                                                     | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/Anti-Corp/filters)         |
| CHEF-KOCH's PopAds Filter List                             | CHEF-KOCH        | Block Popads.                                                                                                                                    | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's Reddit Filter List                             | CHEF-KOCH        | Remove tracking and cosmetical annoyance which is Reddit exclusive.                                                                              | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's Unbreak Filter List                            | CHEF-KOCH        | Whitelist rules and exceptions in order to not break several websites.                                                                           | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| CHEF-KOCH's YouTube Filter List                            | CHEF-KOCH        | Block annoying web elements on YouTube.                                                                                                          | [LINK](https://github.com/CHEF-KOCH/CKs-FilterList-Mirror/tree/master/filters)                   |
| EasyList - Lite                                            | AdBlock Team     | Contains filters to block and hide ads everywhere.                                                                                               | [LINK](https://help.getadblock.com/support/solutions/articles/6000142821-what-is-easylist-lite-) |
| Hexxium Creations Threat List                              | Hexxium          | Protect user from malware, scams, phishing attempts, deceptive content.                                                                          | [LINK](https://github.com/HexxiumCreations/threat-list)                                          |
| I don't care about cookies                                 | Daniel Kladnik   | Removes annoying cookie warnings from almost all websites.                                                                                       | [LINK](https://www.i-dont-care-about-cookies.eu/)                                                |
| Lightswitch05's Ads & Tracking                             | Daniel White     | Analytics, Ads, and tracking hosts to block.                                                                                                     | [LINK](https://github.com/lightswitch05/hosts)                                                   |
| Lightswitch05's AMP Hosts                                  | Daniel White     | Block AMP pages.                                                                                                                                 | [LINK](https://github.com/lightswitch05/hosts)                                                   |
| Miscellaneous Annoyance                                    | Kowith337        | Uncategorized miscellaneous annoyance.                                                                                                           | [LINK](https://github.com/kowith337/PersonalFilterListCollection/tree/master/filterlist/other)   |
| IpLoggerFilter                                             | Piperun          | Filter any site/subsite who's only purpose is to log your IP.                                                                                    | [LINK](https://github.com/piperun/iploggerfilter)                                                |
| Web Annoyances Ultralist - Modal Overlay Filters           | Yourduskquibbles | Block annoying web elements that block screen real estate.                                                                                       | [LINK](https://github.com/yourduskquibbles/webannoyances/tree/master/filters)                    |
| Web Annoyances Ultralist - Newsletter Subscription Filters | Yourduskquibbles | Block annoying newsletter that block screen real estate.                                                                                         | [LINK](https://github.com/yourduskquibbles/webannoyances/tree/master/filters)                    |

## Wiki

Do you **need some help**? Check the _articles_ from the [wiki](https://github.com/ArmynC/ArminC-uBlock-Setings/wiki/).

## Contributing

Got **something interesting** you'd like to **share**? Learn about [contributing](https://github.com/ArmynC/ArminC-uBlock-Settings/blob/master/docs/CONTRIBUTING.md).

## Author

| [![ArminC](http://www.gamerconfig.eu/files/avatars/thumbnail_arminc.png)](https://linkedin.com/in/arminc) 	| [![?](https://cdn2.iconfinder.com/data/icons/ios-7-icons/50/help-128.png)](https://github.com/ArmynC/ArminC-uBlock-Settings#sources)		|
|:---------------------------------------------------------------------------------------------------------:	|:------------------------------------------------------------------------------------------------------------------------------------:		|
|                                            **Armin Chanchian**                                            	|                                                             **Filters Authors**                                          					|

## Support

Reach out to me at one of the following places:

- Website at [arminc.tk](https://arminc.tk)
- Steam Profile at **[ArminC](https://steamcommunity.com/id/arminc/)**
- E-Mail: **arminandrey@gmail.com**

## License

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-orange.svg?style=flat-square)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

- Copyright © [ArminC](https://arminc.tk "ArminC Directory Database").