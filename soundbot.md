---
layout: page
title:
subtitle: 
permalink: /soundbot/
---

# Open Source Audio

A set of instructions to setup an open source sound production environment. Supports a variety of possibilities.


# Layers

### Arch

* minimal footprint;
  - to save on cpu calls
    - file indexing/search is done with caching as opposed to a service regularly polling
    - systemd-networkd/dhcp instead network-manager
    - i3-wm (potenially sway in the future) is used to free up even more resources

* designed to focus the workflow...the toolbar and menus are focused on audio applications

* documentation - the arch wiki/stackoverflow

Using a combination of Anarchy Installer / Archiso

insert video

### Ansible

To manage packages and hosts

Ansible is being used to help standardize how the Soundbots are managed. A major issue in getting a sound production environment setup is replicating the sound. Ansible helps ensure that systems configurations are consistently synchronized.

Ansible also assists in setting up a netorked series of nodes for your enjoyment. Using jacktrip, you can split up workloads between the nodes and have the audio routed to a mixing/mastering host. Or however you think is best for your sound. Play around with it, don't be afraid to break things. Ansible helps with that too. Should your one of your Soundbots malfunction, use Ansible to restore the functionality. Configurations are re-generated so performing system backups should be unncessary.



### Ruby

Ruby is a programming language. It's excellent at allowing the instructions to be set more as prose than obtuse symbols. Ruby is used in the cli/menu portion as a wrapper around many audio related tools as well as running Ansible tasks.

## Featured Software

# $$deadsampler$$
  - #### Utilizing [deadbeef](https://deadbeef.sourceforge.io/), samples can be analyzed using sonic-annotator, tagged and sorted into collections. [Sonyonm](https://www.sononym.net/), is a sample collection manager that provides similar functionality with a dedicated UI.

# $$robot-stuff$$

  | `Projects Involved`
--|--
  |  [Sonic-Pi](https://sonic-pi.net/)
  |  [Sonic Visualiser](https://www.sonicvisualiser.org/)
  |  [Hydrogen](http://hydrogen-music.org/)
  |  [Reaper](http://reaper.fm)
  |  baudline
  |  zita
  |  x42
  |  swh
  |  ray-session
  |
  |
  |
  |
  |

#
