---
title: "Telnet unter Linux"
date: 2022-11-03T19:16:18+02:00
draft: false
author: "Robert"
tags: ["Technik", "Linux", "2022", "Tipp"]
categories: ["Tipp", "Technik", "Linux"]
---

## Telnet Alternative unter Linux

Aus der Windows Welt bekannt, das gute alte Telnet. Möchte man ohne große Umwege wissen, ob zum Beispiel der Remote Desktop Port offen ist, bedient man sich unter Windows des Kommandos Telnet. Ein Pedant unter Linux ist mir bisher nicht bekannt gewesen.

Auf Stackexchange bin ich auf eine gute Lösung gestoßen:


*If using Bash Shell, then you can use its feature to check if a port is open or closed:*

*(timeout 1 bash -c '</dev/tcp/127.0.0.1/17500 && echo PORT OPEN || echo PORT CLOSED') 2>/dev/null*
*PORT OPEN*

*(timeout 1 bash -c '</dev/tcp/127.0.0.1/7500 && echo PORT OPEN || echo PORT CLOSED') 2>/dev/null*
*PORT CLOSED*

[Quelle](https://unix.stackexchange.com/a/479770 "Stackexchange")
