---
layout: post
title:  "Ordering my solar system"
date:   2017-03-06
header-img: assets/images/background_shot_of_blue_sky_with_white_cloud.jpg
---

Today I ordered all the components for my future solar system. :tada:

As I'll be working from my van I want to be 100% autonomous for several days even on cloudy and rainy days.

## Estimating the required energy

To get a rough idea about the required capacity I measured the power consumption of all devices that will be operated in my van:

| Device                | Power (W) | Usage per day (h) | Energy (Wh) |
|-----------------------|-----------|-------------------|-------------|
| Laptop                | 30        | 8                 | 270         |
| Router                | 2.5       | 12                | 30          |
| Radio                 | 10        | 3                 | 30          |
| Lights                | 5.2       | 3                 | 15.6        |
| Water pumps           | 10        | 0.25              | 2.5         |
| Smartphone (charging) | 5         | 2                 | 10          |
| **Sub-total**         |           |                   | **358.1**   |
| Fridge (optional)     | 110       | 14                | 1540        |
| **Total**             |           |                   | **1898.1**  |

Based on my estimate I need at least 360Wh on a regular working day. 360Wh roughly correlates with 360Wh / 12.8V ≈ 28Ah.

The built-in absorption refrigerator is very old and eats a lot of power. I might replace it with a more efficient compressor fridge in the future but in the meanwhile I'll turn it off while I don't need it. Fruits, vegetables, bread, pasta and a lot of other food can be stored for a couple of days without a fridge. With the help of cooling elements I should be able to run the fridge during the day and turn it off at night. Operating the fridge for 14 instead of 24 hours seems reasonable.

Considering all devices including the fridge I need about 1900Wh a day which roughly correlates with 1900Wh / 12.8V ≈ 148Ah.

## Picking the right battery

I wanted to be able to sustain at least for one day. Considering a little buffer I aimed for a battery setup that could deliver 200Ah without charging the battery at all.

For camper vans you can generally choose between three main types of batteries: [lead-acid](https://en.wikipedia.org/wiki/Lead%E2%80%93acid_battery), [gel/AGM](https://en.wikipedia.org/wiki/VRLA_battery) or [lithium-ion](https://en.wikipedia.org/wiki/Lithium-ion_battery). Lithium batteries noticeably outperform gel or lead-acid batteries. But the better performance comes at a price: lithium batteries cost about 2.5 times more than gel batteries with the same Ah specification. However lithium batteries last longer, are way more efficient, require less space and are lighter.

Gel and lead-acid batteries can't be fully discharged without causing damage. They should also get fully charged on a regular basis. Especially when charged by solar energy that isn't constantly available this might be tricky. If you want to be able to efficiently use 200Ah without charging the battery, you probably have to pick a gel-based setup that delivers at least 300Ah or even 400Ah. Such a setup would result in about 130kg and 0.05m² of space whereas a 200Ah lithium battery only weighs 42kg and requires about 0.03m².

Considering that I plan to use the battery for several years I picked a high-quality [LiFePO4 (Lithium-Iron-Phosphate) battery](https://www.victronenergy.com/upload/documents/Datasheet-12,8-Volt-lithium-iron-phosphate-batteries-EN.pdf) from Victron Energy with 200Ah. With the fridge turned on this battery would allow me to sustain at least for a full day. With the fridge turned off I should be able to work for a bit more than five days without charging the battery at all.

The battery consists of four 3.2V cells that are connected in series and deliver 12.8V in total. These cells do not auto-balance at the end of the charge cycle. To guarantee a long lifetime of the whole battery I also ordered the [battery management system (BMS) 12/200](https://www.victronenergy.com/upload/documents/Datasheet-BMS-12-200-EN.pdf) which offers several connectors to efficiently charge and protect the battery.

## Selecting the best matching solar panels for the given space

Picking the right solar panels was not easy, because a lot of parameters had to be considered: the available space, the angle of the solar panels (fixed or flexible) and of course the hours of daily sunshine. Especially the latter is hard to specify because it further depends on the location (north vs. south), the season (winter vs. summer) and of course the daily weather (cloudy vs. sunny). Based on climate statistics and reports I found online, I assumed that a solar panel with 100Wp would deliver about 500Wh a day from spring to autumn. So my overall energy consumption of 1900Wh correlates with a 1900 / 5 = 380Wp solar panel setup.

The rack and the two windows in the roof of my van forced me to use the space on top of the alcove. I picked three mono-crystalline panels that would cover as much space as possible: two [100Wp panels](https://www.offgridtec.com/generatoren/solarmodule/12v-24v-solarmodule/offgridtecr-100w-mono-solarpanel-12v.html) (540mm x 1200mm) and one [150Wp panel](https://www.offgridtec.com/offgridtecr-150w-mono-12v-solarpanel.html) (1340mm x 67mm).

After reading through several [tests](https://www.amumot.de/solar-laderegler-12v-mppt/) I picked the [SmartSolar MPPT 100/30 solar charge controller](https://www.victronenergy.com/solar-charge-controllers/smartsolar-100-30-100-50) from Victron Energy which seemed to be one of the most efficient controllers currently available.

## Operating 230V AC devices

To operate and charge devices that run with 230V AC like my cordless impact wrench, I also ordered a [voltage converter](https://www.amazon.de/gp/product/B00FMUVRKK/) that provides 1500W of continuous and up to 3000W peak power for start-up currents.

I'm really looking forward to getting all the parts delivered and install the solar system in my van! :sunny: :electric_plug:
