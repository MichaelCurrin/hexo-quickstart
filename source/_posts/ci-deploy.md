---
title: CI Deploy
date: 2020-06-28 22:56:49
tags:
---

This post is to celebrate adding Github Actions CI flow to the quickstart site.

The problem I have before was at the build step. Eventually I came back to it and realized I need to do a **recursive** clone so that the theme is available.

This was accomplished by adding `submodules: true` to the workflow file.
