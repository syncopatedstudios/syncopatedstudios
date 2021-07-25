---
layout: page
title: \{------------------------------------------------------}
subtitle: herding invisible cats
permalink: /soundbot/
---

# Open Source Audio

A (partially) automated set of instructions to setup an open source sound production environment. Supports a variety of possibilities.

<!-- {% seqdiag %}
seqdiag {
  browser  -> webserver [label = "GET /index.html"];
  browser <-- webserver;
  browser  -> webserver [label = "POST /blog/comment"];
              webserver  -> database [label = "INSERT comment"];
              webserver <-- database;
  browser <-- webserver;
}
{% endseqdiag %}

{% nwdiag %}
nwdiag {
  network soundbot {
      address = "210.x.x.x/24"

      soundbot01_reaper_node [address = "210.x.x.1"];
      soundbot02_mic_node [address = "210.x.x.2"];
      soundbot03_controller_node [address = "210.x.x.3"];
  }
  network nodes {
      address = "172.x.x.x/24";

      soundbot01 [address = "172.x.x.1"];
      soundbot02 [address = "172.x.x.2"];
      db01;
      db02;
  }
}
{% endnwdiag %}

{% actdiag %}
  actdiag {
    write -> convert -> image

    lane user {
      label = "decision"
      write [label = "Thinking about using this"];
      image [label = "Still thinking about using this"];
    }
    lane actdiag {
      convert [label = "go eat ice cream"];
    }
  }
{% endactdiag %} -->

# Layers

The idea is to be able to configure any running system for the use of sound production. Until package/application management can be sorted out, Arch is used as a base Linux system.

### Arch
Arch is used mainly for these reasons;

* documentation
* easy build process
* ability to utilize latest toolsets

Building a Fedora ISO is a chore. Building a Fedora package is worse. Documentation is ok. Debian based systems are often limited as to what software can be compiled. Arch seems to be a nice comprise.



### Ansible

One of the design aspects is to utilize currently existing open source tools. As opposed to scripting an install and configuration, Ansible is being used to help standardize how systems are setup. A major issue in getting a sound production environment setup is replicating the sound. Ansible helps ensure that systems configurations are consistently synchronized.

### Ruby

Ruby is a programming language. It's excellent at allowing the instructions to be set more as prose than obtuse symbols. Ruby is used in the cli/menu portion as a wrapper around many audio related tools as well as running Ansible tasks.

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
  |
  |
  |
  |
  |
  |
