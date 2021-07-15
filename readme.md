# FreshRSS Extensions

A collection of FreshRSS extensions found around the web.

## Why?

For ease of installation and updates.

## Already available via semi-supported repo

The following extensions are available in
[FreshRSS/Extensions](https://github.com/FreshRSS/Extensions) repository.

* CustomCSS
* CustomJS
* ImageProxy
* QuickCollapse
* ReadingTime
* ShareByEmail
* StickyFeeds
* TitleWrap
* TTRSS_API

Some of the following extensions were found in the readme of that repository.

## Managed

These extensions are added as submodules to this repository.

This repository manages the installation and updating of these extensions.

Removing extensions is not supported. You will need to manually delete them
from the `extensions` directory.

* [ClickableLinks](https://github.com/kapdap/freshrss-extensions.git)
* [DateFormat](https://github.com/aledeg/xExtension-DateFormat.git)
* [Dilbert](https://github.com/kevinpapst/freshrss-dilbert.git)
* [Explosm](https://framagit.org/dohseven/freshrss-explosm.git)
* [FixedNavMenu](https://github.com/langfeld/FreshRSS-extensions.git)
* [KeepFolderState](https://github.com/langfeld/FreshRSS-extensions.git)
* [LatexSupport](https://github.com/aledeg/xExtension-LatexSupport.git)
* [MobileScrollMenu](https://github.com/langfeld/FreshRSS-extensions.git)
* [RedditImage](https://github.com/aledeg/xExtension-RedditImage.git)
* [RSS-Bridge](https://github.com/DevonHess/FreshRSS-Extensions.git)
* [SmartMobileMenu](https://github.com/langfeld/FreshRSS-extensions.git)
* [TouchControl](https://github.com/langfeld/FreshRSS-extensions.git)
* [YouTube](https://github.com/kevinpapst/freshrss-youtube.git)

The install script knows what to install based on the final word in parens.

* **(repo)** means the entire repo is a single extension and should be copied
  as is (minus any git related files)
* **(dir)** means the repository holds one or more extensions and to look in
  the directory named in the first part of link.

Extensions will be copied to `/usr/share/webapps/freshrss/extensions` as
`xExtension-[linkname]`. These files need to be owned by root, so a sudo call
will be made.
