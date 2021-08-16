---
title: "Arch Linux Installation"
date: 2021-07-23T11:34:34+05:30
draft: true
---

# What is Arch Linux?

Arch Linux is a Linux distribution. If you don't know what Linux is, a quick skim through the first few sections of my [Linux Guide](/blog/linux-intro) should get you up to speed. Arch is an extremely minimal distribution with low hardware requirements and is built for flexibility. The whole idea is, you put whatever you need into your computer, and remove whatever you don't need. This causes the initial installation to be a little tedious and un-intuitive as it is not exactly straightforward. However, it is not difficult according to popular belief. The official Arch Wiki is an amazing resource and the installation guide is very helpful. But, there are a few pieces of additional information that may be required for beginners which are not very clear. I will be going over everything you need to know so that you will be able to get a fully functional desktop at the end. 

On the other hand, one installation of Arch Linux is enough to give you a much better understanding of what goes into making a computer and its OS.

# Installation

## Caution

It is advised to try out Arch and its installation on a Virtual Machine before trying it out on bare metal, as you are very likely to brake something. A popular software is [VirtualBox](https://www.virtualbox.org/).

## Create the installation media

Go to the official Arch Wiki and navigate to the Downloads page. You can directly download the ISO file from a mirror which is closest to you for a faster download. Or, you can use a torrent if that is what you prefer.

Then download a tool like balenaEtcher to flash the ISO to a flash drive to create the installation media. I have given some instruction in my [Linux Guide](/blog/linux-intro) which you can check out in the [Install section](/blog/linux-intro/#preparing-for-installation).

## Boot from the installation media

Plug in the flash drive and boot from it. Make sure that the flash drive is in the first position in the boot order. You will have to enter the BIOS setup to do this. It might be F2 or F12 depending on the make of your computer.

