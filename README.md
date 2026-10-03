<img width="627" height="73" alt="image" src="https://github.com/user-attachments/assets/aee62f5f-468a-4a6a-b3ef-9cecea99e2e9" />
<img width="621" height="257" alt="image" src="https://github.com/user-attachments/assets/63e82b49-0597-4399-a4ba-c43ef912fcf5" />
<img width="481" height="165" alt="image" src="https://github.com/user-attachments/assets/7113f34d-2697-48c5-9b4c-8684fb02276c" />

# Minecraft Paper Server

A base Minecraft Paper server setup designed as a clean starting point for Minecraft server development, configuration, and plugin management.

## Overview

This repository contains the initial files and configuration required to run a Minecraft server using **Paper**.

It provides a clean foundation for adding plugins, configuring server settings, managing permissions, creating custom systems, and developing the server over time.

This is a development foundation rather than a fully configured public Minecraft server.

## Server Startup

`server.jar` is the main Paper server JAR file used to start the Minecraft server.

Depending on the setup, the server can be started using a startup script such as:

```bat
java -Xms4G -Xmx4G -jar server.jar nogui
```

The allocated RAM can be changed depending on the hardware available and the requirements of the server.

## Features

- Minecraft Paper server base
- Pre-configured server files
- Plugin-ready environment
- Permission and configuration support
- Suitable for development and testing
- Easy to customise and expand
- Foundation for future server systems

## Requirements

- **Java:** A Java version compatible with the Minecraft/Paper version being used
- **Paper:** Paper server JAR included in the server directory
- **RAM:** At least 4 GB recommended for development, depending on the number of plugins, players, and server systems

> **Note:** The required Java version depends on the Minecraft version. Java 21 is required for Minecraft versions such as 1.20.5–1.21.x, but you should use the Java version specified by the Paper/Minecraft version you are running.

## Purpose

This repository serves as the foundation for Minecraft server development.

It allows server configurations, plugins, scripts, and custom systems to be developed and tested in one organised environment before being deployed to a live server.
