---
title: "Pulse oxymeter"
date: 2013-05-29
draft: false
---

6-weeks student project during the 3rd year at ISEN Brest.
The project was done in groups of 2.

The project was divided in 3 parts:
* Electronic: design the card with CAO software, then sold the component on the PCB
* FPGA: Impelment the alogorithm in VHDL to process the IR variation and determine the heart beat.
* Software: The card was plugged to a computer with an FTDI serial interface, the role of the computer was just to compute the SPO2 arte and show the heart rate.

For durther details, the reports and source code can be found below:
* [Report of the electronic part](/img/pulse_oxymeter/Rapport_Electronique.pdf)
* [Report of the FPGA part](/img/pulse_oxymeter/Rapport_VHDL.pdf)
* [Source Code (C & SDL library)](https://github.com/corentin-R/ISEN_oxymetre)



{{< figure src="/img/pulse_oxymeter/oxymeter1.png" caption="Screenshot of the interface" >}}

