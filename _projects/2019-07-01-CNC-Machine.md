---
layout: post
title:  CNC Machine
date:   2019-07-01 00:00:00 -0400
categories: C/C++ Hardware Arduino CNC GRBL
---

<div style="text-align: justify">
My first experience was updating a CNC Machine in a Security Illumination company in Venezuela, this was my innitial approach to the embedded system world and hardware development, in this job I made some hardware adaptations and also some tests in the machine itself before implementing a tested software solution.
</div>

<img alt="Machine review" src="/portfolio/assets/images/cnc/cnc3.jpg" style="width: 30%; display: block; margin: 0 auto;"/>

## The team

<div style="text-align: justify">
In this opportunity, I was an Electronic Engineer Intern, and I had support from a Senior Engineer.
</div>

## Challenges

<div style="text-align: justify">
As this was my first time, I was so insecure about which going to be my tasks and also if I was capable of doing the job. Fortunately, I was in good hands my supervisor always show me the path to make this happen. My tasks in this project were:
</div>

- Update the CNC Machine in a month.
- Update hardware if it is necessary
- Update system firmware if it is necessary.
- Check the machine components.

<img alt="Machine review" src="/portfolio/assets/images/cnc/cnc2.png" style="width: 60%; display: block; margin: 0 auto;"/>

## Tasks

The tasks in this project were more related to hardware, below I share an image where I show how I implemented stop button by hardware and handle the PWM output.

<img alt="Machine review" src="/portfolio/assets/images/cnc/sch1.jpg" style="width: 60%; display: block; margin: 0 auto;"/>
<br/>

<img alt="Machine review" src="/portfolio/assets/images/cnc/sch2.jpg" style="width: 60%; display: block; margin: 0 auto;"/>
This image show how I handle each binary sensor inputs
<br/>

<div style="text-align: justify">
Another task that I did was to test the machine with some C++ test scripts, to be sure about the sensor condition, and also the actuators (Step Motors). In detail my tasks were:
</div>

- Design the new hardware for the control task.
- Design a button for stopping the machine by hardware.
- Implement GRBL in the system.
- Generate PCB examples.
- Document the results.

<img alt="Machine review" src="/portfolio/assets/images/cnc/cnc1.png" style="width: 40%; display: block; margin: 0 auto;"/>
<br/>
<img alt="Machine review" src="/portfolio/assets/images/cnc/candle.png" style="width: 40%; display: block; margin: 0 auto;"/>

## Results

<div style="text-align: justify">
Despite the fact that I wasn't so confident about the results, the results were accepted and I have learned a lot from that. Some of the most important results were:
</div>

- Make PCBs with a trace separation of around 0.5mm.
- Create the PCB for the machine.
- Activate the machine.\

<img alt="Machine review" src="/portfolio/assets/images/cnc/cnc4.png" style="width: 70%; display: block; margin: 0 auto;"/>
<br/>
<img alt="Machine review" src="/portfolio/assets/images/cnc/cnc5.png" style="width: 70%; display: block; margin: 0 auto;"/>
<br/>
<img alt="Machine review" src="/portfolio/assets/images/cnc/cnc6.png" style="width: 70%; display: block; margin: 0 auto;"/>
<br/>
<video controls style="width: 40%; display: block; margin: 0 auto;">
  <source src="/portfolio/assets/videos/cnc/cnc.mp4">
</video>

## Next steps

I watched a lot of software solutions for CNC Machine using GRBL I think the next step for this project could be:

- Integrate a new board with WiFi or Ethernet connection for automate the process or hardware generation in the company, imagine that you could finish your hardware design and just send it to a IP inside the company and the machine start making your PCB.

## Conclusions

Although it was my first experience, I did it excellently and also enjoy being on an engineering project with hardware and software development. After going through this the lessons that I learned were:

- Listening to indications of your partners could save a lot of time.
- The university taught me the basics and It´s so useful in the job.
- It's ok to not completely know about the solution it the beginning, research and knowing how to do things right it's your main tool to solve any problem.

<div style="text-align: justify">
The first approach to a job in any role it's so important, at that moment I didn't know how to do it right but being with a good team and the right people helps a lot, as well as implement the knowledge from the university and also trust yourself, with these keys there isn't any trouble that we couldn't make. If you have any question about this project please send me a email. Thanks for reading!.
</div>
