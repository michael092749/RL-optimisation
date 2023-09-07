# RL-optmisation

This project aims to optimise task offloading in decisions using reinforcement learning.

With the advent of 5G, and general development in wireless communication technologies, the growth
of smart communication devices such as mobile devices and Internet-of-Things (IoT) has increased.
Consequently, the amount of data collected and expected to be processed and transported by these
devices grow, putting a huge burden on the wireless communication infrastructure with limited
processor, bandwidth, and battery power, limiting the effective use of these devices in computationalintensive
and delay sensitive communication and data processing technology. In order to circumvent
these obvious challenges and ensure better quality of service (QoS) delivery, mobile edge computing
or multi-user edge computing (MEC) has been proposed. MEC therefore, is a communication
technology that prescribes task sharing between a device and an edge server. The device can offload
the computationally intensive or latency-critical task to the nearby MEC server so as to save energy
and extend battery life. Typically devices are battery powered and battery energy rely on some form
of energy harvesting, typically harvesting from Radio Frequency (RF) transmissions, for battery
recharge.

The challenge therefore is in obtaining optimal use of the RF harvested energy to maintain the tradeoff
between users’ energy consumption and system latency. This project focuses on the design of a
task offloading scheme for energy harvesting internet-of-things devices in mobile edge computing. A
number of methods have been developed in the literature, some based on algebraic approaches and
other based on Machine Learning (ML) approaches.

This code developes a reinforcemnt learning algorithm that optimises the use of battery power whilst minimising the transmission delay.
Specifically, it utilises a Deep Deterministic Policy Gradient approach that allows for the modelling of continuous action spaces.
