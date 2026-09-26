---
title: "How to Add Beautiful OG Social Preview Images to Your GitHub Repository"
date: 2026-09-26
author: Adventure Products
---

# How to Add Beautiful OG Social Preview Images to Your GitHub Repository

When you share a link to your GitHub repo on Twitter/X, LinkedIn, or Slack, 
what shows up? 

If you haven't set a social preview image, it's either a generic GitHub logo
or nothing at all. That's a missed opportunity — social previews increase
click-through rates by up to 3x.

## The Problem

GitHub supports a `social_preview` image for every repository, but most 
projects never set one. The default is a generic GitHub-generated image 
with your repo name on a white background.

## The Solution (30 seconds)

1. Go to your repo's **Settings** → **Social preview** 
2. Upload a 1280×640 PNG image
3. Click **Save**

That's it. Next time someone shares your repo link, it'll show your 
custom image.

## Generating the Image

You have a few options:

### Option A: Use a Free Tool

The **[OG Preview Checker](http://167.233.135.161:8081/)** lets you:
- Check what your repo currently shows when shared
- Generate a free OG image with your repo name and description
- Preview it before uploading

Free, no signup required.

### Option B: The $1 Custom Service

If you want a professionally designed image with:
- Custom color scheme matching your brand
- Icons/illustrations specific to your project
- Proper typography and layout

I create **custom OG images for $1** — [get yours here](https://grantshatz.gumroad.com/l/kcdpnv).

### Option C: Automated via GitHub Actions

The **[OG Image Action](https://github.com/astra-intelligence/og-image-action)** 
generates social previews automatically on every push. Add it to your 
workflow in 2 minutes.

## What Makes a Good OG Image?

- **1280×640 pixels** (the standard)
- **Your project name** prominently displayed
- **A short tagline** or description
- **Clean, high-contrast design**
- **No small text** — it'll be tiny when scaled down

## Check Your Repo

Use the free [OG Preview Checker](http://167.233.135.161:8081/) to see 
what your repo currently shows:

```
https://167.233.135.161:8081/?url=https://github.com/yourname/yourrepo
```

Or use the API:

```bash
curl https://167.233.135.161:8081/api/check?url=https://github.com/yourname/yourrepo
```

## Done

That's literally it. 1280×640 PNG, upload to Settings, done. Your repos 
will look professional everywhere they're shared.