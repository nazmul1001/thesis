# thesis
## Machine Learning on DIN rails
Universität Rostock
Type of work: Master's or Bachelor's thesis (then with reduced scope),
project work
Background:
We are researching in several projects for the safety of field buses. Often,
machine learning (ML) methods are applied in order to be able to make
statements about the safety of the network. This includes:
Investigation of the signal course on the physical layer and detection
of manipulations of devices and media by means of various features.
Estimation of the risk based on information about the topology of
field bus networks and access possibilities of the attacker.
Intrusion detection systems and firewalling on field buses (Data
Driven Security).
In the training phase, most ML algorithms are very performance-hungry.
Therefore, we have usually carried out the training phase on an
appropriately powerful system. As a rule, we have to deal with locations
that are difficult to reach. We also cannot connect any number of
resources via internet or use any number of powerful computers locally.
This means that up to now we have had to accept cutbacks in the
execution of ML procedures due to the restrictions. The limitations relate
to the amount of data processed per time, the amount and selection of
the features examined and the complexity of the model. So far we have
gained experience with TinyML. Here, a neural network is taught on an
external system using TensorFlow Lite and then executed on microcontrollers.
Meanwhile several hardware accelerators for ML are available. TheseMachine Learning on DIN rails - IuK - Universität Rostock 15.07.22, 23:16
https://iuk.uni-rostock.de/en/teaching-study/teaching/machine-learning-on-din-rails/ Seite 2 von 3
include Google Coral and NVIDIA Jetson nano. Within the scope of this
work, the two systems and, at the request of the processor, possibly
further hardware accelerators for the above-mentioned purposes are to
be evaluated.
Task description:
High-dimensional data are to be analysed with the help of ML methods for
certain patterns typical for attacks. Prototypical implementations for
conventional CPUs are available. Within the scope of the thesis it shall be
investigated which methods are especially suitable for hardware
acceleration, which performance gain occurs for the specific problems
and specific algorithms and which pitfalls have to be considered.
The following questions shall be answered:
Which algorithms and features can be used?
Which processes are particularly affected by hardware acceleration?
What gain can be expected from this in terms of risk analysis?
Is ML possible in the field (on the DIN rail)?
Possible work steps:
Consideration of the application area (safety in field buses) and the
recorded data
consideration of possible evaluation algorithms and procedures
Basics machine learning
Known quality parameters for evaluating the procedures
Consideration of the hardware and procedures for acceleration
Design of a prototype for at least one process
Implementation of a prototype
Testing and evaluation based on quality parameters
The exact definition of the topic is done in coordination with the
supervisor.Machine Learning on DIN rails - IuK - Universität Rostock 15.07.22, 23:16
https://iuk.uni-rostock.de/en/teaching-study/teaching/machine-learning-on-din-rails/ Seite 3 von 3
Literature and resources:
Peters, M., Goltz, J., Wiedenmann, S., & Mundt, T. (2019, July). Using
Machine Learning to Find Anomalies in Field Bus Network Traffic.
In International Conference on Security, Privacy and Anonymity in
Computation, Communication and Storage (pp. 336-353). Springer,
Cham.
Warden, P., & Situnayake, D. (2020). Tinyml: Machine learning with
tensorflow lite on arduino and ultra-low-power microcontrollers.
O'Reilly Media, Incorporated.
Descriptions of the above hardware.
Supervisor: Dr. Thomas Mundt (thomas.mundt@uni-rostock.de)
Requirements: Ability to program ML models. See instructions for Google
Coral, NVIDIA Jetson and TensorFlow Lite in general.
