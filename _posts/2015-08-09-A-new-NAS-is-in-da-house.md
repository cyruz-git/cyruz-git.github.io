---
layout: post
title: A new NAS is in da house
tags: network disks nas hacks projects github
---

I was running out of available space on my old, double drive (2 x 2TB) external disk, so I bought a new couple of hard 
drives (2 x 4TB) and found a deal for an old [Thecus N5200](http://www.thecus.com/product.php?PROD_ID=5) BR on a forum 
I visit frequently.

It's a 5 disks SOHO NAS with an integrated Gigabit switch and some USB ports. The original firmware of the N5200 
doesn't support hard drives bigger than 1TB, so I investigated the possibility to install a custom Linux and found a 
lot of links of people who did it with success. I bought it.

The hardware isn't top notch, but a Celeron-M 600 and 256 MB of DDR are quite adeguate for a file server. The RAM can 
be replaced, so can be the internal 64 MB DOM. I opted for a Debian Wheezy (oldstable) installed on a usb flash drive. 

After installing the system I wrote a couple of scripts to make use (sorta) of the leds, the lcd and the buttons. 
Everything related to this small project it's on [GitHub](https://github.com/cyruz-git/thecus-n5200).

Maybe I will detail all the steps next time...
