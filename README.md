# Born2beRoot Project

## Introduction

The Born2beRoot project is a system administration exercise that introduces the world of virtualization. You will create your first machine in VirtualBox (or UTM if you can’t use VirtualBox) under specific instructions. Then, at the end of this project, you will be able to set up your own operating system while implementing strict rules.

## Mandatory Part

- Since it is a matter of setting up a server, you will install the minimum of services.
- A graphical interface is of no use here. It is therefore forbidden to install X.org or any other equivalent graphics server.
- You must choose as an operating system either the latest stable version of Debian (no testing/unstable), or the latest stable version of Rocky. Debian is highly recommended if you are new to system administration.
- Setting up Rocky is quite complex. Therefore, you don’t have to set up KDump. However, SELinux must be running at startup and its configuration has to be adapted for the project’s needs.
- AppArmor for Debian must be running at startup too.
- You must create at least 2 encrypted partitions using LVM.

## Bonus Part

- Set up partitions correctly so you get a structure similar to the one below.
- Set up a functional WordPress website with the following services: lighttpd, MariaDB, and PHP.
- Set up a service of your choice that you think is useful (NGINX / Apache2 excluded!). During the defense, you will have to justify your choice.
- To complete the bonus part, you have the possibility to set up extra services. In this case, you may open more ports to suit your needs. Of course, the UFW/Firewalld rules have to be adapted accordingly.
- The bonus part will only be assessed if the mandatory part is PERFECT. Perfect means the mandatory part has been integrally done and works without malfunctioning. If you have not passed ALL the mandatory requirements, your bonus part will not be evaluated at all.
