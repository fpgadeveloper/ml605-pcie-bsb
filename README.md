ml605-bsb
=========

PCIe project created with the Base System Builder for the ML605

### Description

This project was generated using Xilinx Platform Studio's Base System Builder
for the ML605 evaluation board and includes the AXI PCI Express peripheral.
It serves as a base design for other projects that you will find on
fpgadeveloper.com.

### Usage Notes

To run this design on the ML605, you must setup the FPGA configuration by
either compact flash (SysAce) or the Platform Flash XL device. Configuration
by JTAG is not effective because the board must be configured before the
host machine is booted.

Also, you must have the ML605 plugged into a functional PCIe bus to run this
design, otherwise the MicroBlaze will be kept in reset.

### Requirements

* ISE Design Suite 14.7
* ML605 Evaluation Board

### License

Feel free to modify the code for your specific application.

### Fork and share

If you port this project to another hardware platform, please send me the
code or push it onto GitHub and send me the link so I can post it on my
website. The more people that benefit, the better.

### About the author

I'm an FPGA consultant and I provide FPGA design services and training to
innovative companies around the world. I believe in sharing knowledge and
I regularly contribute to the open source community.

Jeff Johnson
http://www.fpgadeveloper.com