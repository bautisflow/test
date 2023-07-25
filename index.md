---
title: Plugins
layout: home
description: This section explains how to deploy and to use the platform Plugins System
---

# PLUGINS MARKETPLACE

## Introduction

Thinger.io Plugins are powerful extensions that enhance the capabilities of the Thinger.io IoT Platform. These plugins allow users to complement the platform with additional features, integrate third-party internet services, implement data analytics algorithms, or even develop custom software tailored to their specific needs.

The core of Thinger.io IoT Platform is designed to be lightweight and flexible, providing maximum flexibility and ease of configuration for IoT networks. Plugins offer on-demand custom functions, empowering each user to customize their IoT server as required.

[Please note that Plugins are available exclusively for premium Thinger.io servers. You can create your own instance quickly by visiting **this link**](https://thinger.io/pricing).

Great news! Thinger.io plugins' source code is now available in our [Github repository](https://github.com/thinger-io/plugins). If you wish to contribute, feel free to fork the project and submit your pull-requests.

## Managing Plugins

The Plugins Marketplace can be accessed by clicking the "Plugins" tab in the main menu.

![Plugins Marketplace shown in Thinger.io Web Console](https://s3.eu-west-1.amazonaws.com/thinger.io.files/plugins/plugin-marketplace.png)

This interface displays the existing plugins that can be installed to extend the Thinger.io IoT Platform. The collection of plugins is continuously growing, offering various categories for easy filtering and management.

### Install and Deploy an Existent Plugin

Each plugin has a detailed description page that provides useful information about its features and usage. Additionally, users can access the plugin's Logs, Shell, and even Share it publicly.

![Plugin Details](https://s3.eu-west-1.amazonaws.com/thinger.io.files/plugins/plugin-details.jpg)

Users can easily manage plugins through the "Plugin Management" section. From here, they have the flexibility to perform various actions, such as installing, starting, stopping, killing, restarting, pausing, resuming, or removing a plugin.

![Plugin Management operations](https://s3.eu-west-1.amazonaws.com/thinger.io.files/plugins/plugin-management.jpg)

This graphical interface enables the following operations:

* **Install:** Installs the plugin, granting access to its services and features while adding a new tab in the main menu.
* **Start:** Deploys the execution of the plugin process. Press this button after installation or after stopping the process to restart the execution.
* **Stop:** Ends the execution of the plugin process gracefully.
* **Kill:** Forcefully terminates the plugin process.
* **Restart:** Performs a Stop + Start cycle for the plugin process.
* **Pause:** Halts the execution of the plugin while preserving all runtime variables.
* **Resume:** Resumes the plugin's execution after being paused.
* **Remove:** Uninstalls the plugin from the platform.

## Custom Plugins Development

Thinger.io encourages community developers to contribute by creating Open Source plugins. To support this initiative, we have established a dedicated repository and wiki providing comprehensive information about the plugins system infrastructure, development guidelines, testing, and deployment.

Plugins Repository

Plugins Development Wiki

