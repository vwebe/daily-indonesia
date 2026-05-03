# Daily Indonesia Bola

Ready-to-use GitHub Pages/Jekyll news template for `vwebe/daily-indonesia`.

## Setup

1. Upload all files to the root of `https://github.com/vwebe/daily-indonesia`.
2. Go to **Settings → Pages**.
3. Set **Source** to `Deploy from a branch`.
4. Select branch `main`, folder `/root`.
5. Wait for GitHub Pages to build.

## Auto post path

The Apps Script should publish generated Markdown posts into:

```text
_posts/YYYY-MM-DD-title-slug.md
```

## Required post front matter example

```yaml
---
layout: post
title: "Contoh Judul"
description: "Deskripsi artikel."
date: 2026-05-03 18:00:00 +0700
categories: [bola]
tags: [Sepak Bola, Liga Indonesia]
image: "https://example.com/image.jpg"
source_site: "Kompas Bola"
source_title: "Judul sumber"
---
```
