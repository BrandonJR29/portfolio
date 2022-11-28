---
layout: post
title:  Fuzzy Logic Controller For a Ball and Beam System
date:   2020-12-01 00:00:00 -0400
categories: C/C++ MATLAB FreeRTOS Hardware Control Simulink
---
<div style="text-align: justify">
My experience at the University was great, I realized that I would be an Embedded Software Engineer when I was doing my final assessment that was designed and implemented a Fuzzy Logic Controller for a Ball and Beam System. This time I used all the knowledge that I got in the classroom such as physics, math, programming, and control theory to finally built a controller with excellent performance.

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
In this project, I found a variety of tasks such as choosing the microcontroller, studying the system, making the hardware, and designing and implementing the controllers. I couldn't say that it wasn't interesting, believe me if you really love control systems this is the best way to start. As you can see these tasks infer other ones, I can summarize them in the next items:
</div>

- Extract the interested variables of the systems, in this case, the ball position and the beam angle.
- Designed the hardware filters for signal adjustments to the microcontroller.
- Designed and simulate the controller obtaining good performance from them.
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

## Next steps

I think the next steps for this project could be about implementing more control techniques, here I implemented two, maybe studying one more It could be found one with a better performance.


## Conclusions

<div style="text-align: justify">
Implementing a thorough control system is a big challenge and also obtained relation between the simulation and the real values in the implementation, for me the lessons of this project were:
</div>

- How to integrate the variables in a control system.
- How to implement a control theory strategy in a control system.
- Hardware filters help any controller.
- Optimizing tasks could take time but that time show me that it wasn't easy even for a computer.
- The simulation and the implementation have to go through some conditioning in order to make it similars.

<div style="text-align: justify">
I feel so good due to I have implemented these controllers they show me bunch of things that I wouldn't forget.  If you are reading this because you love control theory I invite you to read the document of this project on my Github account and also check the code, just remember I did it when I was a junior developer, now I would change a lot of things, starting for the Fuzzy Logic library that use a lot the heap memory. Thanks for reading!
</div>

