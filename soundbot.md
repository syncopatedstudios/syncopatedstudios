---
layout: page
title: soundbot
subtitle: herding cats
permalink: /soundbot/
---

# Open Source Audio

A (partially) automated set of instructions to setup an open source sound production environment

# Layers

Currently, having a specific distrobution of Linux (Arch or Fedora) installed is required, however the idea is to be able to configure any running system for the use of sound production.

## Ansible

One of the design aspects is to utilize currently existing open source tools. As opposed to scripting an install and configuration, Ansible is being used to help standardize how systems are setup. A major issue in getting a sound production environment setup is replicating the sound. Ansible helps ensure that systems configurations are consistently syncronized.

## Ruby

Ruby is a programming language. It's excellent at allowing the instructions to be set more as prose than obtuse symbols. Ruby is used in the cli/menu portion as a wrapper around many audio related tools as well as running Ansible tasks.

Ruby is also used in some custom tools;

# $$deadsampler$$
  - #### Utilizing [deadbeef](https://deadbeef.sourceforge.io/), samples can be anyalyed using sonic-annotator, tagged and sorted into collections. [Sonyonm](https://www.sononym.net/), is a sample collection manager that provies similar functionality with a dedicated UI.

# $$robot-stuff$$

What is "robot-stuff"?

# {----------------------------------------------------}

  | `Projects Involved`
--|--
  |  [sonic-pi](https://sonic-pi.net/)
  |  [Sonic Visualiser](https://www.sonicvisualiser.org/)
  |  [hydrogen](http://hydrogen-music.org/)
  |  [reaper](http://reaper.fm)
  |
  |
  |
  |
  |
  |
