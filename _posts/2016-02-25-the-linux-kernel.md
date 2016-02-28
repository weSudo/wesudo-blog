---
layout: post
title: What is the Kernel 
published: true
subtitle: It's all Linux
author: Rainer
---

The Linux Kernel
================

Over the past couple of posts we have been talking a lot about the Linux Kernel and how it is this huge global phenomenon but we have never talked about the Kernel itself. This post is going to fix all that.

## Let us first understand what is a Kernel!

A kernel is the core of an operating system. An operating system is a software helps the user interact with the computer. Without an operating system the user would have to interact directly with the computer hardware. Back in the early days to change a program the entire computer had to be rewired(ENIAC) and today we just tap/click on the desired program to launch it. All this is enabled by the increased complexity of the computer system and the operating systems that help us interact with the hardware.

One might ask what is the difference between a Kernel and an OS. The kernel is part of the OS is provides the core functionality to an OS. These core functionalities include memory management, process management, file management, networking, device management(device drivers). On top of these various applications run that make up the full and complete OS. For example in Ubuntu the file management that the kernel provides is used by the file manager(Caja, Nautilus).

This is a map of the Linux Kenel By Conan at English Wikipedia.![kernel_map.png]({{site.baseurl}}/img/kernel_map.png)

## Now why is the Linux Kernel is so special?

Firstly the Linux Kernel is Open source and it is maintained collaboratively by an exceptionally large group of dedicated and talented professionals. But, this is not where the pros for the Linux Kernel ends. There is a technical side to this discussion too! 

To discuss the features of the Linux Kernel *here* would be definitely stupid so we will limit ourselves to the most important ones. I will be posting my sources for you to check them yourself.

The [Wikipedia](https://en.wikipedia.org/wiki/Linux_kernel) page of the Linux Kernel says that it is a *Unix-like* operating system kernel. What this means is that the Linux Kernel is like the Unix Kernel however it is not exactly like the Unix Kernel.

Further down here we will talk about the design or the architecture of the Linux Kernel and its most prominent technical features. Hold on!!

Again from Wikipedia: The Linux kernel is a monolithic kernel, supporting true preemptive multitasking, virtual memory, shared libraries, demand loading, memory management, the Internet protocol suite, and threading. Device drivers and kernel extensions run in kernel space with some exceptions where they do run in user space. The Graphics system does not run with the kernel itself instead it runs on top of the kernel. The Linux kernel is also modular and the functionality of the kernel can be drastically extended via loadable modules. These modules can be loaded/unloaded on the fly i.e. dynamically while the system is running.

We need clear up the jargon above but before we do so we need to clarify two terms that we will use in the descriptions:-
In a computer the kernel along with other application is just a program that is sharing the processor time and virtual memory. The virtual memory is segregated into the kernel space and the user space. The kernel space is that part of the memory that is to be used by the kernel. Similarly the user space is the part of the memory which is addressable legally only the user applications. This helps to implement memory protection.

The Linux Kernel is a monolithic Kernel. - This means that the Linux kernel runs entirely in the kernel space. This has some design befits as it eliminates the overheads in micro-kernels since all the functions of the kernel can be invoked directly from a single address space.

It supports preemptive multitasking - This means that the Linux Kernel or rather its process scheduler can suspend one running process and allow another process to run. Thus both the process can share some CPU time. This is also called time-sharing. This in turn is very beneficial since the Linux Kernel supports multi-user multi-tasking. Thus two processes from two users can run simultaneously without having to wait for the first one to end.

Virtual memory is a feature of an OS that allows it transfer some pages from its main memory(RAM) to the disk so as to compensate for low memory. We know this as the swap memory space. Demand loading is a method used to manage the virtual memory.

To understand shared libraries we need to understand what are libraries. In computer science a library is a collection of computer programs that can be used to develop software. These libraries are generally non-volatile. Shared libraries means that the programs can be shared by one or more applications.

Memory management is the act of managing computer memory on a system level. The essential requirement of memory management is to provide ways to dynamically allocate memory when it is required and to free it when not required. This is particularly important in computer systems that support multitasking.

In computer science a thread is the smallest sequence of programmed instruction that can be handled by a scheduler. The scheduler is a part of the Operating System. This is very essential to multi tasking. When the user runs two programs simultaneously the processor does not run both the programs at the same time, instead it runs one program(or thread) and switches to the other thread. This is implemented by time-slicing as each thread shares a time-slice of the whole CPU time. This switching between the two threads happens so often that the user perceives them to be running simultaneously. Without threading multi-tasking on single-CPU computers would not be possible as one program would have to wait for the other one to finish executing.

These are just *some* of the things that make the kernel special. If we were to discuss ALL the features of the kernel then this post would not end. So! I guess thats the end of this post.
Thanks for reading, and point out some errors if any!
Comment. Share. And don’t forget to mention what would you like to hear from us next. Either drop in your suggestion in the comments below or you can go to the Contact Us page and fill out the simple form.
