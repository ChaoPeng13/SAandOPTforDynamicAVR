# Schedulability Analysis and Performance Optimization of Dynamic AVR Task Model #

The file "dynamic-AVR-analysis.pdf" introduces the dynamic AVR task model and provides the analysis method for such tasks.  

The file "engine-optimization.pdf" presents an exhaustive search optimization algorithm (namely dAVR-exact), which will dynamically adjust the switching speeds to maximize the control performance for each data point in the engine speed profiles.

The source code evaluates:
- the engine control performance of the optimization procedures using static and dynamic AVR task model
- the accuracy of the schedulability analysis techniques for the dynamic AVR task model

And the code has been tested to work well in Visual Studio 2012 with Microsoft Windows 7, and Unix-like systems (e.g., Ubuntu and Raspberry Pi Desktop).

## Authors ##
### Chao Peng ###
National University of Defense Technology, Changsha, Hunan, China<br/>
E-mail: pengchao06@gmail.com

### Yecheng Zhao ###
Virginia Polytechnic Institute and State University<br/>
E-mail: zyecheng@vt.edu

### Haibo Zeng ###
Virginia Polytechnic Institute and State University<br/>
302 Whittemore (0111), Virginia Tech, Blacksburg, VA 24061, USA<br/>
Tel.: +1-540-231-5961<br/>
Fax: +1-540-231-3362<br/>
E-mail: hbzeng@vt.edu

## Requirements ##
GSL - GNU Scientific Library

## Evaluating Procedure ##

The main.cpp file includes all the experiments for our paper "Schedulability Analysis of Engine Control Tasks
with Dynamic Switching Speeds", which was submitted to RTSS 2018. 

Please let us know if there is any issue.
