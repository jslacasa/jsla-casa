---
title: Tools
date: 2026-02-04
draft: true
tags:
---
Sync changes with the actual content folder of quartz:
```bash
rsync -avh --progress --delete /home/jesus/Google\ Drive/Zettelkasten/jsla-casa/ /home/jesus/jsla-casa/content

npx quartz sync
```

Build and publish: 
```bash
npx quartz sync
```