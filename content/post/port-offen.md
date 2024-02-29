---
title: "Port offen"
date: 2024-02-29T12:16:18+02:00
draft: false
author: "Robert"
tags: ["neu", "blog", "2024", "irgendwas"]
categories: ["gesülze", "blog", "index"]
---

## Noch ein Befehl mit dem Telnet auf der Linux Bash ersetzt werden kann:

(>/dev/tcp/[IP]/[PORT]) >/dev/null 2>&1 && echo 'Connection Success' || echo 'Connection refused'

Einfach [IP] mit der IP-Adresse und [PORT] dem gewünschten Port ersetzen (Klammern inklusive).