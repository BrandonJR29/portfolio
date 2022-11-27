---
layout: post
title:  Fuzzy Logic Controller For a Ball and Beam System
date:   2020-12-01 00:00:00 -0400
categories: C/C++ MATLAB FreeRTOS Hardware Control Simulink
---

<div style="text-align: justify">
My experience in the University was great, I realized that I would be an Embedded Software Engineer when I was doing my final assessment that was designed an implement a Fuzzy Logic Controller for a Ball and Beam System. This time I used all the knowledge that I got in the classrom such as physics, math, programming, and control theory for finally built a controller with an awesome performance.
</div>

<img alt="Machine review" src="/portfolio/assets/images/fuzzy/bb1.png" style="width: 70%; display: block; margin: 0 auto;"/>

## Challenges

This was my first control system, so I was so excited to give my best on it, the challenges that I found were:

- Designed a Fuzzy Logic Controller in MATLAB with Simulink.
- Designed a Fuzzy Logic Controller with three inputs.
- Designed a PD Controller.
- Optimized the Fuzzy Logic Controller.
- Adjust the signals of the system.
- Create the control hardware.
- Implement the controllers.

## Tasks

<div style="text-align: justify">
In this project I found a variety of taks such as choose the microcontroller, study the system, make the hardware, designed the controllers, and implement the controllers. I couldn't say that it wasn't interesting, believe me if you really love control systems this is the best way to start. As you can see this tasks infers another nested tasks, I can summarize them in the next items:
</div>

- Extract the interested variables of the systems, in this case were the ball position and the beam angle.
- Designed the hardware filters for signals adjustments to the microcontroller.
- Designed and simulate the controllers obtaining a good-performance from them.
- Development of the firmware in C/C++ with FreeRTOS.
- Test the system with different set points.
- Compare the result with the simulation through UART connection with MATLAB generating plots.

### Block diagram of the controll system

![esquema-de-control](/portfolio/assets/images/fuzzy/esquema.png)

### Double loop Controller.

![doble-lazo](/portfolio/assets/images/fuzzy/dobleLazo.png)

### Fuzzy Logic controller with three inputs.

![tres-entradas](/portfolio/assets/images/fuzzy/tresEntradas.png)

## Results


### Simulation results.

| Controller | PD | Fuzzy |
| ------ | ------ | ------- |
| Settling time [s] | 2.3404 | 1.6107 |
| Rise time [s] | 0.6812 | 1.1030 |
| Overshoot [%] | 12.0648 | 0.9372 |

![resultado-simulacion](/portfolio/assets/images/fuzzy/simulacion.png)

### Implementation results.

| Controller | PD | Fuzzy |
| ------ | ------ | ------- |
| Settling time [s] | 2.3618 | 1.9159 |
| Rise time [s] | 0.7576 | 1.4304 |
| Overshoot [%] | 12.5931 | 0 |

![resultado-implementación](/portfolio/assets/images/fuzzy/resultadoFinal.png)

The test videos are in this [link](https://www.youtube.com/watch?v=K9Vu6w_IInE&list=PL-Z_5Zx_UY59NFn0tXmD-8x4Mgz_DTYgh)

## Conclusions

