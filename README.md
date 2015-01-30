# IMAGE_PROCESS_SUB_MODULE
All sub modules for image processing project on FPGA.

***

Dirs Struct:
===========
**This project will content many moudles, which are useful in image processing.  
Each module will have its directory, and this directories will have the same struct as follows:**  

1.IMAGE_FOR_TEST:
-----------------
**A directory for storing images, you can put your images for testing here.**  

2.SOFT_SIM:
----------
**Files for software simulation will be here, those can show you this module's function by software method.  
Before using those, you must get a python 2.7.8.**

3.HDL:
-----
**FPGA project will be here, built on xilinx vivado.**

***

Modules:
=======
Kind:
----
**All sub modules will be given a kind, and they will be placed in thoes directories, like "POINT".**
1.RGB2GRAY:
-----------
**Function:**  
Graying, transforming a 24bits(rgb) image to a 8bits(gray) image.  
**Files:**  
1. RGB2GRAY.v: Main function.
2. RGB2GRAY_TB.sv: TestBench.

2.GRAY2BIN:
-----------
**Function:**  
Binorization, transforming a 8bits(gray) image to a 1bit(bin) image.  
**Files:**  
1. GARY2BIN.v: Main function.
2. GARY2BIN_TB.sv: TestBench.

***

Others
======

AUTHOR
---
Dai Tianyu(dtysky)   
[dtysky@outlook.com](dtysky@outlook.com)  
[http://github.com/dtysky](http://github.com/dtysky)

Copyright
---
Copyright © 2014, Dai Tianyu(dtysky). All Rights Reserved.  
This project is free software and released under the [MIT License (MIT)](http://mit-license.org/).