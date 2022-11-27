---
layout: post
title:  IoT Cold Chain
date:   2021-03-01 00:00:00 -0400
categories: Dart Flutter IoT HTTP Cold-Chain RaspberryPi Datalogger
---

<div style="text-align: justify">
Working as an Embedded Software Engineer sometimes involves integrating an interface for establishing interaction with the users, it could be a display, buttons, even a web interface or a Mobile app, this time I was involved in a cold chain project where I have to send data to a server in order to create records of a temperature product, demonstrating to a client that the product is in good conditions according to temperature measures registered in the system.
</div>

## The team

<div style="text-align: justify">
In this project, I was with a UI designer and another Embedded Software Engineer who also develop this app. The solution consisted of a mobile app with Android and a Raspberry Pi for extracting data from temperature dataloggers through USB.
</div>

## Challenges

<div style="text-align: justify">
I've never tried to develop a mobile app but working in a startup gives me the opportunity to work with a variety of technologies and also learn a lot. In this project the challenges were:
</div>

- Create a Mobile App.
- Connect the app with a Datalogger.
- Extract the data.
- Create an interface satisfying the designer's requirements.
- Successfully send the data to the server.

## Tasks

<div style="text-align: justify">
The App was focused to do two things: registering dataloggers through bar code, extracting the data from the dataloggers, and sending the data to the server. The first iteration of this development was with a barcode scanner, USB Temperature Dataloggers, and a Rasberry Pi for extracting the data and communicating with the app through Bluetooth. Knowing this my tasks in this project were:
</div>

- Develop a Mobile App using Flutter.
- Create interfaces satisfying the UI designer's requirements.
- Connect the App with the Raspberry Pi through Bluetooth.
- Parse the data from a pdf file, just get the temperature measurements and times.
- Extract the barcode of the Datalogger.
- Send the data to the server.
- Change the barcode scanner to use the camera instead of the scanner in order to reduce the cost of the solution.

<img alt="Machine review" src="/portfolio/assets/estelio_cold_chain.png" style="width: 100%; display: block; margin: 0 auto;"/>
<br>
<img alt="Machine review" src="/portfolio/assets/estelio_cold_chain_photo.jpg" style="width: 40%; display: block; margin: 0 auto;"/>


## Results

<div style="text-align: justify">
The project accomplished all the requirements since extracting the barcode and sending the data to the server. Some of the most important features were:
</div>

- A thorough Mobile App result.
- Achieve all the requirements.
- Parse the data and encapsulate the data successfully
- Change the barcode scanner to use the camera.


<video controls style="width: 50%; display: block; margin: 0 auto;">
  <source src="/portfolio/assets/estelio_cold_chain.mp4">
</video>


## Next steps

<div style="text-align: justify">
The necessity of two devices for this project could inflate the client budget, for that we watched these next features:
</div>

- Use a Datalogger with a Bluetooth connection, with this we could remove the Raspberry Pi from the process.
- Create a driver for the mobile app to handle USB, in this case, the datalogger USB version was too old for that we added the Raspberry Pi.

## Conclusions

<div style="text-align: justify">
Watching this project finished I only could think of the challenges that the team beat in order to achieve the final goal, a mobile app with good performance, the lessons that I learned here were:
</div>

- Starting with a new programming language could take time but it is not impossible having good support and a good community behind.
- Being in a different role could open your mind and think in different ways, this also lets you be more creative than you were.
- Knowing new technologies that you already use in your daily life give you a better background when you have to integrate that into another project.

<div style="text-align: justify">
With this I feel satisfied with the first version of the mobile, maybe you could think if it is in the Google play store now, unfortunately, this was a demo and after that, I move to another opportunity in a different job, the last thing that I know about the app was that it has changed a lot. I only could say thanks for having this experience and of course, if you have any questions about this don't hesitate an email me, and I will answer you back ASAP.
</div>

