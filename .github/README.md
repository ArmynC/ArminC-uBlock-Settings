<h1 align="center">
  <br>
  <a href="https://github.com/ArmynC/ArminC-uBlock-Settings/archive/master.zip"><img src="https://raw.githubusercontent.com/ArmynC/ArminC-uBlock-Settings/master/arminc_ublock_settings.png" alt="ArminC uBlock Settings"></a>
</h1>

<h4 align="center">A high-quality uBlock₀ config built for everyone.</h4>

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
  <a href="#author">Author</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

---

## About

<table>
<tr>
<td>
  
**ArminC uBlock Settings** is a _configuration_ file  for **uBlock Origin** which consists of several **high-quality** *filters* that aim to **block** **ads**, **pop-ups**, **trackers**, **malicious addresses** and **decreases** the number of loaded **elements**, thus **loading** the pages **faster**.

</td>
</tr>
</table>

## Installation

##### Downloading and installing steps:
* **[Download](https://github.com/ArmynC/ArminC-uBlock-Settings/archive/master.zip)** the latest version of these settings.
  * Get the **[uBlock Origin](https://github.com/gorhill/uBlock#installation)** extension.
    * Make sure that you use **[Firefox Browser](https://www.mozilla.org/en-US/firefox/new/)** for **unrestricted** working capabilities.
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

|           |  🔰 ArminC uBlock₀ Settings | ◾ Other uBlock₀ settings  |
| --------------------------    | :----------------: | :-------------: |
| Blocks ads                    |         ✔️         |        〰️       |
| Blocks pop-ups                |         ✔️         |        〰️       |
| Blocks trackers               |         ✔️         |        〰️       |
| Blocks annoyances             |         ✔️         |        〰️       |
| Blocks malware                |         ✔️         |        〰️       |
| Blocks coin miners            |         ✔️         |        ❌       |
| Blocks +18                    |         ✔️         |        ❌       |
| Has only useful filters       |         ✔️         |        ❌       |
| Has only recent filters       |         ✔️         |        ❌       |

## Sources

#### Built-in
|               **Name**            |            **Credits**           |                                                                              **Block**                                                                              |                                           **Source**                                           |
|:---------------------------------:|:--------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------:|
| uBlock Filters (uAssets)          | Raymond Hill                     | Ads, adware, trackers, resource abusers and page breaking.                                                                                                          | [LINK](https://github.com/uBlockOrigin/uAssets/tree/master/filters)                            |
| Adguard - Ads                     | AdGuard Team                     | Ads from websites with English content.                                                                                                                             | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/EnglishFilter/sections)       |
| EasyList                          | EasyList Team                    | Adverts from international webpages, including unwanted frames, images and objects.                                                                                 | [LINK](https://easylist.to/)                                                                   |
| AdGuard Tracking Protection       | AdGuard Team                     | Online counters and web analytics tools.                                                                                                                            | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/TrackParamFilter/sections)    |
| AdGuard URL Tracking Protection   | AdGuard Team                     | Filter that enhances privacy by removing tracking parameters from URLs.                                                                                             | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/TrackParamFilter/sections)    |
| Block Outsider Intrusion into LAN | Gwarser                          | Public internet sites from digging into your local LAN files, and can also help mitigate DNS rebind attacks.                                                        | [LINK](https://github.com/gwarser/filter-lists)                                                |
| URLhaus - Malicious URL Blocklist | Ming Di Leom                     | Malicious websites that are being used for malware distribution.                                                                                                    | [LINK](https://gitlab.com/curben/urlhaus-filter)                                               |
| AdGuard Annoyances filter         | AdGuard Team                     | Cookie notices, third-party widgets and in-page pop-ups.                                                                                                            | [LINK](https://github.com/AdguardTeam/AdguardFilters/tree/master/AnnoyancesFilter/sections)    |
| uBlock - Annoyances               | Raymond Hill                     | Annoyances.                                                                                                                                                         | [LINK](https://github.com/uBlockOrigin/uAssets/tree/master/filters)                            |

#### Custom
|                          **Name**                          |              **Credits**             |                                                                   **Blocks**                                                                     |                                              **Source**                                           |
|:----------------------------------------------------------:|:------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------:|
| Actually Legitimate URL Shortener Tool                     | iam-py-test & DandelionSprout        | unnecessary $/& values from the URLs.                                                                                                            | [LINK](https://github.com/DandelionSprout/adfilt)                                                 |
| Browse websites without logging in                         | DandelionSprout                      | Log-in notifications.                                                                                                                            | [LINK](https://github.com/DandelionSprout/adfilt)                                                 |
| I Don't Want to Download Your Browser                      | DandelionSprout                      | Browser upgrade notifications.                                                                                                                   | [LINK](https://github.com/DandelionSprout/adfilt)                                                 |
| Steven Black's ad-hoc list                                 | Steven Black                         | Additional sketch domains.                                                                                                                       | [LINK](https://github.com/StevenBlack/hosts/tree/master/data/StevenBlack)                         |
| The P@ Dude                                                | OISD                                 | P@ sites.                                                                                                                                        | [LINK](https://oisd.nl/includedlists/nsfw)                                                        |
| Top P@ Sites                                               | OISD                                 | Additional NSFW sites.                                                                                                                           | [LINK](https://oisd.nl/includedlists/nsfw)                                                        |
| OpenPhish Phishing Feed                                    | OpenPhish Community                  | Phishing sites.                                                                                                                                  | [LINK](https://www.openphish.com/index.html)                                                      |
| Fanboy Addon - Notification General Block                  | EasyList Team                        | General notifications.                                                                                                                           | [LINK](https://github.com/easylist/easylist/tree/master/fanboy-addon)                             |
| Fanboy Addon - Notification General Hide                   | EasyList Team                        | General notifications element.                                                                                                                   | [LINK](https://github.com/easylist/easylist/tree/master/fanboy-addon)                             |
| Fanboy Addon - Notification Thirdparty                     | EasyList Team                        | Thirdparty notifications.                                                                                                                        | [LINK](https://github.com/easylist/easylist/tree/master/fanboy-addon)                             |
| SomeoneWhoCares                                            | Dan Pollock                          | Spyware, certain pop-up traps, user tracking, and most advertising.                                                                              | [LINK](http://someonewhocares.org/hosts/zero)                                                     |
| Fanboy's Enhanced Tracking List                            | EasyList Team                        | Common tracking scripts.                                                                                                                         | [LINK](https://fanboy.co.nz/filters.html)                                                         |
| NoCoin Filter List                                         | hoshsadiq                            | Nrowser based miners such as coin-hive.                                                                                                          | [LINK](https://github.com/hoshsadiq/adblock-nocoin-list)                                          |
| Spam404                                                    | Cameron Dawe                         | Online scams.                                                                                                                                    | [LINK](https://github.com/Spam404/lists)                                                          |

## Credits

| [![ArminC](https://raw.githubusercontent.com/ArmynC/ArminC-Resources/main/images/a_small.png)](https://github.com/ArmynC) | [![Community](https://raw.githubusercontent.com/ArmynC/ArminC-Resources/main/images/community.png)](https://github.com/ArmynC/ArminC-uBlock-Settings#sources)		|
|:------------------------------------------------------------------------------------------------------------------------:	|:------------------------------------------------------------------------------------------------------------------------------------------------------------:		|
|                                                    **Armin Chanchian**                                                   	|                                                                         **The community**                                                                         |

## Support

Reach out to me via **[profile addresses](https://github.com/ArmynC)**.

## License

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0%201.0-lightgrey.svg)](https://tldrlegal.com/license/creative-commons-cc0-1.0-universal)