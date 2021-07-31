# FPGA-Based Neural Network Acceleration for Handwritten Digits & Alphabets Recognition 

## This is the graduation project from NCKU EE
* Auther: 
    - Jack from NCKUEE
    - Charley from NCKUES
* Tools:  PYNQ-Z2, Vivado, Jupyter notebook
* Programming language:  Verilog, Python
* Architecture:

## PYNQ-Z2 Utilization
|Resource                  |Utilization  |Avaliable    |Utilization % |
|  -----                   | -----       | -----       | -----        |
|LUT     	               |40856        |53200        |76.80         |
|LUTRAM                    |1923         |17400        |11.05         |
|FF                        |43075        |106400       |40.48         |
|BRAM   	               |112          |140          |80.00         |
|DSP    		           |200          |220          |90.91         |
|BUFG                      |2            |32           |6.25          |

<img src="/Image/Utilization_graph.png" height="40%" width="40%"/>

## References:
* [1] https://github.com/ChrisZonghaoLi/Rudi_CNN_Conv_Accelerator
* [2] https://github.com/eecheng87/Convolution
* [3] https://github.com/WeiCheng14159/MNIST_accelerator
* [4] NCKU Courses:
    - AI-ON-CHIP FOR MACHINE LEARNING AND INFERENCE
    - DEEP LEARNING INTEGRATED CIRCUIT DESIGN AND ACCELERATION
* [5] LeCun, Yann  (1998), "Gradient-Based Learning Applied to Document Recognition"
* [6] Dai Rongshi  (2019), "Accelerator Implementation of Lenet-5 Convolution Neural Network Based on FPGA with HLS"
* [7] Yu-Hsin Chen (2017), "Eyeriss: An Energy-Efficient Reconfigurable Accelerator for Deep Convolutional Neural Networks"
* [8] Vivienne Sze, Yu-Hsin Chen, Tien-Ju Yang, Joel S. Emer (2017), "Efficient Processing of Deep Neural Networks: A Tutorial and Survey"
* [9] David Gschwend (2016), "ZynqNet: An FPGA-Accelerated Embedded Convolutional Neural Network"
