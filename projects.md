# Projects
_Notation: C/O (Conference); J (Journal)_
 
## 7. March 2018 – February 2019
### Title: 
At-the-Edge Machine Learning VLSI Accelerators for Energy-efficient Brain State Classification and Responsive Stimulation
### Description: 
This project is in collaboration between Prof. Roman Genov at University of Toronto, Prof. Taufik Valiante at Krembil Research Institute, and Prof. Naveen Verma at Princeton University.

The main goals include the implementation of energy-efficient machine learning algorithms for both: (1) accurate prediction/detection of pathological brain states such as epileptic seizures; and (2) patient-tailored lifelong adaptive neurostimulation.

The algorithms are currently support vector machines and will likely also include reinforcement learning / RNNs / deep learning etc in the future. These would be initially implemented on an FPGA connected in a closed loop to a human patient brain, with a digital ASIC implementation constraints in minds. Next these would be synthesized on a low-power implantable ASIC. This is currently a fully-digital computing architecture: on-FPGA/on-ASIC open-core microprocessor MSP430 IP combined with accelerator co-processors both for multiple feature extractors and the data classifier, as well as on-chip SRAM, etc. 

The project involves fully-digital computing architectures (on-chip open-core MSP430 IP combined with accelerator co-processors, highly parallel accelerators, bit-level processing, asynchronous processors, etc) - first in Verilog/FPGA then fabricated in digital CMOS; novel ways of implementing both feature extraction (spatio-temporal filtering, PCA, ICA, etc) and data classification in VLSI; resources balancing between feature extraction and data classification.

### Publications: 
C24
  
## 6. April 2014 – February 2018
### Title: 
Low-latency Coordinate Rotation Digital Computer (CORDIC)
### Description: 
This project was in collaboration with the Ho Chi Minh University of Science.
### Publications: 
J8, J7, J6, J4, J1
 
## 5. October 2014 – February 2018
### Title: 
Hardware Technologies for High-Performance Bitmap-Index-Based Data-Analytics System
### Description: 
This project was led by [Prof. Cong-Kha Pham](http://kjk.office.uec.ac.jp/Profiles/6/0000550/prof_e.html) ([UEC](https://www.uec.ac.jp/eng/)) and funded by Advanced Original Technology Co., Ltd ([AOT](http://www.aot-slid.com)) and Nippon Computer Dynamics Co., Ltd ([NCD](https://www.ncd.co.jp/)).\
In this project, we proposed several scalable bitmap-index-based analytics hardware accelerators based on FPGA technology. We then integrated the hardware accelerators in a real database system. The system outperformed CPU and GPU by at least 3 times regarding energy efficiency. Furthermore, we also released some 65-nm and 180-nm CMOS chips for data analytics.

256-bit Priority Encoder Using 1D-array to 2D-array Conversion

| Meas. Date | Technology | Core Size |  I/O VDD | Core VDD | 
|--|--|--|--|--|
| **September 2017** | 65-nm SOTB CMOS | 0.78 $mm^2$ | 3.3 V | 0.6 V - 1.2 V |
### Publications: 
J10, J9, J5, J3, J2
 
## 4. April 2015 – February 2018
### Title: 
Reliable and Self-Adaptive Transfer Protocol for Wireless Multimedia Sensor Network (WMSN)
### Description: 
In this project, we proposed and simulated a reliable and self-adaptive transfer protocol for WMSN. We subsequently designed a full-stack embedded software containing this protocol in a sensor node formed by a Raspberry Pi and an Atmel RF. The experimental results showed that this design could stream a 640x480@15fps video between several nodes with distance up to 500 m. The video was captured by a camera and compressed in H.264 standard. We also successfully integrated the proposed design into other commercial ZigBee networks. 
This project was led by [Prof. Koichiro Ishibashi](http://mtm.es.uec.ac.jp/english/professor.html) ([UEC](https://www.uec.ac.jp/eng/)) and funded by the Semiconductor Technology Academic Research Center ([STARC](http://www.starc.jp/)).

The general block diagram of source node and sink node.
 

The prototype of a sensor node.
### Publications: 
    C20, C6
 
## 3. October 2016 – November 2016
### Title: 
Detection and Prediction of Telecommunication Equipment Failures Using Machine Learning Algorithms
### Description: 
In this project, we first processed a 3-month data set collected from all of the telecommunication equipment installed in Kuala Lumpur. We then employed KNN to detect up to 85% of faulty devices. Besides, nonlinear regression was used to predict the situations of the normal devices.\
This project was funded by Telekom Malaysia Research & Development and the Japan Student Services Organization (1,100 USD).
### Publications: 
C17
 
## 2. 2012 – 2013
### Title: 
Low-Cost Network-Attached Storage for Home Entertainment Applications
### Description: 
In this project, we addressed the pros and cons (cost, flexibility, the number of users’ accesses, etc.), of all of the commercial network-attached storage devices using in home entertainment. We then proposed some optimized transfer protocols and implement them in the low-cost embedded boards (Raspberry Pi, Beagle Bone, and Panda) as gateways. The experimental results showed that our design could stream up to 6 full-HD videos simultaneously from the storage devices to the mobile devices through the proposed gateways in the 802.11 network. More importantly, we successfully commercialized the product and APIs.\
This project was funded by the Ho Chi Minh Department of Science and Technology (4,000 USD).
### Publications: 
O11
 
## 1. 2011 – 2012
### Title: 
Designing a High-Speed Motion Detection System
### Description: 
In this project, a spatial-temporal entropy algorithm to not only detect moving objects but also precisely estimate their velocity in real time was proposed. This algorithm then was implemented in an Intel Stratix III FPGA. The full system was fully operational at the 100-MHz clock frequency and could successfully detected multiple moving objects in a 1280x960@30fps input video.\
This project was funded by HCMUS (700 USD).
### Publications: 
O1, C1


# IC Design Gallery


Publications:
-- C22	

