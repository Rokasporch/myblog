---
title: "Remote Desktop Verbindung zu Windows Gast auf QEMU Hosts"
date: 2022-10-16T20:16:18+02:00
draft: false
author: "Robert"
tags: ["Technik", "QEMU", "2022", "Tipp"]
categories: ["Tipp", "Technik", "QEMU"]
---

## Remote Desktop

Sicherlich betreibt der ein oder andere von euch auf dem Linux Rechner eine virtuelle Maschine mittels QEMU.

Im folgenden Beitrag von Christian Imhorst wird der Zugriff vom Host System (Suse Linux) via RDP auf den Windows Gast beschrieben.


[Remote Desktop mit Windows in QEMU](https://www.datenteiler.de/remotedesktop-mit-windows-in-qemukvm/ "Remote Desktop mit Windows in QEMU")

Ich konnte es bei mir erfolgreich testen. Eine Verbindung von einem Drittrechner konnte ich nur via SSH Tunnel auf das Host System nachstellen.
