---
layout: post
title: Technische Beschreibung
date: 2019-02-26
---

Das *Host You Own Minecraft Server* Projekt besteht im wesentlichen aus drei GitRepositories, welche alle bei [GitHub](https://github.com/nolte?utf8=%E2%9C%93&tab=repositories&q=minecraft&type=&language=) zu finden sind. Ziel ist es die Komplette Infrastruktur im SourceCode zu verwalten und öffentlich auf GitHub für die Wiederverwendung zu presentieren.

## Der Blog

{{< githubrepostars type="stars" id="nolte/minecraft-gameserver" >}}
{{< githubrepostars type="watch" id="nolte/minecraft-gameserver" >}}
{{< githubrepostars type="forked" id="nolte/minecraft-gameserver" >}}
{{< githubrepostars type="issue" id="nolte/minecraft-gameserver" >}}
{{< travisci repo="nolte/minecraft-gameserver" branch="master" >}}

Der mit Hilfe von [Hugo](https://gohugo.io) generierte Blog ([nolte/minecraft-gameserver](https://github.com/nolte/minecraft-gameserver)) trennt den Redaktionellen Teil des Projektes vom Technischen-Aufbau.

## Die Infrastruktur

{{< githubrepostars type="stars" id="nolte/minecraft-server" >}}
{{< githubrepostars type="watch" id="nolte/minecraft-server" >}}
{{< githubrepostars type="forked" id="nolte/minecraft-server" >}}
{{< githubrepostars type="issue" id="nolte/minecraft-server" >}}
{{< readthedocs repo="minecraft-server" version="master" >}}
{{< travisci repo="nolte/ansible-minecraft" branch="master" >}}
{{< circleci repo="nolte/ansible-minecraft" branch="master" >}}

Die Infrastruktur wird aktuell bei [hetzner.de](https://hetzner.de/cloud) betrieben und mit einer Kombination von [Ansible](https://www.ansible.com/) und [Terraform](https://www.terraform.io/) bereitgestellt, weitere Informationen sind im [nolte/minecraft-server](https://github.com/nolte/minecraft-server) Repository zu finden.

## Minecraft Ansible Role

{{< githubrepostars type="stars" id="nolte/ansible-minecraft" >}}
{{< githubrepostars type="watch" id="nolte/ansible-minecraft" >}}
{{< githubrepostars type="forked" id="nolte/ansible-minecraft" >}}
{{< githubrepostars type="issue" id="nolte/ansible-minecraft" >}}
{{< readthedocs repo="ansible-minecraft" version="master" >}}
{{< travisci repo="nolte/ansible-minecraft" branch="master" >}}
{{< circleci repo="nolte/ansible-minecraft" branch="master" >}}

Der Minecraft Server wird mit Hilfe eine Ansible Role ([nolte/ansible-minecraft](https://github.com/nolte/ansible-minecraft)) konfiguriert und installiert. Diese Role ist durch [Ansible Galaxy](https://galaxy.ansible.com/nolte/minecraft) einfach nutzbar.
