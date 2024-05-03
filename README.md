# home-assistant-tuya-custom

[![hacs_badge](https://img.shields.io/badge/HACS-Default-41BDF5.svg?style=for-the-badge)](https://github.com/hacs/integration)

A Home Assistant integration for adding custom Tuya categories without waiting for Core to update.
This code Home Assistanmt Core pull request and to allow quick additon of more devices.


This is a fork of lasry1/home-assistant-tuya-custom (https://github.com/lasry1/home-assistant-tuya-custom). To get the newest version I got the actual tuya components from HomeAssistant/Core Pull request Add support for tuya ggq irrigator #115604 (https://github.com/home-assistant/core/pull/115604). So this rep has the latest tuya version with QR code login (no IoT account needed anymore) and the GQQ support.

This adds 2 different water irrigation valves named ‘GGQ’ (Diivoo dual zone irrigation kit).

To add this repo as a custom component in home assistant:

Go to HACS
Integrations
3 Dots on top right corner
Custom repositories
repository: https://github.com/snap2phil/home-assistant-tuya-custom/
Category: Integration


Then you'll need to install it and reboot home assistant

Hope that helps somebody as I struggled for years adding my irrigation natively to home assistant.

