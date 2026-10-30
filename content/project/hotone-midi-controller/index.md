---
title: "Hotone Ampero II Stomp Desktop ToneSwitcher"
summary: "A Python desktop application for controlling guitar effects through MIDI, including patch switching, scene selection, and tuner control."
date: "2026-04-10"

tags:
  - Python
  - MIDI
  - Tkinter
  - Desktop Application

url_code: "https://github.com/yuanjunze/Hotone-Ampero-II-stomp-Desk-ToneSwitcher"
url_video: 'https://www.bilibili.com/video/BV1mZDCBFE9n/?spm_id_from=333.337.search-card.all.click'
---

## Overview

A lightweight desktop MIDI controller developed for the Hotone Ampero II Stomp guitar multi-effects processor.

The application provides convenient control of guitar effects directly from a Windows computer, reducing the need to manually operate the physical pedalboard.

## Key Features

- **Patch Switching:** Direct selection of presets and navigation between patches.
- **Bank Navigation:** Quick switching between preset banks.
- **Scene Control:** MIDI-based switching between five scenes.
- **Tuner Control:** Enable or disable the device tuner.
- **Keyboard Shortcuts:** Convenient control without navigating the graphical interface.
- **Configuration Persistence:** Remember previously selected MIDI ports, channels, and banks.

## Implementation

The application is developed with Python and Tkinter, using mido and python-rtmidi for MIDI communication.

It features a dark-themed graphical interface, automatic MIDI output port detection, and support for packaging as a standalone Windows executable.

## Source Code

The complete implementation is available on GitHub.
---