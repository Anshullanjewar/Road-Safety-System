<a name="readme-top"></a>

<!-- PROJECT SHIELDS -->

[![LinkedIn][linkedin-shield]][linkedin-url]


<br />
<div align="center">

  <h3 align="center">Road Safety System</h3>

  <p align="center">
	This road safety system is integrated with features like drowsiness detection, over speeding, drunk and driving, and accident detection system!!    <br />
    <a href="https://github.com/Anshullanjewar/Road-Safety-System"><strong>Explore the docs »</strong></a>
    <br />
    <br />
  </p>
</div>


<!-- ABOUT THE PROJECT -->
## About The Project

<p align="center" float="left">
<table>
  <tr>
    <td><img src="https://github.com/Anshullanjewar/Road-Safety-System/blob/main/Screenshot%20(191).png" width="1080"></td>
  </tr>
 </table>

The usage of autos has significantly increased in the modern world. Since there are more people driving, there is more traffic, which has led to an increase in traffic accidents. Due to a lack of timely preventative and safety facilities, this damages the property and results in human life loss. Although complete accident avoidance is impossible, consequences can at least be lessened. This embedded system can take the necessary precautions to avoid accidents, and it does so. Because the position and a link to a Google Map were supplied to their smart devices with mobile network accessibility, the ambulance service and the police station can quickly locate the area. Eye blink sensors, temperature sensors, alcohol sensors, accelerometers, GPS modules, GSM modules, motors, buzzers, leds, and other components make up the system. These components are all connected to the core microcontroller unit. By selecting a certain time restriction, we will employ an eye blink sensor to detect sleep so that we may alert the driver if necessary. The temperature sensor aids in detecting engine heat so that we can alert the driver if the engine is running hotter than usual. Alcohol sensors assist us in determining whether or not a motorist is intoxicated. The car warns the driver if they are too intoxicated and the motor shuts off. When an accident occurs, the accelerometer sends a signal to the microcontroller so it may continue operating. The GPS module gives us real-time access to the location, speed, time, and date of the specific spot where the car is. In the event of an accident, the GSM module is used to notify the accident's position, which we learn via the GPS, to the police and ambulance service. After a minor collision, everything can be fine, in which case the driver can update the ambulance service and police station.


 
### Hardware Integrated

* Arduino UNO
* Alcohol Sensor(MQ-3)
* Accelerometer(ADXL335)
* Eye Blink Sensor
* GPS (Global Positioning System) Module
* LED Lights
* 16*2 LCD Dispaly
* Buzzer
  
<table>
  <tr>
    <td><img src="https://github.com/Anshullanjewar/Road-Safety-System/blob/main/Road%20Safety.png" width="1080" height="500"></td>
  </tr>
 </table>
 
### WORKING 
Algorithm for the working of the system:

* First of all, the system is powered with the proper amount of power supply.
* After the system is on, the alcohol sensor detects if the driver is drunk or not. If
  he/she is over drunk the system provides warning and the engine of the vehicle
  stop functioning.
* If no alcohol is detected then the vehicle starts properly or does not stop running.
* Eye blink sensors detect whether the driver is drowsy or not. If the driver is
  asleep the system warns him with an alarm and red light alert.
* Continuously Temperature sensor helps us in detecting the heat of the engine
  and if the engine is overheated then that of a normal condition, driver gets red
  light alert else keeps moving.
* If accident occurs, accelerometer detects the occurrence of accident and sends
  signal to the microcontroller for further functioning.
* GPS module finds the location and GSM module sends message with latitude,
  longitude and link of google map to emergency numbers of ambulance and
  police.
* Once the system is on, it continuously checks all the sensors by the help of
  microcontroller (Arduino Uno) in order to perform all the prevention, detection
  and reporting works.



### CONCLUSION 

In this 21’s century, with the continuous advancement in science and technology, more
emphasis is given for vehicle safety. With the increase in number of vehicle, the number
Road accidents are also increasing day by day, so it is our duty to control it. Mostly the
accident takes place because of drunk drivers, drowsiness while driving and over
heating of engine causing fire. Implementation of this project will help to decrease the
accident caused because of the above reason. The system is automatic, low cost and power
efficient which makes it easy to install in vehicles. Unfortunately, if accident happens to
take place, the system detects it and with the help of GPS exact location can be pointed
and informed the emergency unit using the GSM module. This helps to save many lives by
informing the rescuing agent in time.
Over all, this system is very affordable, targets common people and easily implemented
in all types of vehicles.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Get Started!

To learn more about the project, explore the codebase, or contribute, visit the GitHub repository:

* **Project Link:** https://github.com/Anshullanjewar/Road-Safety-System



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTACT -->
## Contact

Name - [Anshul Lanjewar](https://www.linkedin.com/in/anshul-lanjewar) - anshullanjewar12@gmail.com

Project Link: [https://github.com/Anshullanjewar/Road-Safety-System](https://github.com/Anshullanjewar/Road-Safety-System)






<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[Portfolio-shield]: https://img.shields.io/github/contributors/Anshullanjewar/Best-README-Template.svg?style=for-the-badge
[portfolio-url]: https://anshullanjewar.github.io/
[stars-shield]: https://img.shields.io/github/stars/Anshullanjewar/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/Anshullanjewar/Guided_App/issues
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/Anshullanjewar/Guided_App/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]:https://github.com/Anshullanjewar/Guided_App/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/anshul-lanjewar
[Java_url]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[firebase_url]: https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34
[android_url]: https://img.shields.io/badge/android%20studio-346ac1?style=for-the-badge&logo=android%20studio&logoColor=white
