# CHEF-KOCH's Filter List [![Build Status](https://travis-ci.org/CHEF-KOCH/CKs-FilterList.svg?branch=master)](https://travis-ci.org/CHEF-KOCH/CKs-FilterList)

CK's Filter List was created 2018 because I didn't liked the well-known filter lists and I think they're often outdated or _incomplete_ and simply too inefficient. My list is not restricted by any region and the main-focus is english, russian, swiss and germany regions since I speak these languages.



## Project Goal(s)

#### Intro 

The overall project goal is to block ads and reduce the traffic coming from the domains/websites you visit. The term 'ads' is not defined in this project because I also block cosmetically banners and popup stuff which I think only causes useless traffic without any real benefit.

#### Short explanation
* Reduce traffic
* Reduce page loading times
* Remove annoyance web elements like e.g. floating headers, banners or useless footers
* Provide list in order to block connections to bigger corps. e.g. Apple.
* [Get rid of malware](https://threatpost.com/malvertising-ransomware-vidar/140641/).


## Meme

<p align="center">
  <img width="480" height="430" src="https://i.imgur.com/rlEFwae.png">
</p>

[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/fold_left.svg?style=social&label=Follow%20%40CHEF-KOCH)](https://twitter.com/CKsTechNews)
[![Discord](https://img.shields.io/discord/418256415874875402.svg?colorA=7289da&colorB=99aab5&label=Discord&logo=discord&maxAge=60)](https://discord.me/CHEF-KOCH)
<img src="http://img.shields.io/liberapay/receives/CHEF-KOCH.svg?logo=liberapay">
<noscript><a href="https://liberapay.com/CHEF-KOCH/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>



## Important information about filter usage

**Site-specific or filter-based extensions such as AdBlock Plus, Request Policy, Ghostery, Priv3 and Sharemenot are in general to be avoided**. According to my own security expertise and [history](https://www.menlosecurity.com/blog/a-jar-full-of-problems-for-financial-services-companies-1?hs_preview=fnfbcEyu-6824107036) I can guarantee that these extensions do not add any real privacy layer to the Browser by itself - a proper implementation of the privacy requirements and development efforts on the Browser directly should be preferred on general solutions that prevent tracking by all third parties, rather than a list of specific URLs or hosts.

[I do not recommend using any filter lists](https://github.com/CHEF-KOCH/CKs-FilterList/wiki/Information-about-filter-usage), instead I highly recommend to work with whitelist only which are based on your own needs. However, a filter lists can help to reduce a possible attack surface based on the daily browsing habits.

**DO NOT** combine Anti-Corp list with the normal filters and **DO NOT** use anti-corp HOSTS lists together with anti-corp filters in both uBO and uM - that only takes more memory and results in higher loading times with no benefit. Use the anti-corp list in either uBO or uM. 

:arrow_right: Please use the HOSTS filters for domain/dns based blocking and the filter lists for cosmetical blocking. AdGuard, uBO & Co. can also block entire domains but I like to separate the list to avoid redundancies. 



# Integration into other filter lists

It's cool that some people add my lists into _their own projects_ and I in general allow it but it's not cool that several people make some money via donations with my and other peoples lists. **I DO NOT ALLOW** any commercial usage - this also includes donations! Everyone which doesn't respect this will get a DMCA takedown request and a paper from my lawyer.



## General Project Structure

* `CONTRIBUTING.md` is the file which shows you how to contribute to the project. It's essentially that you read the guidelines before you submit something.
* `Readme.md` is this file and is the general project overview file.
* `ToDo.md` is like the name already suggest the current todo list - same as the CONTRIBUTING.md it [needs to be read](https://github.com/CHEF-KOCH/CKs-FilterList/wiki/Filter-Policy-&-Issue-Tickets) before you submit something. 

#### Main Filter
* The main list `/CK's-FilterList.txt` which will be loaded by your fav. Ad-Blocker extension. The filter gets updated at least every 8 days. The list contains all other lists!
* `CK's-FilterList-slimm.txt` is only the normal filter lists without any additional _sublists_.


* [CHEF-KOCH's FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/CK's-FilterList.txt&title=CHEF-KOCH's-Filter-List) - Click-to-install in order to sub the filter list via your Browser.


* [CHEF-KOCH's FilterList (slimm)](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/CK's-FilterList-slimm.txt&title=CHEF-KOCH's-Filter-List) - Click-to-install in order to sub the filter list via your Browser.


##### uBO, Adblock etc filters

* `/filters` Other sub-filters belong into this folder.


##### I2P & Onion
* `/I2P & Onion` includes the I2P and .Onion related filter list `CK's-Onion-FilterList`.


##### Spotify
* `/Spotify Ad-Free` includes Spotify ad-blocking filters resources.


##### HOSTS

* `/HOSTS` includes all (optional) lists as HOSTS compatible format.


##### Test

* `/Test` includes multiple test filters for IP/ASN and uBlock + uMatrix rulesets.



## Supported Ad-Blockers

Make sure you have an ad-blocker installed in your desktop or mobile browsers that uses [Adblock Plus](https://adblockplus.org/) filter syntax:
* ![AdAway](https://i.imgur.com/AdWsIxw.png) [AdAway](https://github.com/AdAway/AdAway) - for **Android** only (partial supported)
* ![Blackada](https://i.imgur.com/XB1l9aG.png?1) [Blockada](http://blokada.org/) - for **Android** only
* ![DNS66](https://i.imgur.com/FET3qmb.png) [DNS66](https://github.com/julian-klode/dns66) - for **Android** only
* ![uBock Origin](https://i.imgur.com/PSFuzKb.png) [uBlock Origin](https://github.com/gorhill/uBlock) or [Nano Adblocker](https://github.com/NanoAdblocker/NanoCore) - for **Browsers** as extension only
* ![AdGuard Browser Extension](https://i.imgur.com/zmMHq2j.png) [AdGuard](https://adguard.com/en/adguard-browser-extension/overview.html) - for **All Platforms** 
* ![pfSense](https://i.imgur.com/ElyO5Ie.png) [pfSense](https://www.pfsense.org/) with [pfBlockerNG](https://www.tecmint.com/install-configure-pfblockerng-dns-black-listing-in-pfsense/)
* ![Pi-hole](https://i.imgur.com/0mgKKma.png) [Pi-hole](https://pi-hole.net) - for **PI devices** 
* ![Gasmask](https://i.imgur.com/vVumrpf.png) [Gasmask](https://github.com/2ndalpha/gasmask) - for **OS X**



## Partial supported 

The following blockers aren't fully supported, so they might work but they have some limitations and I personally can't recommend them. A more detailed explanation is given [here](https://github.com/CHEF-KOCH/CKs-FilterList/wiki/Limited-support-for-AdBlock-&-AdBlock-Plus).


* ![AdBlock](https://i.imgur.com/3KbyifF.png) [AdBlock](https://getadblock.com) - for **All Platforms** 
* ![AdBlock Plus](https://i.imgur.com/kPRCfhu.png) [Adblock Plus](https://adblockplus.org/) - for **Browsers** as extension only
* <img src="https://1blocker.com/img/icon.png" width=16> [1Blocker](https://1blocker.com) for **iOS or MacOS** devices only
* ![AdBlock Browser](https://i.imgur.com/6pkmjA0.png) [Adblock Browser](https://adblockbrowser.org/) - for **Android** and **iOS** devices only
* ![Brave Browser](https://user-images.githubusercontent.com/831718/32730079-e80c013c-c853-11e7-83b4-7443bc489581.png) [Brave Browser](https://www.brave.com) - (partial supported, request to add the list send)
* ![Opera Browser](https://i.imgur.com/bP0t9xc.png) [Opera Browser](https://www.opera.com) - (partial supported, request to add the list send)



## Documentation

For a more detailed project description and documentation please see the [Wiki pages](https://github.com/CHEF-KOCH/CKs-FilterList/wiki).



## Optional lists

The following filters might not getting into the main filter list (_CK's-FilterList.txt_) and are labeled as [optional](https://github.com/CHEF-KOCH/CKs-FilterList#optional-lists), there also not getting as fast updates, their update interval is set to 14 days. 



### Filter Lists (click to install)

Filter Name | Description | Sub link
--- | --- | ---
Ad & Tracker Filter List | Blocks known Ads & Trackers | [CHEF-KOCH's Ad & Tracker Filter List](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/ads-tracker.txt&title=CHEF-KOCH's-Ad-&-Trackers-Filter-List)
Android | Blocks ads & trackers and other unneeded Android traffic | [CHEF-KOCH's Android FilterList](https://subscribe.adblockplus.org/?location=https://github.com/CHEF-KOCH/CKs-FilterList/blob/master/filters/android.txt&title=CHEF-KOCH's-Android-Filter-List)
Adobe | Blocks all Adobe traffic | [CHEF-KOCH's Adobe FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/adobe.txt&title=CHEF-KOCH's-Adobe-Filter-List)
Apple | Blocks all Apple traffic | [CHEF-KOCH's Apple FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/apple.txt&title=CHEF-KOCH's-Apple-Filter-List)
Avast/CCleaner | Blocks all Avast/CCleaner traffic | [CHEF-KOCH's Avast/CCleaner FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/ccleaner.txt&title=CHEF-KOCH's-CCleaner-Filter-List)
Cloudflare | Blocks all Cloudflare traffic | [CHEF-KOCH's Cloudflare FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/cloudflare.txt&title=CHEF-KOCH's-Cloudflare-Filter-List)
Facebook | Blocks all Facebook & services traffic | [CHEF-KOCH's Facebook FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/facebook.txt&title=CHEF-KOCH's-Facebook-Filter-List)
Google | Blocks all Google & services traffic | [CHEF-KOCH's Google FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/google.txt&title=CHEF-KOCH's-Google-Filter-List)
Instagram | Blocks all Instagram & services traffic | [CHEF-KOCH's Instagram FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/instagram.txt&title=CHEF-KOCH's-Instagram-Filter-List)
Microsoft | Blocks all Microsoft & services traffic | [CHEF-KOCH's Microsoft FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/microsoft.txt&title=CHEF-KOCH's-Microsoft-Filter-List)
Mozilla | Blocks all Mozilla & services traffic | [CHEF-KOCH's Mozilla FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/mozilla.txt&title=CHEF-KOCH's-Mozilla-Filter-List)
Pinterest | Blocks all Pinterest & services traffic | [CHEF-KOCH's Pinterest FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/pinterest.txt&title=CHEF-KOCH's-Pinterest-Filter-List)
App: Skype | Skype Ad-Free | [CHEF-KOCH's Skype Ad-Free FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/skype.txt&title=CHEF-KOCH's-Skype-Ad-Free-Filter-List)
App: Spotify | Spotify Ad-Free | [CHEF-KOCH's Spotify Ad-Free FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/Spotify/Spotify-AdBlock.txt&title=CHEF-KOCH's-Spotify-Ad-Free-Filter-List)
Fonts | Block all web fonts | [CHEF-KOCH's Fonts FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/fonts.txt&title=CHEF-KOCH's-Fonts-Filter-List)
I2P & Onion | Blocklist for bad I2P & Onion domains (not for ad-blockers!) | [CHEF-KOCH's I2P & Onion FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/Onion/Onion-FilterList.txt&title=CHEF-KOCH's-I2P-&-Onion-Filter-List)
Malware | Blocklist for Malware | [CHEF-KOCH's Malware FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/malware.txt&title=CHEF-KOCH's-I2P-&-Onion-Filter-List)
Wontblock | Unblock the Internet and good pages | [CHEF-KOCH's Wontblock FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/Not%20blocked/CK's-Wontblock-FilterList.txt&title=CHEF-KOCH's-I2P-&-Onion-Filter-List)
Torrent | Blocklist for bad Torrent Tracker | [CHEF-KOCH's Torrent FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/torrent-tracker.txt&title=CHEF-KOCH's-I2P-&-Onion-Filter-List)
CoinMiners | Block all crypto coin miners | [CHEF-KOCH's CoinMiner FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/filters/coinminer.txt&title=CHEF-KOCH's-Fonts-Filter-List)




### uMatrix & HOSTS only optional filter lists.


HOSTS and uMatrix only filter lists - please keep in mind that _there not sub-clickable_ (like the above uBO list). There will also be [no 127.0.0.1 versions](https://github.com/CHEF-KOCH/CKs-FilterList/wiki/127.0.0.1-vs-0.0.0.0). 


Filter Name | Description | Sub link
--- | --- | ---
Ad & Tracker Filter List | Blocks additional Ads & Trackers | [CHEF-KOCH's Ad & Tracker FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Ads-tracker.txt&title=CHEF-KOCH's-Ad-&-Trackers-Filter-List)
Adguard | Blocks AdGuard related traffic | [CHEF-KOCH's Adguard FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/AdGuard.txt&title=CHEF-KOCH's-Adguard-Filter-List)
Adobe | Blocks all Adobe traffic | [CHEF-KOCH's Adobe FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Adobe.txt&title=CHEF-KOCH's-Adobe-Filter-List)
Apple | Blocks all Apple traffic | [CHEF-KOCH's Apple FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Apple.txt&title=CHEF-KOCH's-Apple-Filter-List)
Avast/CCleaner | Blocks all Avast/CCleaner traffic | [CHEF-KOCH's Avast/CCleaner FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/CCleaner.txt&title=CHEF-KOCH's-CCleaner-Filter-List)
Cloudflare | Blocks all Cloudflare traffic | [CHEF-KOCH's Cloudflare FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Cloudflare.txt&title=CHEF-KOCH's-Cloudflare-Filter-List)
Facebook | Blocks all Facebook traffic | [CHEF-KOCH's Facebook FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Facebook.txt&title=CHEF-KOCH's-Facebook-Filter-List)
Google | Blocks all Google & services traffic | [CHEF-KOCH's Google FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Google.txt&title=CHEF-KOCH's-Google-Filter-List)
Instagram | Blocks all Instagram & services traffic | [CHEF-KOCH's Instagram FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Instagram.txt&title=CHEF-KOCH's-Instagram-Filter-List)
Microsoft | Blocks all Microsoft & services traffic | [CHEF-KOCH's Microsoft FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Microsoft.txt&title=CHEF-KOCH's-Microsoft-Filter-List)
Mozilla | Blocks all Mozilla & services traffic | [CHEF-KOCH's Mozilla FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Mozilla.txt&title=CHEF-KOCH's-Mozilla-Filter-List)
NSA,FBI,CIA | Blocks all NSA, CIA, FBI etc 'spying' server connections | [CHEF-KOCH's NSA FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/NSABlocklist.txt&title=CHEF-KOCH's-Mozilla-Filter-List)
Pinterest | Blocks all Pinterest & services traffic | [CHEF-KOCH's Pinterest FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Pinterest.txt&title=CHEF-KOCH's-Pinterest-Filter-List)
App: Skype | Skype Ad-Free | [CHEF-KOCH's Skype Ad-Free FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Skype.txt&title=CHEF-KOCH's-Skype-Ad-Free-Filter-List)
App: Spotify | Spotify Ad-Free | [CHEF-KOCH's Spotify Ad-Free FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/Spotify/Spotify-HOSTS.txt&title=CHEF-KOCH's-Spotify-Ad-Free-Filter-List)
uMatrix | uMatrix / HOSTS based lists (only for uMatrix users!)| [CHEF-KOCH's uMatrix FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/uMatrix/CK's-uMatrix-FilterList.txt&title=CHEF-KOCH's-Spotify-Ad-Free-Filter-List)
Game List | Blocks additional game tracking | [CHEF-KOCH's Game FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Game.txt&title=CHEF-KOCH's-Game-Filter-List)
CoinMiners | Block all crypto coin miners | [CHEF-KOCH's CoinMiner FilterList](https://subscribe.adblockplus.org/?location=https://raw.githubusercontent.com/CHEF-KOCH/CKs-FilterList/master/HOSTS/Coinminer.txt&title=CHEF-KOCH's-Fonts-Filter-List)


## Report issues, unblocked ads or trackers

You can report issue [here](https://github.com/CHEF-KOCH/CKs-FilterList/issues), keep in mind that this requires that you read the [contribution guidelines](https://github.com/CHEF-KOCH/CKs-FilterList/blob/master/CONTRIBUTING.md) first.  


#### Like the list? 

Star it on GitHub! :star: or consider making a [donation](https://github.com/CHEF-KOCH/Donations). :muscle:


## Credits 

:construction: The following people contributed to CK's Filter List in order to improve the project. :construction:
* The-Commissioner
* @AddaxSoft
* @ZeroDot1
* @bogachenko


## License

The project and it's content of CHEF-KOCH's Filter List is licensed under a [ISC License](https://github.com/CHEF-KOCH/CKs-FilterList/blob/master/LICENSE).
