---
id: Linux
aliases: []
tags: []
---

# Linux Knowledge Base

Welcome to my Linux notes. Here you can find all kinds of notes regarding Linux (obviously) like, filesystems, navigation, system tools, distros and their philosophy, scripting and scripting-related (awk, sed, grep), kernels and drivers, system administration and package management and different types of package managers and my dotfiles and personal scripts that I use everyday.

I've been using Linux since my childhood and it plays a integral part in my everyday software usage. So this is one of the most important knowledge that I have in this knowledge vault.

So, starting up, Linux is a open source operating system based on the Linux kernel. So, it's not actually a pure operating system but a kernel on top of which the operating system is built.

## Distros

There are many Linux operating systems or Linux distribution or shortly called [[Distro|distros]] by the community. Each of these distros have their own philosophy of operating system Arch is known for its DIY nature, Debian is known for its simplicity and NixOS is known for its declarative and reproducibility nature.

Most of these distros, have their own derived distros like Arch-Based (Manjaro, Endeavour) and Debain-Based (Ubuntu, Linux Mint). This is to make them more usable out of the box and enjoy the advantages of their package managers.

## CLI/Terminal utilities

Linux is also known for its command line or the terminal. There are lots of [[CLI|CLI tools]] supported and made for Linux to ease the workflow.
Some of the CLIs don't only work as text-based CLIs. They also provide a user interface called as TUIs (Terminal User Interface) which is keyboard-driven.

## Networking

Linux is known for its important role in [[Linux-Networking|Linux-Networking]]. About 96% of the top 1 million servers runs on Linux and its due to its stability and its nature of lightweight. There are lots of CLI tools that are made to simplify Linux networking majorly after the the raising popularity of [[Golang|Golang]] which is sometimes also called "Language of the Cloud".

## Kernel

[[Kernel|Linux Kernel]] is one of the most lightweight and one of the most efficiently functioning kernels out there. Here, there are notes about my Linux kernel knowledge, like user space and kernel space, syscalls, compiling kernels, different types of Linux kernels and much more.

## Package Management

When it comes to [[Packaging|package management]] in Linux, there are many package managers for different distros like pacman, apt, yum, dnf, flatpak, snap(one of the most hated) and much more. All these package managers have their own pros and cons.

## Dotfiles Management

This is one of the most interesting parts of Linux is that its extremely customisable for the user's needs, be it for the workflow or be it for the eye candy. [[dotfiles|Dotfiles-management]]. 

### Structure

```bash
Linux/
├── Linux (Index).md
├── Concepts/
│   ├── What is Linux?.md
│   ├── Unix Philosophy.md
│   ├── GNU vs Linux.md
│   ├── Everything is a File.md
│   ├── Linux Kernel vs User Space.md
│   ├── Open Source and Copyleft Licensing.md
│   ├── POSIX Compliance.md
│   ├── /proc and /sys Explained.md
│   ├── Linux File Hierarchy Standard (FHS).md
│   └── Linux User Groups and Permissions Model.md
├── Terminals and Shells/
│   ├── What is a Terminal Emulator?.md
│   ├── TTY vs PTY.md
│   ├── What is a Shell?.md
│   ├── Login Shell vs Non-login Shell.md
│   ├── Interactive vs Non-Interactive Shell.md
│   ├── Bash vs Zsh vs Fish.md
│   ├── Shell Prompt and PS1.md
│   ├── Writing Your First Bash Script.md
│   ├── Shell Expansion and Quoting Rules.md
│   ├── Dotfiles.md
│   ├── Terminal Multiplexers.md
│   └── REPL and Shell History Internals.md
├── Linux Architecture/
│   ├── User Space vs Kernel Space.md
│   ├── Monolithic Kernel Design.md
│   ├── System Calls and Syscall Interface.md
│   ├── Signals and Traps.md
│   ├── fork() and exec() Family.md
│   ├── Process Lifecycle.md
│   ├── PID, PPID, and Process Trees.md
│   ├── Context Switching Internals.md
│   ├── Process Scheduling with CFS.md
│   └── How strace Works.md
├── Kernel & Internals/
│   ├── Linux Kernel Overview\.md
│   ├── How to Compile the Kernel.md
│   ├── Linux Kernel Modules.md
│   ├── procfs vs sysfs.md
│   ├── udev and Hotplugging Devices.md
│   ├── Cgroups.md
│   ├── Namespaces.md
│   ├── eBPF and Observability.md
│   ├── Preemption in Kernel.md
│   ├── Kernel Panic.md
│   ├── Realtime Kernel.md
│   ├── Device Tree.md
│   └── Writing a Kernel Module.md
├── Boot Process/
│   ├── Full Linux Boot Sequence.md
│   ├── BIOS vs UEFI.md
│   ├── Power-On and POST.md
│   ├── MBR vs GPT.md
│   ├── What is a Bootloader?.md
│   ├── GRUB2 Configuration.md
│   ├── GRUB vs systemd-boot.md
│   ├── Chainloading.md
│   ├── /boot Directory Structure.md
│   ├── initrd vs initramfs.md
│   ├── Kernel Loading.md
│   ├── What is init?.md
│   ├── systemd Boot Target Flow\.md
│   ├── systemd-analyze.md
│   └── Debugging Boot Failures.md
├── Command Line & Coreutils/
│   ├── Essential GNU Commands.md
│   ├── Basic File Commands.md
│   ├── find and xargs.md
│   ├── cut, sort, uniq, tee, head, tail.md
│   ├── grep vs ack vs ripgrep.md
│   ├── sed.md
│   ├── awk.md
│   ├── tr and wc.md
│   ├── env and export.md
│   ├── Pipes and Redirection.md
│   ├── Job Control.md
│   └── PATH and Environment Variables.md
├── Filesystems & Storage/
│   ├── What is a Filesystem?.md
│   ├── ext4.md
│   ├── Btrfs and ZFS.md
│   ├── Filesystem Comparison.md
│   ├── Inodes and Metadata.md
│   ├── File Allocation Methods.md
│   ├── Mounting and fstab.md
│   ├── Loop Devices.md
│   ├── Virtual Filesystems.md
│   ├── LVM.md
│   ├── RAID and mdadm.md
│   ├── Block vs Character Devices.md
│   ├── udev Rules.md
│   └── Disk Partitioning.md
├── Networking/
│   ├── Network Interface Basics.md
│   ├── ip vs ifconfig vs nmcli.md
│   ├── Netplan and systemd-networkd.md
│   ├── Sockets in Linux.md
│   ├── Networking Tools.md
│   ├── iptables and nftables.md
│   ├── DNS and /etc/hosts.md
│   ├── ARP, ICMP, DHCP.md
│   ├── firewalld and ufw\.md
│   ├── VPN Setup.md
│   ├── Network Namespaces.md
│   ├── Wireshark and tcpdump.md
│   ├── Netstat vs ss vs lsof.md
│   └── Linux Network Stack.md
├── Security & Permissions/
│   ├── File Permissions Explained.md
│   ├── chmod, chown, umask.md
│   ├── sudo vs su.md
│   ├── Linux Capabilities.md
│   ├── /etc/shadow and passwd.md
│   ├── PAM.md
│   ├── SSH Security.md
│   ├── Rootkits and Malware.md
│   ├── Lynis Hardening.md
│   ├── Secure Boot.md
│   └── Auditd.md
├── System Administration/
│   ├── User Management.md
│   ├── useradd vs adduser.md
│   ├── systemctl Service Management.md
│   ├── Timers and Cron.md
│   ├── Logs and journald.md
│   ├── systemctl status.md
│   ├── Root Recovery.md
│   ├── Backup Tools.md
│   ├── Software Updates.md
│   ├── Resource Limits and ulimit.md
│   ├── Monitoring Tools.md
│   ├── Log Rotation.md
│   └── Debugging Daemons.md
├── Package Management/
│   ├── Package Manager Comparison.md
│   ├── What are Repositories.md
│   ├── PPAs and Third-Party Sources.md
│   ├── dpkg Internals.md
│   ├── .deb Package Structure.md
│   ├── pacman.md
│   ├── Flatpak vs Snap vs AppImage.md
│   ├── nix Package Management.md
│   ├── Binary vs Source Packages.md
│   └── Static vs Dynamic Linking.md
├── Distros & Ecosystem/
│   ├── What is a Distro?.md
│   ├── Debian vs Fedora vs Arch.md
│   ├── NixOS Explained.md
│   ├── Rolling vs Stable Release.md
│   ├── Systemd Debate.md
│   ├── Linux on Phones.md
│   ├── Server vs Desktop vs Embedded.md
│   └── Yocto and Buildroot.md

```

Parent Node: [[Table of Contents]]

---
