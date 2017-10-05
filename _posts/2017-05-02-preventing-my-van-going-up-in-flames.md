---
layout: post
title:  "Preventing my van going up in flames"
date:   2017-05-02
header-img: assets/images/IMG_7612.JPG
---

It has been raining a lot for the last weeks in Berlin. I urged installing the [solar panels]({% post_url 2017-03-06-ordering-my-solar-system %}) so I drove around to find a bridge that offers a dry place to work on the roof. While driving in the rain I realized that the wipers moved very slowly.

I couldn't find any issues with the wipers or the motor. However I observed that the blinkers also flashed a bit weakly. While diving deeper into the issue I realized that several electric devices operated weakly:

- the headlights
- the blinkers
- the wipers
- the fan for the heating
- several lamps on the instrument panel

Where to start looking for the root cause of all these problems? :thinking: With the help of the wire diagram I tracked the issue down to the fuse box.

![Wire diagram for a Mercedes-Benz 207D/209D](/assets/images/IMG_7618.JPG)

All fuses seemed intact however some connectors looked really bad:

![Fuse box in bad condition](/assets/images/IMG_7117.JPG)

Some cables even looked scorched:

![Fuse box in bad condition](/assets/images/IMG_7118.JPG)

For some of these connectors I measured a resistance above 200 Ω. :scream: The connectors were held together by bolts that got loose over time. These loose connections caused very bad conductivity, resulting in a lot of heat which further led to corrosion. A vicious circle!

Ignoring this issue might have resulted in my van going up in flames. :fire:

All shops I checked were out of stock (part number *A0015450001*) so I sanded all the connectors,

![Sanding the connectors](/assets/images/IMG_7599.JPG)

replaced the loose bolts with proper screws and linked the connectors with a thick copper sheet.

![Screws replacing the loose bolts](/assets/images/IMG_7612.JPG)

Before installing the fuse box back into the van I measured the resistance of every single fuse connection:

![Repaired fuse box](/assets/images/IMG_7614.JPG)

All connections below 1 Ω. Yay, another fixed issue! :heavy_check_mark:

Installing the [solar panels]({% post_url 2017-03-06-ordering-my-solar-system %}) will hopefully the next project! :pray:
