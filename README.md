# LiveAgent-changelog

Changelog for LiveAgent (www.liveagent.com).

## Development
1. checkout repo
2. install `Ruby`
3. in project root `bundle install`

## Content editing
1. Create new file in `_posts` directory.
2. Filename format: `YYYY-MM-DD-VERSION.md`
3. Content needs to start by header:
```
---
layout: post
title: VERSION
author: GITHUB_USERNAME
tags: [ladesk,LiveAgent,VERSION]
---
```
4. Content items are in format:
`- [type] Item title (#ISSUE NUMBER)`
5. Special items:
`**[Important notice] Special item**`
6. Insert `<!--more-->` between items for "Read more"

## View
There is special view for direct linking of issue numbers to github issues. Just add `?linkify` to URL, f.e. https://dev.ladesk.com/?linkify
