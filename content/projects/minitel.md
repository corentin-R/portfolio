---
title: "Minitel reconversion"
date: 2014-04-05
draft: true
---

## Serial Terminal

The first thing we can do with a minitel is to use it as a Linux serial Terminal. It can be done with a small level shifter card to interface the tension of the minitel to the 3V3 needed by the Raspberry Pi.
even if it doesn't handle colors, you can use any Linux commands and play [Dunnet](https://en.wikipedia.org/wiki/Dunnet_(video_game)) or go on the web with [Elinks](https://en.wikipedia.org/wiki/ELinks).

Links to similar projects:
* [What to do of an old Minitel ?](http://www.acbm.com/inedits/recycler-minitel.html)
* [A minitel as linux USB terminal Part 1 : Hardware](http://pila.fr/wordpress/?p=361)
* [A minitel as linux USB terminal Part 2 : Software Raspberry Pi](http://pila.fr/wordpress/?p=425)
* [Terminal Minitel by Furrtek](http://furrtek.free.fr/?a=telinux)
* [Minitel on Raspberry Pi](http://x0r.fr/blog/19)



{{< image src="/img/minitel/minitel1.jpg" position="left"  style="max-width:320px; margin:3%; display:inline-block;" >}}
{{< image src="/img/minitel/minitel3.jpg" position="right" style="max-width:320px; margin:3%; display:inline-block;" >}}



## TV Monitor


The aim of the second project is to transmit black and white video stream to the screen of the minitel.
To do so we can bypass the video chip and directly plug the RGB signal and Vertical sync to the IO of the removed chip.
For example a pertiel connector provides theses signals.					



Schematic of the video component of the minitel ([datasheet of the EF9345](/img/minitel/EF9345.pdf))

{{< image src="/img/minitel/minitel5.gif" position="center ">}}

Under is the freebox crystal decoder plugged on the minitel:

{{< image src="/img/minitel/minitel4.jpg" position="center" >}}



Links to similar projects:
* [Recycle an old Minitel by cfp-radio](http://www.cfp-radio.com/realisations/rea48/minitel-01.html) 
* [Super Minitel Entertainment System by Virtualabs.fr](http://virtualabs.fr/Super-Minitel-Entertainment-System)
* [The Minitel, what to do with this cube!?](http://forum.hardware.fr/hfr/OverclockingCoolingModding/Mod-elec/minitel-cube-sujet_277377_1.htm#t2243569) 


There is another method that need to remove the modem part of the minitel and replace it with a card able to take a composite video signal and using a sync separator (LM1881)


---
## Warning!

**The minitel use a cathodic screen and contains a high voltage block!**
**DO NOT tear down a minitel without being careful and knowing the risks involved.**





