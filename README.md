![GitHub OpenSource](https://img.shields.io/badge/open%20source-yes-green)![GitHub Maintained](https://img.shields.io/badge/maintained-yes-green)![GitHub last commit](https://img.shields.io/github/last-commit/teamdominant/betterfox)![GitHub issues](https://img.shields.io/github/issues/yokoffing/betterfox)![GitHub closed issues](https://img.shields.io/github/issues-closed/yokoffing/betterfox)![GitHub repo size](https://img.shields.io/github/repo-size/teamdominant/betterfox)[![shields.io Stars](https://img.shields.io/github/stars/yokoffing/betterfox)](https://github.com/yokoffing/betterfox/stargazers)

# Betterfox

> [!WARNING]
> This repo is **Betterfox** fork. \
> Check out the original [repository](https://github.com/yokoffing/Betterfox/).

[about:config](https://support.mozilla.org/en-US/kb/about-config-editor-firefox) tweaks to enhance [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/).

## Required reading

*If you don't have it already: [Get Zen](https://zen-browser.app/download/)*
*However, if you are in doubt about Zen, [Get Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)*

0) Create a [backup profile](https://github.com/yokoffing/Betterfox/wiki/Backup).

1) Download the user.js file [here](https://raw.githubusercontent.com/TeamDominant/Betterfox/main/zen/user.js) (Right click > `Save Link As…`). In case you're using Firefox download it [here](https://raw.githubusercontent.com/TeamDominant/Betterfox/main/user.js).
2) Review [Common Overrides](https://github.com/yokoffing/Betterfox/wiki/Common-Overrides) and make any necessary changes.
   * See also [Optional Hardening](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening) for other recommendations.
   * Do not change [Recommended Overrides](https://github.com/TeamDominant/wiki/Recommended-Overrides) as there is no need to do so, create an [Issue](https://github.com/TeamDominant/Betterfox/issues/) if I'm wrong.
3) Open Firefox. In the URL bar, type `about:profiles` and press **Enter**.
4) For the profile you want to use (or use default), click **Open Folder** in the **Root Directory** section.
5) Close Firefox.
5) Move the `user.js` file into the folder.
7) Open Firefox and make changes in settings if you need.

### Extensions

1) Get an **ad blocker** like [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) with our [recommended filters](https://github.com/yokoffing/filterlists#guidelines).
2) Go to `C:\Program Files\Mozilla Firefox\distribution` and put [policies.json](https://raw.githubusercontent.com/TeamDominant/Betterfox/main/zen/distribution/policies.json) there. In case you're using Firefox download it [here](https://raw.githubusercontent.com/TeamDominant/Betterfox/main/policies.json).
3) Restart again and then check `about:policies`, if you see tweaks there, then you're good to go.
    * You probably don't have distribution, so create it.
    * If your Firefox folder isn't in that path, so find it yourself and do the same steps.

2) *(optional)* Enable **DNS-level protection** with [NextDNS](https://nextdns.io/?from=xujj63g5). <sup><i>Use the link and support this page!</i></sup>
    * Check out our configuration [guide](https://github.com/yokoffing/NextDNS-Config) for the best experience.
    * See how to [quickly enable](https://support.mozilla.org/en-US/kb/dns-over-https) **secure DNS** in Firefox.

## Made for everyday browsing
**A secure, blazing fast browsing experience. Without breakage.**

Betterfox is an opinionated preference list inspired by the [law of diminishing returns](https://miro.medium.com/v2/resize:fit:1206/1*lcOcxriV_II_lZuXQYLoXg.jpeg) and the [minimum effective dose](https://medium.com/the-mission/less-is-more-the-minimum-effective-dose-e6d56625931e).

## Simple configs

`Fastfox`, `Securefox`, `Peskyfox`, and `Smoothfox` are guides to settings within Firefox.

The `user.js` — a configuration file that controls Firefox settings — is curated from these guides.

| List      | Description |
|:---------:|-------------|
| [Fastfox](https://github.com/yokoffing/Betterfox/blob/main/Fastfox.js)   | Increase Firefox's browsing speed. Give Chrome a run for its money!|
| [Securefox](https://github.com/yokoffing/Betterfox/blob/main/Securefox.js) | Protect user data without causing site breakage. |
| [Peskyfox](https://github.com/yokoffing/Betterfox/blob/main/Peskyfox.js)  | Provide a clean, distraction-free browsing experience. |
| [Smoothfox](https://github.com/yokoffing/Betterfox/blob/main/Smoothfox.js) | Get Edge-like smooth scrolling on your favorite browser — or choose something more your style. |
| [user.js](https://github.com/yokoffing/Betterfox/blob/main/user.js) | All the essentials. None of the breakage. This is your `user.js`. |

## Recognition

### Browser Integration
> [!IMPORTANT]
> While the browsers listed below incorporate Betterfox to some extent, they often modify it in ways that reduce its effectiveness. For optimal results, apply the `user.js` file even when using Firefox forks.

* [Zen](https://github.com/zen-browser/desktop?tab=readme-ov-file) | [files](https://github.com/zen-browser/desktop/blob/stable/src/browser/app/profile/zen-browser.js) (July 2024)
* [Midori](https://github.com/goastian/midori-desktop/blob/ESR115/README.md) | [files](https://github.com/goastian/midori-desktop/blob/f3d8d96eb8e08f35a64e3c957bea4e839d7c7730/floorp/browser/components/userjsUtils.sys.mjs#L28-L33) (Dec 2023?)
* [Mercury](https://github.com/Alex313031/Mercury/releases/tag/v.115.3.0) | [files](https://github.com/Alex313031/Mercury/commit/eb9600f9fb8f48c8f5b5c6f3264fbcdb5caff7f5) (Sep 2023)
* [Waterfox](https://www.waterfox.net/en-US/docs/releases/G6.0/) | [files](https://github.com/WaterfoxCo/Waterfox/tree/current/waterfox/browser/app/profile) (Sep 2023)
* [Floorp](https://github.com/Floorp-Projects/Floorp#-betterfox) <sup>[1](https://github.com/Floorp-Projects/Floorp/issues/233#issuecomment-1543557167) [2](https://blog.ablaze.one/3135/2023-04-01/)</sup> | [files](https://github.com/Floorp-Projects/Floorp/blob/ESR115/floorp/browser/components/preferences/userjs.inc.xhtml) (Apr 2023)
* [Pulse](https://github.com/pulse-browser/browser#%EF%B8%8F-credits) | [files](https://github.com/pulse-browser/browser/tree/alpha/src/browser/app/profile) (Dec 2021)
* [Ghostery Private Browser](https://github.com/ghostery/user-agent-desktop#community) <sup>[1](https://web.archive.org/web/20210509171835/https://www.ghostery.com/ghostery-dawn-update-more/) [2](https://web.archive.org/web/20210921114333/https://www.ghostery.com/ghostery-dawn-product-update/)</sup> | [files](https://github.com/ghostery/user-agent-desktop/tree/main/brands/ghostery/branding/pref) (Feb 2021)

## Support

If you like the project, leave a :star: (top right) and become a [stargazer](https://github.com/yokoffing/Betterfox/stargazers)!

[![Stargazers repo roster for @yokoffing/Betterfox](https://reporoster.com/stars/dark/yokoffing/Betterfox)](https://github.com/yokoffing/Betterfox/stargazers)

<a href='https://ko-fi.com/Q5Q5G8EPH' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
<noscript><a href="https://liberapay.com/yokoffing/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>

## Credit
* Modified by [prettyleaf](https://github.com/prettyleaf) for everyday usage and perfomance. [Buy me a coffee.](https://www.donationalerts.com/r/pr3ttyleaf)
* Betterfox mirrors the ongoing work provided by [arkenfox](https://github.com/arkenfox/user.js). Additionally, this repository includes content reproduced or adapted from other sources. Credit for overlapping material goes to the original authors.
* Appreciation goes to the [Firefox](https://www.mozilla.org/en-US/firefox/new/) team and developers working on [Bugzilla](https://bugzilla.mozilla.org/home), fighting for the open web.
* Thanks to [Denperidge](https://github.com/Denperidge) for adding [`install.py`](https://github.com/yokoffing/Betterfox/blob/main/install.py) for advanced users in v.131.
* A special thanks to [Alex Kontos](https://github.com/MrAlex94) of [Waterfox](https://github.com/WaterfoxCo/Waterfox) for his collaboration in v.116.
* Many thanks to the 2021 [Ghostery](https://github.com/ghostery) team for testing Betterfox at scale in its early days.

<div align='center'>
  <a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=59870&s=1' border='0' alt='Free Website Counter'></a><br / >
since 23 July 2022</div>
