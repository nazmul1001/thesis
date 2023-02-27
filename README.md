# <p style="text-align: center;">Thesis</p>
## Machine Learning on DIN rails

### Background:
We are researching in several projects for the safety of field buses. Often, machine learning (ML) methods are applied in order to be able to make
statements about the safety of the network. This includes:

<ul>
	<li>Investigation of the signal course on the physical layer and detection of manipulations of devices and media by means of various features.</li>
	<li>Estimation of the risk based on information about the topology of field bus networks and access possibilities of the attacker.</li>
	<li>Intrusion detection systems and firewalling on field buses (Data Driven Security).</li>
</ul>

In the training phase, most ML algorithms are very performance-hungry. Therefore, we have usually carried out the training phase on an appropriately powerful system. As a rule, we have to deal with locations that are difficult to reach. We also cannot connect any number of resources via internet or use any number of powerful computers locally.
This means that up to now we have had to accept cutbacks in the execution of ML procedures due to the restrictions. The limitations relate to the amount of data processed per time, the amount and selection of the features examined and the complexity of the model. So far we have gained experience with TinyML. Here, a neural network is taught on an external system using TensorFlow Lite and then executed on microcontrollers.
Meanwhile several hardware accelerators for ML are available. TheseMachine Learning on DIN rails 
include Google Coral and NVIDIA Jetson nano. Within the scope of this work, the two systems and,  at the request of the processor, possibly further hardware accelerators for the above-mentioned purposes are to be evaluated.<br>

### Task description:
High-dimensional data are to be analysed with the help of ML methods for certain patterns typical for attacks. Prototypical implementations for conventional CPUs are available. Within the scope of the thesis it shall be investigated which methods are especially suitable for hardware acceleration, which performance gain occurs for the specific problems and specific algorithms and which pitfalls have to be considered.<br>

The following questions shall be answered:
<br>
<ul>
	<li>Which algorithms and features can be used?</li>
	<li>Which processes are particularly affected by hardware acceleration?</li>
	<li>What gain can be expected from this in terms of risk analysis?</li>
	<li>Is ML possible in the field (on the DIN rail)?</li>
</ul>


**Possible work steps:**

<ul>
	<li>Consideration of the application area (safety in field buses) and the recorded data.</li>
	<li>consideration of possible evaluation algorithms and procedures.</li>
	<li>Basics machine learning.</li>
	<li>Known quality parameters for evaluating the procedures.</li>
	<li>Consideration of the hardware and procedures for acceleration.</li>
	<li>Design of a prototype for at least one process.</li>
	<li>Implementation of a prototype.</li>
	<li>Testing and evaluation based on quality parameters.</li>
</ul>

