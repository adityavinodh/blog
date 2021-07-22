---
title: "Ultimate Beginner's Guide for Linux"
date: 2021-06-29T18:55:46+05:30
draft: false
summary: "Learn about Linux, its fundamental concepts, and get started right away!"
tags: ["tutorial", "linux", "beginner", "guide", "get started", "install", "basics", "fundamentals", "open-source"]
editPost:
    URL: "https://github.com/adityavinodh/blog/tree/main/content"
    Text: "Suggest Changes"
    appendFilePath: true
---

![Linux Penguin Logo](/linux_penguin.jpg)

# What is Linux?

Linux is another operating system comparable to macOS and Windows.
Although it is technically not referred to as a wholesome OS like its
popular counterparts, there are distributions of Linux
(flavours/variations) of it which can be directly compared.

Linux is based on UNIX, similar to macOS, but that is pretty much where
the similarities end. It was created by Linus Torvalds with a free, open
source license, which is the main reason it grew so much in popularity.
But, the software that Linus created, is only what is called the Linux
Kernel, which is not an entire operating system.

## Distributions (or distros)

Other developers and companies over the years, have created their own
versions of an operating system called distributions (or distro for
short) building up on Linux. Few examples of these distributions are
[Debian](https://www.debian.org/), [Arch Linux](https://archlinux.org/), [Red Hat Enterprise](https://www.redhat.com/en/technologies/linux-platforms/enterprise-linux), etc. Some of these distributions
can only be used with a command-line interface (no graphical interface),
but it is possible for users to install desktop environments or window
managers for them to actually use it as a modern desktop operating
system. 

Linux has grown in popularity over the years, and due to its free and
open source nature, there are so many forks and branches of different
distributions which are based on each other. An example is [Ubuntu](https://ubuntu.com/)
created by Canonical, one of the most popular distros in existence right now, which is based on
one of the oldest distributions called Debian. Another popular
distribution created by the company System76, is [Pop!_OS](https://pop.system76.com/), which is based
on Ubuntu, which is based on Debian.

![Red Hat Family Tree](/1280px-RedHatFamilyTree1210.svg.png)

The image above shows the numerous branches or forks of one particular
distribution called Red Hat which is meant for enterprise businesses.

# Advantages of using Linux

## Performance and Efficiency

Linux operating systems or distributions are extremely light-weight and
efficient compared to their proprietary counterparts. The user is in
full control of what runs on their system at all times, and any
component can be removed and installed at any point of time. This causes
computers to run tasks and perform much better on Linux rather on
something like Windows. 

I can personally vouch for this as I have a new Dell XPS 13 with an
Intel i7, which initially had Windows 10 Home pre-installed. Although
there is not much of a performance difference between the Home and Pro
versions, I should have been receiving excellent performance for the
hardware I had. But, I often experienced sluggishness, animations losing
frames, and the laptop often overheating. Once I jumped on to a linux
distro (Ubuntu), I immediately experienced extremely snappy responses,
and the overheating issues vanished. All of this was during regular
browsing, video conferencing, etc.

## File system

This point ties in with performance. Linux uses a much more superior file system especially in contrast to Windows' FAT or NTFS. There are different variations, such as EXT4, which allow for more reliability, and much more faster and robust experience when copying, and moving around files and directories.

## Security

Linux is vastly more secure for two main reasons. Firstly, it is not
nearly as popular as Windows or MacOS, so viruses are usually not made
with Linux in mind. There are very few viruses made for Linux distros
and you will not be needing to install any anti-virus software. Another
reason is also probably because people using Linux are usually a little
more tech-savvy and are careful when installing files from the internet.
As long as you are aware of the file types and permissions on your
system, you shouldn't have to worry.

Secondly, because Linux is open source, vulnerabilities are quickly
identified and patched by any knowledgeable person in the community,
without having to wait for months from some company to provide a
security patch. One could make the argument that if the code is open
source, hackers or malicious individuals could easily exploit
vulnerabilities. But, there are far more people looking to usually fix
bugs and improve the system because they are the ones who are going to
use it at the end of the day.

## Reliability and Stability

Linux is extremely stable and reliable. This is a well-known fact as it
is employed in thousands of servers around the world which are running
Linux continuously without any crashes or errors. Even Microsoft, which
has their own Windows for Servers OS, uses Linux for their servers. They
usually have high uptime and very rarely crash or provide issues. 

And, my most favorite feature of Linux, is that when something goes
wrong, you get very descriptive error messages telling you what and
where the issue has occurred. Using this information, you can most likely
understand the problem and rectify it, or a quick Google search (or
Brave, DuckDuckGo, etc.) will always find you the answer from countless
blog posts and forums where the same question and error has probably
been answered multiple times. In other OSs, it is almost impossible to
get help, because when something goes wrong, it just says 'Oops,
something has gone wrong', and you are pretty much helpless. Even if you
try to ask someone online, there are probably a 100 possible errors
which provide the same message.

## Customizability

Being open source, and further employing the concept of 'everything is a file', makes it possible to customize every aspect of the system. If you don't like the way something looks or behaves, you can just go ahead and change it without asking anyone. Everything in Linux is just a text file, even things like the network configuration or how your display is set up. So you can just open the file with a simple text editor, and make the change.

If you are using a user-friendly distro, you can do this using a friendly GUI with intuitive menus so it can be done easily (just like on Windows or macOS). Other distributions which tend to be more lightweight will required users to actually dig into the files and change what they want.

You will be amazed to see the desktops people have created using Linux. I can argue that it is 100 times better than the ones made by Microsoft and Apple.

## Privacy

Whether you are developer writing some important code for a piece of software, or you are just a regular daily user, privacy is something you never have to worry about in Linux. Due to the same reasons I mentioned above (being open source), you will never have to worry about key loggers, or any other kind of program that will track you on your device.

## Software Updates

Software update models depend on the distribution you are going to choose. Some have a rolling release cycle (like Arch Linux) where small incremental updates are released almost every month or week which always keeps you up-to-date with the latest bleeding-edge features. Others push updates around once or twice a year (like Ubuntu). This is generally considered a little more stable as it is more comprehensively been tested. But regardless of what release cycle is used, if you don't want to update your computer, you do not have to. You can say good bye to the annoying windows updates that you are forced to install. 

When the time comes for you to update your system (only if that is what you want), then one simple click or update command, will update every single package and software on your system, including the actual OS. Updating individual packages separately is also an option.

Another feature about Linux that is really convenient is that for most updates, you do not have to restart or reboot your computer. This is such a time-saver, especially if you are coming from Windows. Every time you update something, or are forced to update something, you might suddenly be asked to reboot your computer. Sometimes, my drivers have suddenly stopped being able to recognize the hardware completely. But on Linux, all of this happens without requiring an update most of the time.

## User management

This might not be too important to you, but the way Linux handles users is vastly superior. Since it was initially not meant to be used as a traditional desktop, rather on servers, Linux has the capability of multiple users logging into the same computer at the same time and working on something. This could be very useful if you are using it for a server, or just a main computer in your home where you want multiple family members to be able to use it and enjoy their content remotely at the same time.

In addition to multiple simultaneous users, permissions are extremely strict and granular. By default, new users do not have most file access permissions (read, write, executable, etc.). You can specifically add permissions to each user, or add users to groups, and then add permissions for users of the group. Furthermore, the permissions that you add can be incredibly granular, such as for a specific file or directory. This also prevents the risk of some malicious file, script, or virus that somehow has made its way to your computer, to actually do any damage.

## Software management

Finally, linux fully embraces the open source idealogy. Most software that is used is open source, but also includes proprietary software. But, the main difference from Windows and macOS is how Linux decides to manage software. All distributions ship with a package manager. This is the default on the system, but you also have the option to install additional ones. A package manager is a tool to help you install any software you want. It maintains a repository of software developed by many developers. As long as the software you want is available in the repository, a simple click or command with the program name is enough to install the entire software with all its dependencies. No annoying installation wizards. It takes care of the entire setup for you.

If the software is not available in the repository, maybe because it is proprietary, you have a few options. Some popular distributions include repositories where all the software is contributed by individual users and developers. The information and instructions to install the software will be provided by the company or developer (usually on their website). So, you can download it from there. The last option is to compile it from source. This is something that will not make sense for the average user, but is still an option. It is very beneficial even though it is difficult, as it allows for you to use a piece of software that would otherwise not be available. Basically it means, you download the source code (the actual code that the developers wrote), download and install any necessary dependencies, and then compile the app yourself for it to be run on your system. Usually this compilation step is done by the developers, and all you need to do is install the actually binary file (.exe, .dmg, .pkg, .deb, .rpm, etc.) and do a quick install.

# Getting Started

## Prerequisites

There are pretty much no prerequisites or minimum system requirements. All you need is a basic understanding of what Linux is, so you know what you are actually doing and getting yourself into. And most importantly, you need a working computer for you to install Linux. Any computer will do, even if it is around 10-15 years old, just make sure you have backed up all your files and are ready to format it.

## Choosing a distro

This is your starting point. But the most important thing you should know, and you will hear this advice everywhere, is to not distro hop. Choose one, use it as your daily driver at least for 6 months, get a good feel for it, start customizing it to your taste, and then you can change distributions if you want. This most common misconception is to change distros because you think another distro looks better.

### Desktop Environments

If you choose Ubuntu for example, it uses a desktop environment called GNOME. This is the default desktop environment that it ships with. This is what gives it the familiar look and feel. If you don't like it, you can install a different one, and it will look completely different. So, if you find a picture of a distro that looks very nice, instead of changing distros, find out what desktop environments and configuration they are using, and just modify your existing setup. It is extremely simple, just a single one-line command will get the job done.

{{< figure src="/gnome.png" caption="GNOME Desktop" >}}
{{< figure src="/plasma-launcher.jpg" caption="KDE Plasma Desktop" >}}

---

For absolute beginners (and anyone with a brief understand - less than 6 months of hands-on experience), I recommend [Ubuntu](https://ubuntu.com/), [Pop!_OS](https://pop.system76.com/), or [Linux Mint](https://linuxmint.com/). These distros are very beginner friendly, have an easy trouble-free installation, and has the tools that you need to work right out of the box.

If you want a polished desktop with a slight resemblance to macOS, then Ubuntu or popOS might be better, as they use the GNOME desktop environment. Linux Mint uses Cinnnamon, a desktop environment from the creators of Linux Mint itself. This will be much easier for a transitioning Windows user. Even though it is customizable, it might not look as modern or polished as Ubuntu or popOS right out of the box.

## Preparing for Installation

Once you have chosen the distribution, head over to the website which I have referenced above. Click on the name of the distribution to navigate to the respective website.

Navigate to the download section and download the disk image. Usually there is just one download button, which will do the job, sometimes it might have different versions like stable, unstable, developer, insiders, VM images, etc. Just choose the main stable one. It is also possible that you might have to choose the correct download depending on the CPU architecture (Intel - X86-64, ARM, etc.).

Once you download the file make sure it ends with '.iso'. That is the disk image for the OS.

### Preparing the installation medium

Now, we need to create a bootable USB drive to install the OS. Traditionally CDs or DVDs were used, but know using a USB Flash Drive is the norm. There are programs that will help us easily format our flash drive in the right way with our disk image on it such that the computer will be able to recognize it and boot from it. I recommend balenaEthcer as it is cross-compatible with Windows, macOS and Linux, so that the steps won't change. In addition to that, it is dead simple to use.

Go to the [balenaEtcher](https://www.balena.io/etcher/) site and download their tool. Once you have downloaded and installed it, plug in your flash drive. Make sure the contents of the flash drive are safely backed up somewhere else, as we are going to completely format it and write it over. Once you are sure that the flash drive is safe to be formatted, open up balenaEthcer. 

![Balena Etcher](/etcher_file_select.png)

Click on select file, and select the ISO file you just downloaded. Then select the flash drive, which should automatically be selected if it is the only one plugged in. Make sure that the right drive selected. Then proceed, and in a few minutes your flash drive will be ready to install the distribution.

## Installing on Physical Hardware

> Warning: This is a beginner's guide and will go over the setup to install the Linux distro on your entire system, formatting your drive in the process. It will not go over dual-booting, creating a separate partition, etc. That will be posted soon in a future post. PLEASE BACKUP your entire data in advance as all of your files and the OS will get deleted.

Please read the above warning before continuing. An option to explore if you don't want to immediately install on actual hardware is a virtual machine. Software like virtualbox from Oracle allow you to quickly and easily create virtual machines (isolated boxes) running any distro or OS you want without affecting your computer. However, it has a minimum hardware requirement of at least 8GB of RAM/memory, at least 100GB of disk space, etc. to run smoothly.

---

Plug in your flash drive and boot up your computer. Enter the BIOS setup in your laptop or computer and make the following changes. You have to do this while your computer starts/boots up. This can be done usually by pressing F2, but it might differ depending on the computer you have. A quick search for the brand or hardware that you are using will get you the right key.

Then, make sure to set the flash drive to be at the top of the boot order. This will ensure that we boot from the flash drive instead of from the Hard Drive or SSD the normal way. 

Once you are done, exit the setup, and the distro of your choice should boot up. If it doesn't, then enter the BIOS setup and try toggling the option for Secure Boot.

---

When you see the desktop UI, you should be able to see some dialog, button or modal to install the Distro. Click it and follow the instructions. The setup is very simple and self-explanatory. I am just going to give you the choices that are important, and the gotchas.

**Using SSDs**

If you are using a SSD instead of a Hard Drive, it might not be detected. When you get to the section where it asks you to select the disk you want to use, make sure you check the size. It will not be exact, but make sure it is approximately similar to the maximum capacity of the SSD. If it is not, then you have to go into the boot setup again, and navigate to the section for SSDs. The name will depend on the computer you are using. Change Intel RST to AHCI. Then boot from the USB again, and you should be able to see your SSD correctly identified.

---

If it asks if you want a minimal or Normal installation, it depends on your preference. It is again self-explanatory, but anyways, it just means that they will pre-install helpful software such as an Office Suite, a video player, etc. to help you start using the computer right away.

Make sure you select the option to **Download Updates while Installing** so that it gives you a fully updated system. Most importantly, select the option to install **proprietary drivers** to make sure you can make use of your hardware to its fullest potential.

Then, choose the option to erase disk and install. This is the simplest option which will delete all your previous data and OS. Make sure that you have backed up your data. There are other options also to install it alongside the existing OS (dual-boot), but that is slightly complicated as you have to manually partition your hard drive or SSD. You can optionally encrypt the hard drive or SSD with a password. This is similar to BitLocker on Windows. It allows you to protect your data even if someone removes your hard drive.

Lastly, you will need to create an account on your computer with your name, username, password, and the name for your computer.

The installation will take a few minutes, maybe an hour, as it has to download all the software and format your disk.

Once it is finished, you will be asked to reboot your computer. While rebooting, it will ask you to remove the installation media (flash drive). Then you will be welcomed into your new OS/distro.

# Linux Fundamentals

## User privilege

Most operations can be done by clicking using your mouse. Sometimes, if required (like when installing software, you might need to install it using the terminal, you might get a 'Permission Denied' error. This means that you don't have permissions. What you can do is run the command as an administrator or a the 'root' user by prefixing the command using 'sudo'. Then it will ask for your password and check if you also have the admin privilege. If you do, it will successfully run. By default when you install a popular distro like Ubuntu, Linux Mint, or Pop!_OS, the new user created already has admin privilege, so you will not have any issues

## Installing Apps

This is the first thing you need to do when setting up your computer. Most Linux distros come with a package manager. This is a very unique concept that is unheard of in macOS and Windows. A package manager takes care of the entire installation process; there is no need to search for the right download link in a website, and go through a complicated installation wizard. All of the beginner-friendly distros that I mentioned above are based on Debian and some are also based on Ubuntu. For these distros, the default package manager is `apt`.

On most user-friendly distros, there will be a GUI application similar to the Windows Store or the Apple App Store to help you install software.

If it is not there, open the terminal app (usually accessible via the keybind <kbd>ctrl + alt + t</kbd>) and run the following command:

```bash
apt search {program name}
```

Replace {program name} with the actual name of the app you want to install. If you want to install Spotify for example, just search for it, and see if it is available. This command will help you find the correct app name as it might be different from what you might expect. The description of the app given can also help you identify it.

Once you find the right program, install it using:

```bash
sudo apt install {program name}
```

This will install the program. We add 'sudo' in the beginning to run the command with admin/root user privilege. It will list the names of the programs and the dependencies that it is going to install, and you need to confirm by typing 'y' when asked.

---

If the app is not available on the main `apt` repository, then you can try the snaps or flatpaks. I am not going through it in detail in this guide, but you can know that it is a way for an app to be easily distributed across all linux distributions easily. Usually, the snapstore is automatically installed on Ubuntu.

---

If it is not available in any of the repositories that I have mentioned (which is highly unlikely), all you need to do is go to their website, and they will give you instructions to install it from their. This may include downloading the binary from their site and then installing it. If you are using a Debian based distro, the binary file will end with '.deb' (similar to .exe in windows). Download it and try to open it. Mostly, your system will have a program installed it which is capable of recognizing the file and installing it for you.

Open the file manager (like windows explorer on windows) and go to the Downloads folder where the binary installer is located. Then right click in that folder to open in terminal. If your file is called for example 'skype_v2.deb', then run:

```bash
sudo apt install ./skype_v2.deb
```

---

Another option is might include an AppImage. This is a way to distribute software in an isolated manner across all distributions. Download the file which ends in '.appimage' from the website, and try to open it. If you are not able to open it, then right click on the file and open the permissions. Change it to 'executable' and then it should work fine.

---

If none of these options are given, you don't have to worry. Detailed steps or commands will be provided to you, and all you need to do is to paste them into the terminal and run them one by one in order. This is very rare, but you still might come across it. And since, you use a Debian based system which is one of the most popular distros, you don't need to worry about some software not being available.

# Recommended Software

Some new users might not be aware of the software that is available, or the good open source alternatives. So I have compiled a list of software that can be good to have.

1. Video Conferencing

    - [Skype](https://www.skype.com/en/get-skype/) (Native App) (from Microsoft - Propreitary)
    - [Jitsi](https://meet.jit.si/) (Web App) (Open Source)
    - [Discord](https://discord.com/) (Web and Native App) (Proprietary)
    - [Zoom](https://zoom.us/download#client_4meeting) (Native App) (Proprietary)
    - [Teams](https://www.microsoft.com/en-us/microsoft-teams/download-app#desktopAppDownloadregion) (Native App) (from Microsoft - Proprietary)

2. Office Suite

    - [Libre Office](https://www.libreoffice.org/download/download/) (Native App) (Open Source)
    - [Microsoft Office](https://www.office.com/) (Web App) (Proprietary)

3. Multimedia player

    - VLC media player
    - Celluloid

4. Browser

    - Brave (chromium based)
    - Chrome (chromium based)
    - Chromium (open source)
    - Firefox
    - LibreWolf (privacy oriented fork of Firefox)

5. Music Streaming

    - [Spotify](https://www.spotify.com/in-en/download/linux/) (Web and Native App) (proprietary)

6. Note-taking (My top favorites)

    - [Obsidian](https://obsidian.md/) (Native App) (open source)
        - It uses Markdown syntax
        - Has a knowledge graph and other advance features for note-taking
    - [Notion](https://www.notion.so/) (Web app)
        - Simple, friendly user interface
        - Does not need markdown knowledge
        - Has a lot of templates to choose from

7. Mail clients

    - Just use the browser version (Gmail, Outlook, Yahoo, etc.)
    - [Mailspring](https://getmailspring.com/) (open source)
        - Inlcudes fancy features such as link tracking, checking number of opens, etc.

# Getting Help

One of the wonderful thing about Linux is the online community. If you exclude the hate in the internet, it is very easy to find help, articles, tutorials/guides, and forums to get help in Linux. This is partly because of the very specific and helpful error messages that Linux gives rather than the blunt ones that you get on Windows or macOS. Just google the question, and you are 99.9% of the time going to get a helpful response. Checkout the Ubuntu forums, sub reddits, blogs created by others, and some discord communities.

Lastly, I am always there to help too if you have any questions. Let me know in the comments if you have any questions, and I will try my best to get it sorted out. You can also reach me via email, twitter, or other platforms. Checkout the main homepage for more details.
