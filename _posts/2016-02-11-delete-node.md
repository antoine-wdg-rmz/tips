---
layout: post
title: delete-node.md
author: antoan2
tags: [oar]
---
# Deleting a node

First set state to Dead :
```
sudo oarnodesetting -s Dead -r $i
```

Then use oarremoveresource :
```
oarremoveresource $i
```
