---
layout: page
title:
subtitle:
permalink: /soundbot/
---

> ooh la la uhhh wewe

A set of instructions to setup an open source sound production environment. Supports a variety of possibilities.

What Ol' Dirty Bastard would've done had he got himself into Linux.


# Layers

## Linux

* minimal footprint;
  - to save on cpu calls
    - file indexing/search with fzf
    - systemd-networkd/dhcp instead network-manager
    - i3-wm (potenially sway in the future) is used to free up even more resources

* designed to focus the workflow...the toolbar and menus are focused on audio applications

insert video

## Ansible

* ensures parity accross hosts
  * assign roles to hosts
      - plugin host
      - mixer host
      - controller host
      -
  * manages various system tasks
      - backups
      - updates
      - package installs*
      - system configuration



To manage packages and hosts

Ansible is being used to help standardize how the Soundbots are managed. A major issue in getting a sound production environment setup is replicating the sound. Ansible helps ensure that systems configurations are consistently synchronized.

> Boom, I fucked your boyfriend. Boom, I fucked your man

Ansible also assists in setting up a netorked series of nodes for your enjoyment. Using jacktrip, you can split up workloads between the nodes and have the audio routed to a mixing/mastering host. Or however you think is best for your sound. Play around with it, don't be afraid to break things. Ansible helps with that too. Should your one of your Soundbots malfunction, use Ansible to restore the functionality. Configurations are re-generated so performing system backups should be unncessary.

## osc server:
  * i3
  * host control
  * and more!

## visualize and annontate
  * sonic-visualiser
  * baudline
  * ocenaudio

## functions to assist in audio composition
  * coltrane

## audio file management:
  * sample manager backend with beets
  * search, preview and collect samples with fzf
      [fzf-search-syntax](https://github.com/junegunn/fzf#search-syntax)
  * export to sfz or hydrogen drumkit
  * integration with deadbeef
  * sonic-annotator parses audio attributes and stores them as tags

## utilize keyboards as midi controllers
  * lsmi_keyhack

## interconnect things with jacktrip,socat
  - reaper
  - sooperlooper
  - sonic-pi

# Ruby

Ruby is a programming language. It's excellent at allowing the instructions to be set more as prose than obtuse symbols. Ruby is used in the cli/menu portion as a wrapper around many audio related tools as well as running Ansible tasks.



~~#[Sonyonm](https://www.sononym.net/), is a sample collection manager that provides similar functionality with a dedicated UI.~~


# `Included Projects:`

## `sonic-pi`
midi controller, synthsizer, sampler

## `deadbeef`
samples can be analyzed using sonic-annotator, tagged and sorted into collections.

## `sonic visualiser`
see what you are hearing

## `baudline`
samesies

## `zita`
various filters, crossover

## `hydrogen`
patterns, sampler

## `reaper`
midi editor, mixer, ambisonics host

## `ray-session`
session manager, patch bay

## `x42`

## `swh`
