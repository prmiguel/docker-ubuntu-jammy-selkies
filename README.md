## 🐳 docker-ubuntu-jammy-selkies

This repository provides a custom Docker image based on **Ubuntu 22.04 LTS (Jammy Jellyfish)**, incorporating components necessary for the **Selkies remote desktop** system.

-----

### ⚙️ Source and Modifications

This image is adapted from the excellent work done by the **LinuxServer.io** team, integrating key features from the following repositories, but with **modifications** to support the Ubuntu Jammy base:

  * **Selkies Base Image:**
      * **Original:** `https://github.com/linuxserver/docker-baseimage-selkies`
  * **Xvfb Integration:**
      * **Original:** `https://github.com/linuxserver/docker-xvfb`
  * **Ubuntu Base Image:**
      * **Original:** `https://github.com/linuxserver/docker-baseimage-ubuntu`

> **Note:** The official LinuxServer images currently focus on newer distributions like **Ubuntu Noble**. This repository explicitly **forks and modifies** the necessary Dockerfiles and configurations to function correctly on **Ubuntu Jammy** (22.04 LTS) and includes minor package/registry updates.
