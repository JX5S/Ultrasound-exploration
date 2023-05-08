# Ultrasound-exploration
Whatever I find regarding ultrasound, mostly about postition tracking

# Speakers/transducers
![41mm_transducer_section](https://user-images.githubusercontent.com/40174559/135248272-098e5d96-e3ba-4b72-a1cb-af3f880173c7.jpg)
First I tried 41mm speakers meant against insects, but giving them 8 pulses of 40khz like the HC-SR04 sensor produces more audible sound than ultrasound. They have about 100x the capacitance of the HC-SR04 transducers, yet the volume is lower. Looking at the cross section we can see that the piezo disk is meant to push against the horn, but there is no support on the other side. So either it has been through an incredible engineering process that determined this shape to be perfect for 40kHz ultrasound, or the design is just some stuff cobbled together and since humans can't hear ultrasound, nobody designing it knows how horrible it is. Judging by the performance compared to a transducer from the HC-SR04, I'd say it is more of the latter.

![HC-SR04_transducer_section](https://user-images.githubusercontent.com/40174559/135249409-8094cd9b-6b4e-4c3b-ae85-22594ccb18c8.jpg)

This is a transducer from the HC-SR04 sensor. This one is the receiver, because I need the transmitter intact. Here the piezo disk actually has support. The horn is way smaller, but it seems like actual engineering effort went into the design, so the output is better. The capacitance is way less than the mosquito speaker, so the power consumption should be less as well. The most common transducers of this type are 10mm or 16mm, plastic or metal shell. The HC-SR04 uses 16mm ones in a metal shell.
