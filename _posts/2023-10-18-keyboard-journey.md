---
layout: post
title: 'My Keyboard Journey'
date: 2023-10-18
categories: blog
---

# My Keyboard Journey

## Introduction

Welcome to my blog, I am surprised you found your way here!

This is my first post through which I would like to tell you my journey using different
keyboards for the past few years in a non technical way.

As a short introduction, I am a computer science student in the 7th - hopefully also last - semester
of my bachelors with interest in embedded programming, Linux and _keyboards_.

## 'Classic' Keyboards

First I humbly started out with some cheap membrane Logitech keyboards. I stayed for quite a while
in the membrane lane, many a year at that, before I realized the potential mechanical keyboards had.

I then quickly grabbed and used various keyboards such as a [Corsair K70](https://www.corsair.com/us/en/p/keyboards/ch-9000069-na/corsair-gaming-k70-mechanical-gaming-keyboard-cherry-mx-red-ch-9000069-na),
with a linear red switch, or a [Logitech G512](https://www.logitechg.com/en-us/products/gaming-keyboards/g512-mechanical-gaming-keyboard.html)
with, imho, just simply weird Logitech tactile switches - which actually made me
despise tactile - brown switches in general - switches for a long long time. Most if not all were
full-sized keyboards at that, taking up my whole desk. Along the first semester of university I then
ordered a Keychron K2, although I don't remember the reasons anymore. It was a nice keyboard,
Keychron was just starting out and I enjoyed the linear reds and the RGB backlight.

![Keychron K2](/assets/keychron_k2.jpg)

I felt I had arrived at my destination. 75% was just perfect then, I didn't need the num-pad but all
the other keys were still there.
Still no idea yet, what programmable keyboards were, so I didn't understand why people would use
smaller than 75% keyboards, thinking they were masochists, restricting themselves in unnecessary ways.
A semester later Keychron released their Q1 series, which I instantly fell in love with. I was just
discovering modding keyboards, including lubing stabilizers and switches, as well as programming
a keyboard. Although I was still uncomfortable with going below the 75% mark.

![Keychron Q1](/assets/keychron_q1.jpg)

Until I started an internship, where one of my colleagues used a 60%. After a while I got intrigued
and inquired about it. Turned out it was not using QMK as it usual with programmable keyboards, but
rather a custom CircuitPython firmware, enabling programming through Python. It was a
[Makerdiary M60](https://makerdiary.com/products/m60-mechanical-keyboard-pcba). I was confronted
with building a keyboard, which I felt like I should avoid. After seeing prices for pre-built ones,
I had a quick change of heart and since QMK felt quite intimidating, the M60 seemed like a nice option.
So up and go I ordered all the parts, nearly forgetting to get a plate, because I read somewhere
that it was not necessary - a load of BS -. Taking its sweet time to arrive and finding the
necessary time, I managed to build at the end of the 3rd semester. I put on some SA profile
keycaps found on Aliexpress and since another colleague was telling me to give tactiles a chance,
which I was against, as mentioned in the beginning, I decided for it and ordered some Gateron
Phantom Browns - spoiler alert, I still use them everyday -, because I had Phantom Reds in the Q1
and I liked that they were pre-lubed.

![M60 self-built keyboard](/assets/m60.jpg)

As you can see in the second image, I got a wooden case, which quickly turned out to have been a
mistake, since it didn't really provide any wrist rest and was just unnecessarily making the
keyboards larger. At least I got some compliments on it at work, but I replaced it by a simple black
plastic case, much handier.
The M60 had been great to me and thanks to my colleague I also discovered the ideas of putting
arrows below `hjkl` - yes I am a [(neo)vim](https://github.com/arminveres/nvim) user - and switching
layers with `f`. No reason to switch, right? ... Right?

## Ergonomic (and Split) Keyboards

Well, while others tend to switch keyboards, use different switches or keycaps, I discovered, there
was a whole community around _ergonomic_ mechanical keyboards, beyond [Microsoft Sculpt](https://www.microsoft.com/en/accessories/products/keyboards/sculpt-ergonomic-desktop?activetab=pivot:overviewtab)
and other older keyboards by Logitech.

A whole new door, or rather rabbit hole, opened. Although I didn't have lots of time to do research,
I haven't found many pre-built keyboards, instead I discovered a DIY niche, where you would order
all the parts and assemble the keyboard yourself, and oh boy, let's not get started about layouts,
that could - will? - be a whole other post. Even though I am interested in embedded systems and
such, I thought that it would be preferable to buy a full package with warranty and such, instead of
soldering everything by yourself, where the component cost could quickly accumulate in the region
of 100+ dollars, or Swiss franks. Therefore I quickly decided on the
[ZSA Moonlander](https://www.zsa.io/moonlander/), which was recommended to me by a friend, who already owned one.

![Moonlander with OEM](/assets/moonlander.jpg)

I was smitten by its design and customizability, the movable tenting legs and thumb cluster. I felt
like the _hackerman_ I always dreamed to be. The default mapping was not very usable for me and I
had to quickly consult the Oryx configurator, which I have to admit is very awesome, in order to
remap the keys. Though I was definitely dissatisfied with the type of switches, Kailh Box Brown, mainly
because the actuation and activation were not at the same force, so the actuation, the tactile bump,
came before the activation, much further down. So again, I swapped them out for Gateron Phantom Browns,
my favorites - although I haven't tried many others -. The keycaps were also too flat for me, so I
played around with different ones, OEMs and KF SA, ordered from AliExpress.
I also noticed that the placement of the thumb cluster was not ideal for my hands, which I would say
are medium sized.

![Sofle v2.1](/assets/sofle.jpg)

Mobility with the Moonlander was not an option for me, though they included a very nice pouch, as
having to set up the height and tenting each time was too much of a hassle so I started looking elsewhere.
I started to consider the DIY boards and the Sofle became the center of my attention.
I was worried about having even less keys, than before but others managed it, why wouldn't I?
So anyway, I ordered it and they arrived a bit late, coming from Australia, and only recently did I
find out, that there are shops from Europe, probably with much lower import taxes.
In any case, we have to circle back to the DIY part. It was such a hurdle, that I didn't manage to
take the time to build it, so it just laid around for a few months. Although once I managed to, i
found myself in pure, eternal bliss. We will simply disregard that recently I basically broke the Sofle
board when I wanted to resolder the microcontrollers for more stability and couldn't use the Sofle
for a few weeks. The thumb cluster here definitely makes more sense and feels more comfortable,
although the two bottom keys on the outer side are basically unused, so in any future shopping
endeavor I could consider one without them.

## Benefits and Drawbacks

As you may have noticed, I prefer the split keyboards. As someone who feels pain in his wrists and
arms after 30 minutes of playing the piano (which I actual haven't played in the past 5 years), let alone
8 hours of typing throughout the day the switch to split keyboards was a pure blessing. The ability
to position the keyboard at shoulder width is immensely helpful. You will (have) read this in many
other posts by other enthusiasts so I won't go too much into it.

Being able to reprogram every aspect of the keyboard is another outspoken gift as well. Most
keyboards I owned were either programmable through QMK, which reaaaly gives you a lot of options,
just go take a look at the [docs](https://docs.qmk.fm/#)! One gripe with it are their missing
support for true Home Mod Rows, on which a great article exists by [precondition](https://precondition.github.io/home-row-mods).

Although I have to say, that buying such a keyboard is one part, the other is not using the mouse as
frequently, as if I rely solely on a mouse for navigation, my wrists get noticeably painful, quite
rapidly. To solve this, another post would make most sense, but having a keyboard centric
environment is the way to go in my opinion a la tiling window manages and keyboard centric editors
such as vim.

On the other hand, mentioned before, the build quality of split keyboards, especially of the
DIY variety is very lacking. I am sure, there are some very nice and robust, alas pricy, builds out
there. Further, for those that appreciate an nice sound and feel, \*_wink r/mechanical keyboards_\*,
the two split keyboards I own are very disappointing, especially the Moonlander, which simply sounds
hollow and plasticky. The Sofle is a tad better in my ears and feel of typing. It is worth
mentioning that there are various mods out there I could do, e.g., putting in foam layers to the
Moonlander PCB and case. But compare to the Keychron Q1, which I recently sold as I wasn't using
it, in any way to sound and feel

I also haven't fully touched on the price point. My grit struggle with the Moonlander is, that it
costs around 400 $ including import taxes, which is a whole damned lot, in any possible way.
For the Sofle I paid around 200 $ with import taxes, but various costs for soldering components
need to be considered as well.

## Conclusion

You have managed to get to the end of my relatively lengthy post, congrats! It means I was able to
inexplicable hold your attention.

Getting into mechanical keyboards was a blessing (on my arms and wrists) and a curse (on my purse).
Combined with the workflow I developed on my workstation and laptop, I cannot imagine another way to
work anymore.

If you are interested in my current QMK configurations take a look at my [qmk configuration](https://github.com/arminveres/qmk_firmware),
which includes the per tandem configurations of the Moonlander and Sofle boards.

What's next in terms of keyboards? Well I recently discovered the [Miryoku layout for 36 key](https://github.com/manna-harbour/miryoku),
so I am interesting in getting a slim profile keyboards, preferably wireless with 36 keys and maybe
get rid of the Moonlander. It could be a Totem or a Corne, I don't know yet!

What's next in terms of posts? Well I could go into my keyboard centric workflow on Linux, or into layouts
and software configuration. I will also try to get more technical in future posts, but no promises!

If you have any preferences, ideas or suggestions, drop me a line at my definitely not shady email address!
