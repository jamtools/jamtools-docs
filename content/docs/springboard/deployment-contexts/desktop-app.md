---
title: "Desktop App"
description: "Reference pages are ideal for outlining how things work in terse and clear terms."
summary: ""
date: 2023-09-07T16:13:18+02:00
lastmod: 2023-09-07T16:13:18+02:00
draft: false
weight: 100
toc: true
seo:
  title: "" # custom title (optional)
  description: "" # custom description (recommended)
  canonical: "" # custom canonical URL (optional)
  robots: "" # custom robot tags (optional)
---

Springboard's desktop app deployment uses [Tauri](https://v2.tauri.app) as the application shell, and packages the app with:

- A Hono server sidecar to host the application
- A separate Maestro node script to make it so IO operations (like MIDI events) can happen with minimal latency
