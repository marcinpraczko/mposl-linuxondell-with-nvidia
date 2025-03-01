Linux on Dell with Nvidia GPU
=============================

.. contents::

Long story short: (TLDR)
------------------------

I bought a Dell Laptop in 2019 and installed Linux on it. Everything was working fine, and as a non-gamer,
I had no issues with the GPU.

In 2024, I decided to start playing some games and installed the Nvidia proprietary drivers for the first time.
Despite my graphics card not being powerful enough for the games I wanted to play, there were no issues
with system stability or performance after installing the drivers.

In January 2025, I bought a new Dell laptop with an Nvidia GPU, expecting everything to work seamlessly.
My primary reason for the new laptop was to have a powerful machine for daily work and occasional gaming.
Given Nvidia's good reputation (from my point of view) for Linux support and my positive experience with my old laptop,
I didn't think twice. This was also my first laptop purchased with only Linux installed, no Windows at all.

With my extensive experience working with Linux, I was confident everything would work out of the box.

However, I was so wrong.

I encountered numerous issues with the Dell, Ubuntu, Kubuntu and Nvidia drivers and spent many hours trying to fix them,
with some problems still unresolved.

This repository is a collection of scripts and documentation to address the issues I faced.
I hope it helps others and saves them time.


List of issues I faced
----------------------

Following is a list of issues I faced with my new DELL laptop with Nvidia GPU (Two GPUs: Intel and Nvidia).
My new laptop is a Dell with Ubuntu and two GPUs: Intel and Nvidia.

- One needs to be sure that Laptop is certified for Linux. I didn't check this before buying the laptop.
  (Lucky for me, it was certified for Linux - I checked this after facing issues)
- Issues with two GPUs: Intel and Nvidia
- Issues with Booting (Black screen, system freeze)
- Issues with Nvidia drivers - installation and understanding architecture for drivers (proprietary and open-source)
- Issues with Nvidia drivers and external monitors (HDMI - black screen)
- Issues with Linux kernel - signing and secure boot
- Issues with SDDM when login to KDE Plasma
- Issues with DKMS and many kernels


Goal of this repository and motivation
--------------------------------------

This repository was created to help others who face similar issues especially for configuration DELL / Linux / Nvidia.
It was unexpected to encounter so many issues, however, there is no desire to blame anyone.
