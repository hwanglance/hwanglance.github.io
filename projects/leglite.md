---
layout: project
type: project
published: true
image: images/LEGLiteP0real-lowres.jpg
title: LegLITE microprocessor
permalink: projects/leglite
# All dates must be YYYY-MM-DD format!
date: 2017-12-12
labels:
  - Verilog
  - HDL
  - FPGA
  - Vivado
  - ARMv8
summary: A simplified ARMv8 simulation that I made and ran on a Digilent Basys 3 Artix-7 FPGA Trainer Board for my course EE 361/361L.
---

For my introductory course on computer hardware design, EE 361 and EE 361L, our lab group of two wrote a microprocessor simulation that ran on a Digilent Basys 3 Artix-7 FPGA Trainer Board.  The simulation was written using the Verilog hardware description language (HDL) using the Xilinx Vivado WebPACK environment.  The architecture of the implemented microprocessor is called LEGLite, which is a simplification of LEGv8.  For background, LEGv8 is a simplification of ARMv8. 

Having gone through an in-lab tutorial on using Vivado, our lab group was given the assignment to design a microprocessor that implements a very basic form of pipelining.  A pipelined processor is often contrasted with a single-cycle processor, with pipelined processors essentially always having superior performance to a single-cycle processor.  This is due to the ability for a pipelined processor to theoretically begin a new computer instruction every clock cycle as opposed to having to complete multiple clock cycles to begin a new instruction.

Source: <a href="https://github.com/hwanglance/leglite"><i class="large github icon "></i>hwanglance/leglite</a>
