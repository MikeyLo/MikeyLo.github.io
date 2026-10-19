---
layout: post
title: "Reviving and Old Dell Optiplex 990 with Pop!OS"
---

---
layout: post
title: "Reviving a Discarded Dell OptiPlex: From CMOS to Linux"
---

I'm a precision machinist working my way into IT. This blog is where
I'll document what I'm learning, mistakes included. First up: a free
computer.

## The machine

Someone was giving away a Dell OptiPlex, so I took it. It turned out
to have an i7 and a 2 TB SSD, which is a lot of computer for free. It
came with Windows already installed.

![The OptiPlex](/assets/images/optiplex.jpg)

## The first problem: it kept forgetting

Every time I shut it down, it lost its BIOS settings. Clock, boot
order, all of it. That pointed to the CMOS battery, the little coin
cell that keeps those settings alive when the power's off.

I popped out the old one, put in a new CR2032, and the problem went
away. It was a small fix, but it was my first real diagnosis on this
machine, and it felt good.

![Swapping the CMOS battery](/assets/images/cmos-battery.jpg)

## Why Linux

The Windows install was older, and keeping it going would have meant
TPM workarounds to stay current. I'd rather learn something new. So I
decided to put Linux on it and run Windows in a virtual machine if I
ever need it.

I chose Pop!_OS. Honestly, I didn't have a deep reason. It looked
beginner-friendly, and that was enough to get started. I may try
other distros later, and I'll write about that if I do.

## The gotcha: the display

I don't have a proper monitor for it, so I'm using old TVs. The first
one showed doubled images, which made it unusable. I switched to a
32-inch LG, which mostly behaves. It's not perfect, but it works.

[Add: what fixed it, or what you think caused it, if you know]

## Where it stands

It boots, it remembers its settings, and it runs Linux.
[Add: a quick "proof of life," like browsing archive.org]

![Pop!_OS running](/assets/images/popos-desktop.jpg)

## What's next

I haven't fully set this machine up yet, because I'm still deciding
how much of my personal life belongs on a project computer. That
question deserves its own post: how to build a separate, secure
identity for lab work, maybe starting with a Proton Mail account.

Thanks for reading. I'm learning as I go, and digging up strange music on archive.org along the way
