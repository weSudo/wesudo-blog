---
layout: post
subtitle: We have more flavors than Mac and Windows combined.
published: false
title: Untitled
---

##What are Distros?

In the last post we wrote about the Linux[kernel]. The most important thing to remember is that the kernel and the operating system are very different. When we speak of the kernel (just the kernel) we generally mean all the background processes that the OS performs; this may mean the memory allocation algorithms that keep running, the algorithms that write data to the hard disk.
 
The kernel interacts directly with the hardware i.e. the ram, the network adapters, the keyboard, the mouse et cetera. When we install new hardware we install drivers for the hardware too. It is because the kernel does not know how to communicate with a particular hardware, say the latest graphics card or your new printer. In a situation like this we need to tell the kernel how to talk with the hardware and this is where the device drivers come into play.
As a matter of fact, the user interface is not a part of the kernel. The user interface is implemented above the kernel, thus hierarchically the user interacts with the computer via the user interface. The user interface in turn interacts with the kernel. When we say that a person is running Linux it means that he/she is running the Linux kernel. This is very confusing since Linux being open-source there are lots of OSes out there that use the Linux kernel. These are called distros [short for distribution]. There are thousands of Linux distribution to choose from.
Each distribution also has divisions called flavors. we will get to that in a bit.

Each distro is like a separate OS but the kernel is the same, well different occasionally. The different distros originated because -- 
some time back during the development days someone had differences with their fellow developers and said "I'm gonna create a separate OS with all the features I like. You do it your way I'll do it my way". Maybe? Whatever!

This picture shows the number of distros based on Linux. Yes; it can be measured COSMICALLY.
![Linux Tree Flow Chart]({{site.baseurl}}/http://www.telemetro.dk/LIST-OF-LINUX-DISTRIBUTIONS.png)

So this is like we have parent distros with stable releases and long-time supports and spin-off distros based on these major distributions. For example, the distro Ubuntu which I use is based on [Debian]( https://www.debian.org/). So mathematically Debian is a superset of Ubuntu. Similarly, [Kali Linux]( https://www.kali.org/) is a penetration testing OS or in vague and noob terms a hacking OS, which is also based on Debian. Thus Kali and Ubuntu are like brothers. Whatever runs on Ubuntu will run on Kali and MUST run on Debian too. Debian was created by [Ian Murdock]( https://en.wikipedia.org/wiki/Ian_Murdock) (DEB=name of wife, IAN=his name). Ian passed away recently at the mere age of 42.

So what’s the difference between different distros?

The most important fact is that these are Open-Source projects. Which means that any individual or a group are doing it for pro bono. The main difference is the organization which maintains it. For example, [Canonical]( www.canonical.com/) maintains [Ubuntu]( www.ubuntu.com/); Offensive Security maintains Kali Linux; Red Hat maintains [RHEL]( www.redhat.com/en) (Red Hat Enterprise Linux). This however does not mean that the distros have to be free (as in free beer). The Linux kernel is free (free as in free beer and free speech) but the distros have no obligation to be free. It’s the noble people at the organizations that decided that Ubuntu should be free and RHEL should not.

Another important deciding factor is the targeted user base. Ubuntu is targeted to the common everyday user (someone who never used Linux before), while Kali is specifically for Hackers/Pen-Testers while RHEL is designed for high end Servers. [Fedora]( https://getfedora.org/) is targeted towards more advanced everyday users.  This however is not obligating anyone who wants to use Ubuntu for ethical hacking, they could just download the required software on Ubuntu and use it. Similarly, many "advanced" users also use OS like Kali Linux even for simple everyday tasks like checking mails, editing pictures, listening to music and web browsing.

So it eventually depends on what you use the OS for, not on what that particular OS has to offer. Go to [this link]( distrowatch.com/) to browse the latest to earliest Linux distros. While we come up with our new post on the Top Ten Distros, as reviewed by us.

Comment. Share. And don’t forget to mention what would you like to hear from us next. Either drop in your suggestion in the comments below or you can go to the Contact Us page and fill out the simple form.
