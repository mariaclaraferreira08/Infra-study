

## What is Linux?
An open-source (free software) computer operating system—meaning it is free of charge and "malleable"—that allows anyone to study, modify, and adapt the system to their needs. Created by Linus Torvalds (the same creator of Git).

## What are the main Families and Distributions?
Versions of the operating system based on Linux, created for different uses.
Red Hat Family: focused primarily on servers and corporate environments. Examples: Red Hat Enterprise Linux (RHEL), Fedora, AlmaLinux, and Rocky Linux.
Debian Family: Debian, Ubuntu, Linux Mint, Pop!_OS, Kali Linux, among others. Widely used on both personal computers and servers.

## Basic commands (Ubuntu)
cd → (change directory): a directory is the same as a folder in Windows. It is like walking through a house: you are in "home" (your house) and go to the "living room" (which is inside the house). Example:
cd livingroom

Now the path would be:
/home/livingroom


ls → lists everything inside the current directory (for example, inside "home": livingroom, kitchen, bathroom, bedroom1...).

pwd → shows where I am right now.
Example:
pwd

Result:
/home/livingroom


mkdir → literally "make directory." It is like building a new room for the house (or creating a new folder in Windows).
mkdir bedroom2


touch → creates a new empty file. Following the house analogy, it is like putting a new piece of furniture inside a room.
touch sofa.txt


cp → makes a copy of a file to another location. It is like buying another identical piece of furniture and putting it in another room.
cp sofa.txt bedroom1

(The second element is the copy's destination.)

mv → moves a file to another place. It is like taking the sofa from the living room and putting it in bedroom2.
mv sofa.txt bedroom2

Now the sofa is no longer in the living room; It was moved to room 2.

rm → remove (deletes) a file. Following the analogy, it would be like throwing the piece of furniture away.
rm sofa.txt


sudo → executes a command with administrator (superuser) permissions. It is frequently used with commands like `apt install`, but can be used with many other commands.

apt (or apt-get) → package manager for Ubuntu and other Debian-based distributions. It is used to install, update, remove, and manage system programs.
Examples:
sudo apt update
sudo apt install git
sudo apt remove git
sudo apt upgrade

etc → system configuration files: stores important configuration files for Linux and installed programs. It is like the "settings hub" of the house.

bin → essential system commands: the `/bin` directory contains basic programs needed for the system to function. These are commands that any user might need to use.

usr → user programs and files: the `/usr` directory stores most of the programs installed on the system and files used by users.

tmp → temporary files
The `/tmp` directory stores temporary files created by the system and programs. It is like a temporary table where you place things that don't need to be kept.