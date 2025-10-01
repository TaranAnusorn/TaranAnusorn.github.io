---
layout: default
title: Microwave Engineering
parent: Academic Notes
nav_order: 2
permalink: notes/Microwave
---

# Microwave Engineering
{: .no_toc}
<img src="\pages\04_Notes\fig\MicrowaveCover.jpg" alt="Cover photo"/>


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## What is Microwave Engineering?

<img src="\pages\04_Notes\fig\EMspectrum.png" alt="The electromagnetic spectrum"/>
*The electromagnetic spectrum.*
{: .fs-3 .fw-300 }

The fields of **radio frequency** (RF) and **microwave engineering** generally cover the behavior of alternating current signals with frequencies in the range of 100 MHz to 1000 GHz, which are equivalent to 0.3 mm to 3 m in wavelength.
RF frequencies range from very high frequency (VHF: 30-300 MHz) to ultra high frequency (UHF: 300-3000 MHz), while the
term microwave is typically used for frequencies between 3 and 300 GHz. Signals with wavelengths on the
order of millimeters may be referred to as **millimeter waves**.

---

## High Frequency Characteristics
<img src="\pages\04_Notes\fig\The_Atacama_Compact_Array.jpg" alt="The Atacama Compact Array"/>
*The Atacama Compact Array (ACA) at the ALMA site, Chile.*
{: .fs-3 .fw-300 }

At low frequencies, an approximation of Maxwell's equations called circuit theory is well suited. However, it fails to describe the behavior of the systems at high frequencies, where the wavelengths of the signals are comparable to the actual circuit size. Consequentially, one must often work with Maxwell's equations and their solutions when dealing with RF and microwave systems. The mathematical difficulties of the equations and the complex nature of the devices at high frequencies, of course, make the design and analysis in this field seem challenging. Fortunately, the same aspects also provide unique opportunities for a variety of applications, including wireless communications networking and systems, radars, remote sensing, radio astronomy, microwave heating, medical diagnostics and treatment, securities, and even chemical studies.

<img src="\pages\04_Notes\fig\BigBangNoise.jpg" alt="Microwave Astronomical Maps Comparison"/>
*Maps of the cosmic microwave background radiation (CMBR), showing the improved resolution which has been achieved with better microwave radio telescopes.*
{: .fs-3 .fw-300 }

Here are some useful practical considerations for designing RF and microwave systems:

- At higher frequencies, more _bandwidth_ (and, of course, data rate) can be achieved.

- At higher frequencies, smaller components can be realized. This means more antennas can be packed in a given compartment, which increases the _antenna gain_ and opens the door for various _multiple-antenna techniques_.

- High-frequency signals travel in the line of sight and are not bent by the ionosphere as are lower-frequency signals. Therefore, satellite and terrestrial communication links with high capacities are possible.

- The _effective reflection area_, a.k.a. _radar cross section_, of a radar tarket is usually proportional to its electrical size. Moreover, the image resolution is much finer when using a shorter-wavelength signal. These facts make microwave frequencies attractive for imaging and sensing applications.

- Various molecular and atomic resonances occur at microwave frequencies, inspiring profound applications ranging from the basic sciences to medicine and securities.

---
## Components in RF/Microwave Systems

<img src="\pages\04_Notes\fig\GenericRFchain.png" alt="A generic RF signal chain"/>
*A generic RF signal chain.*
{: .fs-3 .fw-300 }

Before going through the principles of microwave engineering. Let's first take a look at an overview of the systems and their key components.
Since the majority of today’s applications of RF and microwave technology are to *transceive* energy *wirelessly*, we shall determine a transceiver system as our representative of the microwave systems.

Speech, texts, images, or any other information can be converted into electrical *baseband* signals by a **transducer**. These baseband signals can be processed using various signal-processing techniques and coding schemes. However, since signals at higher frequencies (RF/microwave) can radiate more efficiently, the baseband signals are *upconverted* to more transmission-preferable *passband* signals. The modulation is usually performed with the use of a **mixer** and an **oscillator**. To restrict signals within the band, unwanted frequencies can be filtered out by a **filter**. 

When waves propagate, they unavoidably face *propagation losses* and *noise*. To make signals powerful enough, a **power amplifier** comes into play. 
For wireless systems, RF signals radiate to the surroundings in the presence of an **antenna**. Signals are attenuated and distorted during transmission. When they reach a receiver, they might have fainted, and a **low-noise amplifier** (LNA) recovers their strength while presenting as little noise as possible. The amplified RF signals then pass through the reversal of the transmitting process: *downconversion*, *filtering*, and *data reconstruction*.

Besides the mentioned components, there are many other important microwave components that are frequently used as well, such as **power dividers**, **directional  couplers**, **isolators**, and **circulators**.

The components in microwave systems can be classified into two classes: **passive** and **active**. The passive components are those that require no power supplies for their operation, and the active components are vice versa.

*See [this](https://www.analog.com/en/resources/analog-dialogue/articles/rf-signal-chain-discourse-part-2-essential-building-blocks.html#author){: target="__blank"} and [this](https://www.pasternack.com/pages/rf-microwave-and-millimeter-wave-products/block-diagrams.html){: target="__blank"} for some RF system block diagrams.*

---
## Underlying Physics
### Components at high frequencies
_This section is under construction._

### Nature of Wave Propagation
_This section is under construction._

### Transmission Line Theory
_This section is under construction._

---
## Mathematical "Magic" Tools
### The Smith Chart

### Network Analysis

### 
