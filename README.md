# Zynelion Sports — Evergreen Football Template

Static GitHub Pages/Jekyll template for `https://sports.zynelion.com`.

This repo is prepared for evergreen football content, not daily rewritten news.

## Main content types

- Player Profiles
- Career Stories
- Club Profiles
- Club History

## Required folders

```text
_posts/
assets/img/football/
assets/img/players/
assets/img/clubs/
players/
clubs/
stories/
```

## Apps Script publish path

The Apps Script should publish generated Markdown posts into:

```text
_posts/YYYY-MM-DD-title-slug.md
```

## Required post front matter

Player profile example:

```yaml
---
layout: post
title: "Profil Lionel Messi: Karier, Klub, dan Prestasi"
description: "Profil Lionel Messi, perjalanan karier, klub yang pernah dibela, gaya bermain, dan prestasi pentingnya."
date: 2026-05-13 18:00:00 +0700
categories: [players]
tags: [Lionel Messi, Argentina, Inter Miami, Barcelona, Player Profile]
image: "/assets/img/football/lionel-messi.webp"
image_caption: "Lionel Messi dalam konteks karier sepak bolanya."
image_credit: "Author / Wikimedia Commons"
image_license: "CC BY-SA 4.0"
image_source_page: "https://commons.wikimedia.org/wiki/File:example.jpg"
source_urls:
  - "https://en.wikipedia.org/wiki/Lionel_Messi"
---
```

Club profile example:

```yaml
---
layout: post
title: "Profil FC Barcelona: Sejarah, Stadion, Trofi, dan Rivalitas"
description: "Profil FC Barcelona, sejarah klub, stadion, rivalitas, pemain legenda, dan prestasi penting."
date: 2026-05-13 18:00:00 +0700
categories: [clubs]
tags: [FC Barcelona, La Liga, Camp Nou, Club Profile]
image: "/assets/img/default-football.svg"
---
```

## Important config for Apps Script

Use this public site URL:

```text
SITE_BASE_URL=https://sports.zynelion.com
```

Do not use GitHub Pages repo URLs inside generated posts.
