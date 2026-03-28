# Server Not Available

A lightweight static fallback page displayed when the main deployed project is unreachable.

## Purpose

When the primary deployment goes down or is under maintenance, this page can be served in its place to inform visitors that the service is temporarily unavailable and to try again later.

## Usage

1. **GitHub Pages** – Enable GitHub Pages (Settings → Pages → Branch: `main`, folder: `/`) and the `index.html` will be served automatically.
2. **Custom fallback** – Host `index.html` on any static-file host (Netlify, Vercel, Cloudflare Pages, etc.) and point your DNS/CDN failover rule to it.

## Preview

Open `index.html` directly in a browser to see the fallback page.