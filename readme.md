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

You will need to manually delete them from the `extensions` directory.

* [ClickableLinks](https://github.com/kapdap/freshrss-extensions.git) (dir)
* [DateFormat](https://github.com/aledeg/xExtension-DateFormat.git) (repo)
* [Dilbert](https://github.com/kevinpapst/freshrss-dilbert.git) (dir)
* [Explosm](https://framagit.org/dohseven/freshrss-explosm.git) (dir)
* [FixedNavMenu](https://github.com/langfeld/FreshRSS-extensions.git) (dir)
* [KeepFolderState](https://github.com/langfeld/FreshRSS-extensions.git) (dir)
* [LatexSupport](https://github.com/aledeg/xExtension-LatexSupport.git) (repo)
* [MobileScrollMenu](https://github.com/langfeld/FreshRSS-extensions.git) (dir)
* [RedditImage](https://github.com/aledeg/xExtension-RedditImage.git) (repo)
* [RSS-Bridge](https://github.com/DevonHess/FreshRSS-Extensions.git) (dir)
* [SmartMobileMenu](https://github.com/langfeld/FreshRSS-extensions.git) (dir)
* [TouchControl](https://github.com/langfeld/FreshRSS-extensions.git) (dir)
* [YouTube](https://github.com/kevinpapst/freshrss-youtube.git) (dir)

The install script knows what to install based on the final word in parens.

* **(repo)** means the entire repo is a single extension and should be copied
  as is (minus any git related files)
* **(dir)** means the repository holds one or more extensions and to look in
  the directory named in the first part of link.

Extensions will be copied to `/usr/share/webapps/freshrss/extensions` as
`xExtension-[linkname]`. These files need to be owned by root, so a sudo call
will be made.

### Add a new extension

Add an entry to the list above.

`git submodule add <repo link>`



### Update an extension

#### Update all extensions

### Remove an extension
