# Homelab Minecraft Server

This repository contains documentation for my personal homelab Minecraft server setup.

The server is for private use only and is intended to run FTB StoneBlock 4 on my own Ubuntu Server using Docker Compose and the public `itzg/minecraft-server` Docker image.

## Scope

* Private Minecraft server for myself and a few friends
* FTB StoneBlock 4 server automation
* Docker Compose based server management
* Occasional modpack installation and update checks
* No public launcher
* No file mirror
* No mod redistribution
* No commercial use or monetization

## CurseForge API Usage

The CurseForge API will only be used to query Minecraft modpack metadata and resolve/download the required files for running the private server.

The API key is stored locally in a private `.env` file on my server and is not included in this repository.

This repository does not contain:

* CurseForge API keys
* RCON passwords
* Minecraft server files
* Mod files
* Modpack files
* Redistributed CurseForge content

## Notes

This is a personal non-commercial homelab project. Players will install their client-side modpack through the normal CurseForge or FTB methods.
