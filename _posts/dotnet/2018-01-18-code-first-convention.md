---
layout:     post
title:      "Code First Convention"
date:       2018-01-18 13:05:37 +0800
category:   dotnet
---

1. Navigation properties are typically defined as ```virtual``` so that they can take advantage of certain Entity Framework functionality such as *lazy loading*.