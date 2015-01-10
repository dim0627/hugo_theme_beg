+++
title = "About Beg"
description = ""
tags = [
    "hugo",
    "beg",
]
date = "2015-01-10"
+++

[Beg](https://github.com/dim0627/hugo_theme_beg) is the theme for [Hugo](http://gohugo.io/).

## Install hugo

Please read [Hugo Quickstart Guide](http://gohugo.io/overview/quickstart/).

## Install beg

Please clone from my repository.

``` sh
mkdir themes
cd themes
git clone https://github.com/dim0627/hugo_theme_beg
```

## Run with beg

``` sh
hugo server -t beg
```

<!--more-->

## Configuration

``` yaml
BaseUrl: "http://yet.unresolved.xyz"
LanguageCode: "en-us"
Title: "Beg"

Params:
  Author: "Daisuke Tsuji"
  DateForm: "Mon, Jan 2, 2006"
  GoogleAnalyticsUserID: "UA-55005303-5"
  Facebook: "daisuke.tsuji.735"
  Twitter: "dim0627"
  Github: "dim0627"
  ShowRelatedPost: True
  Disqus: "unresolved"
  SyntaxHighlightTheme: "github.min.css"

Indexes:
  tag: "tags"

permalinks:
  post: /blog/:year/:month/:day/:slug/

MetadataFormat: "yaml"
```

Example : [My config.yaml](https://github.com/dim0627/hugo_theme_beg/blob/source/config.yaml)
