---
title: "\"What Linux distro should I start with?\""
description: "After being asked so many times, it's finally time for me to address this question."
date: 2023-04-07
tags: ["linux", "desktop", "linux-distros", "question"]
# cover:
#   image: "linux-computer-hero.jpg"
#   alt: "Stable Diffusion-Generated Tux Looking at a Laptop"
---

It really doesn't matter.

Beginners often make choosing their first Linux distribution a bigger deal than it needs to be. This is mainly due to the overwhelming number of options available.

A Linux distribution is essentially a collection of software packaged together. The two key components of most distributions are the Desktop Environment (DE), which provides the graphical user interface for users to interact with the operating system, and the Package Manager, which manages the installation, removal, and updating of software on the operating system.

Many Linux "geeks" recommend choosing a distribution right away, but I disagree. I suggest choosing a DE first, as it is what you'll be interacting with the most to complete tasks on your computer. There are several excellent options available, and it's primarily a matter of personal preference.

## Choosing a Desktop Environment

For beginners, I recommend selecting one of the following DEs:
- {{< logo src="kdeplasma.png" alt="KDE Plasma logo" >}} [KDE Plasma](https://kde.org/plasma-desktop/)
{{< figure src="kdeplasma.png" alt="KDE Plasma's Interface" align=center >}}
- {{< logo src="gnome.png" alt="GNOME logo" >}} [GNOME](https://www.gnome.org/)
{{< figure src="gnome.png" alt="GNOME's Interface" align=center >}}
- {{< logo src="cinnamon.png" alt="Cinnamon logo" >}} [Cinnamon](https://wiki.archlinux.org/title/cinnamon)
{{< figure src="cinnamon.webp" alt="Cinnamon's Interface" align=center >}}
- {{< logo src="xfce.png" alt="Xfce logo" >}} [Xfce](https://www.xfce.org/)
{{< figure src="xfce.jpg" alt="Xfce's Interface" align=center >}}
- {{< logo src="mate.png" alt="MATE logo" >}} [MATE](https://mate-desktop.org/)
{{< figure src="mate.png" alt="MATE's Interface" align=center >}}
- {{< logo src="lxqt.png" alt="LXQT logo" >}} [LXQt](https://lxqt-project.org/)
{{< figure src="lxqt.png" alt="LXQT's Interface" align=center >}}

KDE Plasma, GNOME, and Cinnamon are considered more modern and feature-rich desktop environments, while Xfce, MATE, and LXQT are more lightweight and customizable. All of these options are actively developed/maintained and quite stable.

### Tips for Choosing a Desktop Environment
- ***Don't stress about it***. The more you procrastinate actually choosing a DE, the worse. Most DEs are customizable, so you can make them look and feel however you want after installing them, or even switch to another DE entirely if you ever need to.
- **Try them out**: Most Linux distributions allow you to test out different DEs before installing them. Take advantage of the opportunity to test different DEs to see which one you prefer. You can use a live USB or a virtual machine to test any DE or Linux distribution.
- Consider your **system specs**:
  - If you're running really old hardware, I would recommend [Xfce](https://www.xfce.org/) or [LXQt](https://lxqt-project.org/). They're lightweight and don't require a lot of resources.
  - If you're running newer hardware, most DEs will work just fine. Almost **all DEs run better than Windows**, so you can't go wrong with any of them.
- If you're on a laptop and want really good gesture support, I would recommend [GNOME](https://www.gnome.org/) (although a lot of other DEs are good enough these days).
- Don't choose a *new* and *shiny* DE if you are not experienced enough. **I recommend sticking to the ones I listed above.** They're all **stable** and have a **lot more support**.

After choosing a DE, you can choose a distro that uses that DE.

## Choosing a Distro

There are three main types of Linux distros:
- {{< logo src="debian.png" alt="Debian Logo" >}} **Debian-based distros**: These are known for its stability and reliability. Examples include Ubuntu, Linux Mint, Pop!_OS, Zorin OS, and elementary OS.
- {{< logo src="arch.png" alt="Arch Linux Logo" >}} **Arch-based distros**: These are known for being on the "bleeding-edge". Examples include Artix, Manjaro, EndeavourOS.
- {{< logo src="redhat.png" alt="Red Hat Logo" >}} **Red Hat-based distros**: These are known for being the good middle ground between stability and up-to-date software. Examples include Fedora, CentOS, Nobara, Ultramarine, RisiOS, and RHEL.

### Tips for Choosing a Linux Distro
- Use the same distro as your friends. This will make it easier to help them with their problems, and they can help you with yours.
- Just like when it comes to your desktop environment, choose a well-known and established distro. They have more support and are usually more trustworthy.

The two distros that I feel confident recommending to most people are:
- {{< logo src="fedora.png" alt="Fedora Logo" >}} [Fedora](https://getfedora.org/) (Red Hat-based) - This is the distribution that I use and recommend to everyone. It's stable, reliable, and easy to use, with many customization options.
  - Supported DEs: [GNOME](https://getfedora.org/en/workstation/) (official) and [KDE Plasma](https://spins.fedoraproject.org/en/kde/), [Xfce](https://spins.fedoraproject.org/en/xfce/), [MATE](https://spins.fedoraproject.org/en/mate-compiz/), [Cinnamon](https://spins.fedoraproject.org/en/cinnamon/), [LXQt](https://spins.fedoraproject.org/en/lxqt/), [LXDE](https://spins.fedoraproject.org/en/lxde/) (spins) and [others](https://spins.fedoraproject.org/).

- {{< logo src="linuxmint.png" alt="Linux Mint Logo" >}} [Linux Mint](https://linuxmint.com/) (Ubuntu-based -> Debian-based) - This is the distribution that I recommend to people who are new to Linux and want a stable experience with very few problems. It's also easy to use and highly customizable. If you're thinking of choosing the [Cinnamon](https://linuxmint.com/download.php) desktop environment, this is the perfect distribution for you, as it's made by the same developers.
  - Supported DEs: [Cinnamon](https://linuxmint.com/edition.php?id=302) (main), [MATE](https://linuxmint.com/edition.php?id=303), [Xfce](https://linuxmint.com/edition.php?id=304).

---

If you're still not sure which distro to use, you can install a virtual machine (or live USB) with any one that you want! You don't need to install it on your main computer straight away!

Also, what many people don't know is that any distro can practically be turned into any other distro.

So... Just pick one.