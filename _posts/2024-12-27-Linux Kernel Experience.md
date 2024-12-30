---
title: My Linux Kernel Mentorship Experience
date: 2024-12-27 13:20:00 +/-TTTT
categories: [Linux]
tags: [Linux Kernel Mentorship]
author: leebeck3
description: a summary of my experience with the Linux Kernel Mentorship.
comments: false
toc: false
---

Hello, this is a blog about my experience with the 2024 Linux Kernel Mentorship.

# Why I picked the Linux Kernel

I had a couple of reasons behind why I wanted to get involved with the linux kernel.

1. The first reason was that I wanted to learn and grow myself.
2. The second reason was to expand my technical skillset.
3. The final reason was to improve my communication of hard-to-grasp technical concepts and boil them down into an easy-to-use format, improving my communication skills in the process.

# My Experience

Coming into this internship I had no experience with C, I had a minor amount of experience with C++ and had also looked into GO and Rust but have no expertise in any of those languages. I opted to dig into C with Linux as it gave me a semi-structured environment to expand my low-level programming skills. Focusing on one project enabled me to get out of the programming language debate. Focusing on what matters as a developer, building a great product.

I started by building out one of my personal servers as a Debian server for all of my development. Once that was done I then dug into HID devices, including learning about keymaps and how drivers are structured. 

I then dug into KVM, trying to learn about how virtualization works at the low-level within Linux. This enabled me to tie in a lot of my experience as a admin/engineer to better understand the systems I work with normally.

Unfortunately with all of this learning I forgot to actually focus on getting some commits into the code, due to time constraints I wasn't able to start actively digging into committing until late October. 

Fortunately, around this time on discord I saw that Josef Bacik in btrfs was looking for people to help in btrfs so I opted to message him and see if I could help out. This turned out to be a great decision on my part as I wound up doing some work on a couple of red-black binary trees, specifically shortening some boilerplate, which got me all the commits I was required to do.

Now this took me a bit of time to fully figure out as I had absolutely no idea what I was doing so I wound up spinning my wheels and making a lot of really dumb mistakes, however, I persevered through it and was able to accomplish sending out the first 6 patches on the first week of December.

Also, while working with Josef I was introduced me to the idea of performance engineering, this was great as it led me to start digging into gdb, disassembling programs, and assembly as well as flamegraphs.

# Next Steps
I thought this was a great opportunity as it allowed me to get into the nuts and bolts of how Linux works, it's also useful as it enables me to practice C more, I'm currently working on part of the ENOSPC rework[https://github.com/btrfs/btrfs-todo/issues/53] and am planning to contribute to that pretty heavily before I fully consider myself done with this internship. Overall I really enjoyed my experience as the internship enabled me to jump into a new tech stack, learn a ton of new things, and overall improve my understanding of the ecosystem my career is in. It also is pretty great because I have a much better understanding of the fundamental systems I'm working on as well as what to do with stacktraces, coredumps, etc.
