Captcha Recognition Using CNN

Abstract
CAPTCHAs are automated tests designed to distinguish between humans and computers. They could be easily solved by humans, but they become challenging for machines to solve, therefore preventing programs from abusing online services and occupying internet resources. Using Convolutional Neural Networks, the CAPTCHA tests could be solved automatically at high efficiency. Current approaches of high accuracy CAPTCHA recognition can be structurally complicated. As a result, our team explored a different approach to solve CAPTCHAs using a Convolutional Neural Network that is more efficient in terms of structural complexity and run time, with image processing being a possibility to enhance the accuracy. We also tested our networks on CAPTCHA datasets with character adhesion and background noise.

Existing System
Most service providers online have implemented CAPTCHA tests before the user is allowed to commit certain actions, such as submitting a form. Among all the CAPTCHAs, commonly used types contain low resolution, deformed characters with character adhesions and background noise, which the user must read and type correctly into an input box. Other deep learning algorithms like RNN and LSTM are unable to extract or segment selection from the given CAPTCHA image features.
Disadvantages
1.Less accuracy
PROPOSED SYSTEM
Based on existing methods of recognition, we built three CNN networks for testing. These networks do not necessarily have fewer parameters than other networks, but they have less runtime and complexity compared to other CNN networks such as DenseNet. It shows the structure of our first network, Network 1. In the first network, the image initially undergoes three convolutions. Two transition layers with a structure constructed by MaxPool → Batch Normalization (BN) → ReLU are inserted between the three convolutions to implement down-sampling. The third convolution is followed by a BN, a MaxPool, after which the model is flattened.
Advantages
1.High accuracy

SYSTEM REQUIREMENTS
HARDWARE REQUIREMENTS:
	System		:   Pentium IV 2.4 GHz.
	Hard Disk	          :   40 GB.
	Floppy Drive	:   1.44 Mb.
	Monitor	          :   14’ Colour Monitor.
	Mouse		:   Optical Mouse.
	Ram		          :   512 Mb.
SOFTWARE REQUIREMENTS:
	Operating system 	:   Windows 7 Ultimate.
	Coding Language		:   Python.
	Front-End			:   Python.
	Designing			:   Html,css,javascript.
	Data Base			:   MySQL.

