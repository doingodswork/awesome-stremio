# Awesome Stremio [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome tools and addons for Stremio

## Contents

1. [Stremio official](#stremio-official)
2. [Unofficial communities](#unofficial-communities)
3. [Tools](#tools)
4. [Addons](#addons)
    1. [Movies & TV shows](#Movies--TV-shows)
    2. [Live TV](#Live-TV)
    3. [Podcasts](#Podcasts)
    4. [Subtitles](#subtitles)
    5. [Catalogs](#catalogs)
5. [Tutorials](#tutorials)
6. [Addon Developer Resources](#Addon-Developer-Resources)
7. [Contribute](#contribute)
8. [License](#license)

## Stremio official

Links to official Stremio resources:

- [Website](https://www.stremio.com/)
- [Blog](https://blog.strem.io/)
- [Support](https://stremio.zendesk.com/)
- [Bugs](https://github.com/Stremio/stremio-bugs)
- [Feature requests](https://github.com/Stremio/stremio-features)
- [Community addons collection](https://api.strem.io/addonscollection.json)

Community:

- [Facebook](https://www.facebook.com/stremio/)
- [Twitter](https://twitter.com/stremio)
- [Instagram](https://www.instagram.com/stremioofficial/)
- [Reddit](https://www.reddit.com/r/Stremio/)

Open source code:

- [Stremio Core](https://github.com/Stremio/stremio-core/tree/development)
- [Stremio Desktop](https://github.com/stremio/stremio-shell)
- [Stremio Web](https://github.com/stremio/stremio-web)
- [Addon SDK](https://github.com/Stremio/stremio-addon-sdk)

## Unofficial communities

- [Stremio addon subreddit](https://www.reddit.com/r/StremioAddons/)
- [Discord chat](https://discord.gg/zNRf6YF)
- [Stremio addon Facebook page](https://www.facebook.com/StremioAddons/)
- [Stremio Facebook group](https://www.facebook.com/groups/stremio/)

## Tools

Official:

- [Addon publishing helper](https://stremio.github.io/stremio-publish-addon/index.html)
- [Catalog builder](https://stremio.github.io/stremio-catalog-builder/)

3rd party:

- [Flatpak package](https://github.com/bilelmoussaoui/stremio-flatpak): Stremio installer for systems with [Flatpak](https://flatpak.org/)
- [Flatpak package](https://github.com/p1u3o/com.stremio.Stremio): Same
- [Stremio Downloader](https://github.com/BurningSands70/stremio-downloader): Allows you to download streams from Stremio
- [Stremio Install Scripts](https://github.com/alexandru-balan/Stremio-Install-Scripts): Scripts that are meant to install Stremio and its dependencies on systems that do not provide an official installation for Stremio
- [Stremio-RaspberryPi](https://github.com/shivasiddharth/Stremio-RaspberryPi): Helps you to run Stremio on a Raspberry Pi
- [PimpMyStremio (aka "PMS")](https://github.com/sungshon/PimpMyStremio): Local addon manager for Stremio; allows you to run addons that don't work with the regular Stremio
  - [Addon list including links to their GitHub repository](https://github.com/sungshon/PimpMyStremio/blob/master/src/addonsList.json)
  - [Reddit post with further info](https://www.reddit.com/r/Stremio/comments/db9qmn/what_is_pimpmystremio_xpost_from_rstremioaddons/)
  - [Tutorial for running PMS on Android](https://gist.github.com/sleeyax/e9635eb352a4fcdf94194f763d743689)

## Addons

This list here focuses on open source addons, linking the source code repositories. For a list of addons that aren't necessarily open source check <https://github.com/danamag/stremio-addons-list>, which is the successor of the addon list that was maintained on the [r/StremioAddons](https://www.reddit.com/r/StremioAddons/) subreddit in the past.

### Movies & TV shows

Torrent and HTTP streams:

- [Orion](https://github.com/gorlev/orion-stremio-addon): Torrent and Debrid addon with Orion as source and support for multiple debrid services (via Orion: RealDebrid, Premiumize, Offcloud)
- [Torrentio](https://github.com/TheBeastLT/torrentio-scraper): Torrent and Debrid addon with multiple sources (YTS, EZTV, RARBG, 1337x, ThePirateBay, KickassTorrents, HorribleSubs) and support for multiple debrid services (RealDebrid, AllDebrid, Premiumize, Put.io, DebridLink)

HTTP streams only (no P2P uploading):

- [Animes Brasil](https://github.com/mrcanelas/anime-tv-addon): Anime addon for brazilian portuguese (dubbed and subbed)
- [Deflix](https://github.com/doingodswork/deflix-stremio): Debrid addon with multiple sources (YTS, The Pirate Bay, RARBG, 1337x and ibit) and support for multiple debrid services (RealDebrid, AllDebrid, Premiumize), written in Go
- [Lobo Guara Series](https://github.com/mrcanelas/lobo-guara-addon): Addon for dubbed TV Shows in brazilian portuguese

Torrent streams:

- [1337x torrents](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/1337x-torrents): Torrent addon for 1337x
- [HorribleSubs](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/horriblesubs): Anime torrents
- [Juan Carlos 2](https://github.com/JCB9090/juan-carlos-torrents-2): Torrent addon for KAT.cr and torrentz.eu
- [Mico leão dublado](https://github.com/fadoaglauss/stremio-brazilian-addon): Addon for dubbed movies in brazilian portuguese (PT-BR) with multiple sources
- [pct](https://github.com/JCB9090/pct-addon): Torrent addon for EZTV and YTS
- [Piratebay](https://github.com/ThanosDi/piratebay-stremio-addon): Torrent addon for The Pirate Bay
- [RARBG torrents](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/rarbg-torrents): Torrent addon for RARBG
- [rarbg](https://github.com/sebastiencs/rarbg-addon): Torrent addon for RARBG
- [Stream Quality Filter (aka "SQF")](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/stream-quality-filter): Fetches streams from RARBG, 1337x, YTS and TPB+ addons, removes duplicates and sorts them by quality
- [ThePirateBay+](https://github.com/TheBeastLT/stremio-thepiratebay-plus): Torrent addon for The Pirate Bay

### Live TV

- [dlive.tv](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/dlive): Live streams from dlive.tv

### Podcasts

- [podcasts](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/podcasts)
- [podcasts-for-all](https://github.com/NivM1/podcasts-for-all)

### Subtitles

- [OpenSubtitles (*official* addon)](https://github.com/Stremio/stremio-opensubtitles): Adds subtitles from [OpenSubtitles](https://www.opensubtitles.org) to your stream

### Catalogs

- [IMDb list](https://github.com/jaruba/stremio-imdb-list): Allows you to use any IMDb list as catalog
- [IMDb tag](https://github.com/jaruba/stremio-imdb-tag): Allows you to dynamically create a catalog from an IMDb tag
- [Kitsu animes](https://github.com/TheBeastLT/stremio-kitsu-anime): Provides several [Kitsu](https://kitsu.io) anime catalogs (All, Top Rated, Most Popular, Trending) and metadata for them
- [Top movies](https://github.com/doingodswork/stremio-top-movies): Contains multiple catalogs of top movies: IMDb Top 250, IMDb Most Popular, Top Box Office, Rotten Tomatoes Certified Fresh Movies, Academy Award for Best Picture, Cannes Film Festival Palme, Venice Film Festival Golden Lion, Berlin International Film Festival Golden Bear

## Tutorials

- [How to download movies/series on android](https://www.reddit.com/r/StremioAddons/comments/ekwj5x/how_to_download_moviesseries_on_android/)

## Addon Developer Resources

SDKs:

- [Official addon SDK](https://github.com/Stremio/stremio-addon-sdk)
- [Addon SDK for Rust](https://github.com/sleeyax/stremio-addon-sdk): Rust version of the stremio-addon-sdk using stremio-core
- [Addon SDK for Go](https://github.com/Deflix-tv/go-stremio): Stremio addon SDK for Go

Examples using those SDKs:

- Node.js
  - [Hello World Addon](https://github.com/Stremio/addon-helloworld): also includes a step by step tutorial
  - [IGDB Addon](https://github.com/Stremio/stremio-igdb-addon/tree/tutorial)
- Rust
  - [Example Addon](https://github.com/sleeyax/stremio-addon-sdk/tree/master/example-addon)
- Go
  - [Examples for a catalog addon and a stream addon](https://github.com/Deflix-tv/go-stremio/tree/master/examples)

Examples not using any SDK:

- [PHP Addon Example & Tutorial](https://github.com/Stremio/stremio-php-addon-example)
- [Go Addon Example](https://github.com/Stremio/addon-helloworld-go)
- [Python Addon Example & Tutorial](https://github.com/Stremio/addon-helloworld-python)
- [Ruby Addon Example & Tutorial](https://github.com/Stremio/addon-helloworld-ruby)
- [C# Addon Example](https://github.com/Stremio/addon-helloworld-csharp)
- [Node.js Express Addon Example & Tutorial](https://github.com/Stremio/addon-helloworld-express)
- [Node.js Express Addon Example Using User Data](https://github.com/Stremio/stremio-addon-sdk/blob/master/docs/advanced.md)
- [IMDB Lists - Node.js Express Addon Using User Data and Ajax Calls](https://github.com/jaruba/stremio-imdb-list)
- [IMDB Watchlist - Node.js Express Addon Using User Data and Proxying Another Stremio Addon](https://github.com/jaruba/stremio-imdb-watchlist)
- [Jackett Addon - Node.js Express Addon Using User Data](https://github.com/BoredLama/stremio-jackett-addon)

Guides:

- [Official SDK guide](https://stremio.github.io/stremio-addon-guide/sdk-guide/prelude)
- [Official generic guide](https://stremio.github.io/stremio-addon-guide/basics)

Video tutorials:

- [Building a Stremio addon](https://www.youtube.com/watch?v=ULLqhPJl2v0)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, doingodswork has waived all copyright and
related or neighboring rights to this work.
