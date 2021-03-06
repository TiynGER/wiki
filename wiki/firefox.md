# Firefox

[Firefox](https://www.mozilla.org/en-US/firefox) is a free and open-source web
browser.

## List of useful Firefox addons

Following is a list of useful Firefox addons.
They can be removed and configured under `about:config`.

- [ClearURLs](https://addons.mozilla.org/en-GB/firefox/addon/clearurls) removes
  tracking elements from URLs.
- [Dark Reader](https://addons.mozilla.org/en-GB/firefox/addon/darkreader) creates
  an automatic dark mode for sites without native dark mode.
- [Firefox Multi-Account Containers](https://addons.mozilla.org/en-GB/firefox/addon/multi-account-containers)
  lets you separate cookies in different containers on a per site base.
- [Floccus](https://addons.mozilla.org/en-US/firefox/addon/floccus/) syncs your
  bookmarks across devices (supports Nextcloud and WebDAV (ownCloud, etc)).
- [hide-scrollbars](https://addons.mozilla.org/en-GB/firefox/addon/hide-scrollbars)
  hides scrollbars.
- [Never-Consent](https://addons.mozilla.org/en-GB/firefox/addon/never-consent)
  automatically refuses GDPR consent to a bunch of platforms.
- [NoScript](https://addons.mozilla.org/en-GB/firefox/addon/noscript) blocks all
  javascript so that the parts you need can be reenabled and the rest is not used.
- [Privacy Badger](https://addons.mozilla.org/en-GB/firefox/addon/privacy-badger17)
  blocks unwanted invisible trackers.
- [Privacy Redirect](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect/)
  redirects youtube, instagram, twitter, etc to free alternatives or alternative
  frontends.
- [Temporary Containers](https://addons.mozilla.org/en-GB/firefox/addon/temporary-containers)
  opens tabs and websites, that are not already managed by
  `Firefox Multi-Account Containers` in a new container.
- [uBlock Origin](https://addons.mozilla.org/en-GB/firefox/addon/ublock-origin)
  blocks unwanted content like ads.
- [User-Agent Switcher and Manager](https://addons.mozilla.org/en-GB/firefox/addon/user-agent-string-switcher)
  spoofs websites that try to gather information about your webbrowser.
- [Vim Vixen](https://addons.mozilla.org/en-GB/firefox/addon/vim-vixen) enables
  vim movement for firefox.
- Plugins for Tabs, etc. in tree style:
  - [Sidebery](https://addons.mozilla.org/en-GB/firefox/addon/sidebery)
    is a sidebar with treestyle tabs and bookmarks.
  - [Tree Style Tab](https://addons.mozilla.org/en-GB/firefox/addon/tree-style-tab)
    shows tabs like a tree. This is especially useful if many tabs are used.

## Useful configuration

To disable the telemetry of firefox navigate to `about:telemetry` and (if it says
enabled) click on `enabled` and disable all the options.

To disable ads from firefox navigate to `about:config`, search for
`browser.newtabpage.activity-stream.showSponsored` and disable all upcoming results.

On Linux distributions auto scroll is disabled by default.
This means that you cant click the middle mouse button to use it for scrolling.
To enable it go into the preferences and check `Use autoscrolling`.

## Add a new search engine

You can add a new search engine with the addon `Add custom search engine`.
Make sure to replace `<url to search engine>` with the according url.

It is possible to add it without an addon.
Navigate to the search engine and click the `...` in the address bar.
Then click `Add Search Engine`
