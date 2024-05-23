# Project: Very Wide Band Amplifier

Authors : Kyle G. Gayliyev, Peter Gail <br>
Date: 25- August - 2023<br>
Course: ECE 6720 - Fundamentals of Analog Integrated Circuit Design, ECE Department, The University of Utah<br>
GitHub IDs: ggayliye <br>
Repo: https://github.com/ggayliye/aicd <br>
Date: 15- December - 2023, 11:59pm (Time of when submission is due/will be ready to be evaluated)<br>
Copyright: ECE 6720, Kyle G. Gayliyev  - This work may not be copied for use in Academic Coursework.

## Overview of the Project
* The goal of this project is to design a very wide-band amplifier, which is widely used in
wireless/RF systems.
* At the heart of this design, there is a differential-input differential-output amplifier,
loaded with 50 fF parasitic capacitance.
* To extend the bandwidth of the amplifier, a passive inductive peaking mechanism can be employed.
* In order to minimize the effect of supply noise on performance of this amplifier, a voltage regulator
will be employed.
* This voltage regulator needs to have a wide-bandwidth and high DC gain in order to
suppress the supply noise.
* A current distribution network can be applied for producing the necessary bias currents for the
regulator circuit and the amplifier.
* Technology: 45nm CMOS, single-well (only n-well available) 
* Simulator: Cadence Virtuoso

![alt text](https://github.com/ggayliye/aicd/blob/main/CadencePics/1.jpg)

					**Fig 1.** A Very Wideband Amplifier  

![alt text](https://github.com/ggayliye/aicd/blob/main/CadencePics/2.jpg)

					**Fig 2.** Regulator 

![alt text](https://github.com/ggayliye/aicd/blob/main/CadencePics/3.jpg)

					**Fig 3.** RF Amplifier 



