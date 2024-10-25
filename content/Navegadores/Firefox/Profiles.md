## Titulo: Profiles 
**fecha**: 2024-09-05 
**tags**: [#util #navegador #profile #respaldo #browser #firefox ]

# Profiles

_If you don't have it already: [Get Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)_

0. Create a [[Backup Profile]]
1. Download the user.js file [here](https://raw.githubusercontent.com/yokoffing/Betterfox/main/user.js) (Right click > `Save Link As…`).
2. Review [Common Overrides](https://github.com/yokoffing/Betterfox/wiki/Common-Overrides) and make any necessary changes.
    - See also [Optional Hardening](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening) for other recommendations.
3. Open Firefox. In the URL bar, type `about:profiles` and press **Enter**.
4. For the profile you want to use (or use default), click **Open Folder** in the **Root Directory** section.
5. Move the `user.js` file into the folder.

_After restarting Firefox:_

1. Get an **ad blocker** like [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) with our [recommended filters](https://github.com/yokoffing/filterlists#guidelines).
2. Enable **DNS-level protection** with [NextDNS](https://nextdns.io/?from=xujj63g5). _Use the link and support this page!_
    - Check out our configuration [guide](https://github.com/yokoffing/NextDNS-Config) for the best experience.
    - See how to [quickly enable](https://support.mozilla.org/en-US/kb/dns-over-https) **secure DNS** in Firefox.

## Simple goals
1. **Minimalism:** get what isn't needed out of the way
2. **Efficiency:** unleash Firefox's ability to be fast and performant
3. **Privacy:** protect your data without causing site breakage

Configurations

`Fastfox`, `Securefox`, `Peskyfox`, and `Smoothfox` are guides to settings within Firefox.

The `user.js` — a configuration file that controls Firefox settings — is curated from these guides.

|List|Description|
|:-:|---|
|[Fastfox](https://github.com/yokoffing/Betterfox/blob/main/Fastfox.js)|Increase Firefox's browsing speed. Give Chrome a run for its money!|
|[Securefox](https://github.com/yokoffing/Betterfox/blob/main/Securefox.js)|Protect user data without causing site breakage.|
|[Peskyfox](https://github.com/yokoffing/Betterfox/blob/main/Peskyfox.js)|Provide a clean, distraction-free browsing experience.|
|[Smoothfox](https://github.com/yokoffing/Betterfox/blob/main/Smoothfox.js)|Get Edge-like smooth scrolling on your favorite browser — or choose something more your style.|
|[user.js](https://github.com/yokoffing/Betterfox/blob/main/user.js)|All the essentials. None of the breakage. This is your `user.js`.|
