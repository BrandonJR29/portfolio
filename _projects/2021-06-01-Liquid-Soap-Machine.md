---
layout: post
title:  Liquid Soap Vending Machine
date:   2022-06-01 00:00:00 -0400
categories: C/C++ Python IoT FreeRTOS Websocket HTTP OOP Javascript
---

<div style="text-align: justify">
After some experience developing projects such as IoT products, embedded systems, and control systems under the supervision of a senior engineer and with the support of others Embedded Software Engineers. One opportunity showed up and at that time I was on my own, therefore I must design the embedded software solution from the beginning, the test cases, developing a good-performance final product, and achieve all the client requirements. The Liquid Soap Vending Machine was one of the best experiences I've ever had, working with people that I didn't know and being in charge of one of the most important parts of the project.
</div>
<br/>

## The team

<div style="text-align: justify">
In this project, I worked as a contractor with the Embedded Software Engineer role where the client established the machine requirements and our communication with them was by the product owner. The group was conformed of a Fullstack Engineer, Mechanical Engineer, Hardware Designer, Scrum Master, Product Owner, and myself. The strategy was developed by the product owner and the scrum master: a meeting via video call twice a week for planning, watching the results, and determining the next steps, and once a week we made tests in the machine with the hardware. Furthermore, we use Jira Software as a task scheduler and also measure the development of the project.
</div>

<img alt="Team" src="/portfolio/assets/lsvm_team.jpg" style="width: 65%; display: block; margin: 0 auto;"/>
<br/>

## Challenges

According to the client's requirements we found the below challenges:

- Design the Liquid Soap Vending Machine.
- Being in charge of the Embedded Software development.
- Avoid activation from foreign devices.
- The dispensing machine error must be under 3%.

<br/>

## Tasks

<div style="text-align: justify">
The tasks that I covered in this project were not only related to Embedded Software development but also contribute to the decisions about the machine structure and which sensor and actuators (including the pump) we should choose. This gives me the expertise of how to get involved in different areas by giving my knowledge about embedded systems in the final product.
</div>
<br/>

<img alt="Machine review" src="/portfolio/assets/lsvm_team2.jpg" style="width: 60%; display: block; margin: 0 auto;"/>

<div style="text-align: justify">
As my role demanded, I defined the hardware requirements of the systems, as well as the software development that would be working in it. I developed this using C/C++ using object-oriented programming implementing the Observable and State design pattern. About the software architecture, I designed the system to work through Events taking advantage of the real-time operating system that I used, FreeRTOS with Events Groups. Furthermore, as I said at the beginning I designed the test cases of the hardware, mocking some of the sensors or actuators due to I couldn't make tests with real hardware every time (The machine couldn't be at my home), and I did this using Python with HTTP client scripts connecting to the Embedded Web Server and sending a request and mocking the output of the system. By doing this I was sure that the logic of the system was ok. Something that was really important in this system was to develop the control for the dispensing of liquid soap. For this, I estimated the plant equation and designed the PI controller for the dispensing task according to it.
</div>

<img alt="Hardware Prototype" src="/portfolio/assets/lsvm_prototype.png" style="width: 45%; display: block; margin: 0 auto;"/>

<div style="text-align: justify">
So, the main activities that I did in this project were:
</div>

- Development of the firmware in C/C++ with FreeRTOS.
- Control the dispensing soap task.
- Designed the system test. I did it with Python HTTP clients.
- Define the hardware requirement such as the microcontroller, sensors, and actuators.
- Established communication between the embedded system with another server.
- Send data in real-time through Websocket.
- Design a Demo of the embedded system.
- Contribute to the design of the machine.
- Generate the system documentation, I used Doxygen to automate this task through code comments.

Below you can watch a demo that I did for this project where I test the sensor, actuators, and app logic. I used my abilities in web development with javascript for creating this interface and embedded the files in the microcontroller as an Embedded Web server.

<video controls style="width: 40%; display: block; margin: 0 auto;">
  <source src="/portfolio/assets/lsvm_video2.mp4">
</video>

<br/>

## Results

<div style="text-align: justify">
Although the team went through bugs, connection failures, etc. The team successfully developed the Liquid Soap Machine, watching these results:
</div>

- Complete the first version of the Liquid Soap Machine.
- The final error of the dispensing task was 1%, achieving the client requirement of under 3%.
- Save the client data in a robust Database on another local server.
- Show the dispensing process in real time to the users.
- Detect common errors in the machine such as when a user releases the soap container while the machine is dispensing.


<video controls style="width: 40%; display: block; margin: 0 auto;">
  <source src="/portfolio/assets/lsvm_video1.mp4">
</video>

<br/>

## Next steps

<div style="text-align: justify">
Despite the fact that we satisfied the client's requirements for this first version, we think there are some features that could transform this machine, those are:
</div>

- Integrate OTA for updating the firmware remotely, imagine if we have more than one machine and we have found a bug or something that makes the system better would be tedious to go to each location in order to update the code.
- As a consequence of the previous sentence, the system must be connected to the internet, in this first version the embedded system is connected to a local server without an internet connection, then if this system is connected to the internet or maybe is in the cloud would upgrade the performance of the solution due to we could create kind of web interface where we show the clients information and generate some statistics of vending machines.
- Nowadays, AI solutions are becoming popular in any technological solution and we think this is no different. In the next iteration, we would like to integrate a camera in order to detect common users, as well as detect if anybody is in front of the vending machine. Imagine that a common user goes to the place to buy liquid soap in our machine for a second chance and the machine could say hi with his/her name, it would be awesome, wouldn't it?
- Another advantage of using a camera with an AI solution is for authenticating user bills, just imagine if the user only needs to show the bill and the system process the control task, of course, the system must detect if the bill is genuine too.


<br/>

## Conclusions

This project was full of lessons some of which were:

- How to explain technical tasks to people who don't know something about this, using diagrams and looking for ways to explain some technology with daily life examples.
- Another good lesson was how to handle responsibility and my answer to that is being honest with your team, despite the fact that I was alone in my area I felt that I wasn't alone, talking about my concerns about the embedded software development tasks the team helps me to implement them successfully.
- Contribute to the creative process of the final product, also show that it's important to develop that part of the project too, how this could interact with people, which is the best way, etc.
- Watching my partner's job, give me more knowledge than I had when I started the project, believe me watching other people's jobs could teach you something.

<div style="text-align: justify">
Finally, I think for these reasons I feel happy and satisfied about the achievement of this project, how I made it as a leader of the Embedded Software development, as well as contributing to the team. If you have any doubts about this project please don't hesitate to ask me by sending me an email, I would be happy to answer your questions thanks for reading this. 
</div>



