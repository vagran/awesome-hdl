# Awesome Hardware Description Languages [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of amazingly awesome hardware description language projects.

# Hardware developement

## HDL doc

* Verilog [IEEE Std 1364-2001](https://inst.eecs.berkeley.edu/~cs150/fa06/Labs/verilog-ieee.pdf), [Quick Ref Guide](http://sutherland-hdl.com/pdfs/verilog_2001_ref_guide.pdf), [SystemVerilog 3.1a](http://www.ece.uah.edu/~gaede/cpe526/SystemVerilog_3.1a.pdf), [Synthesizing SystemVerilog Busting the Myth that SystemVerilog is only for Verification](http://sutherland-hdl.com/papers/2013-SNUG-SV_Synthesizable-SystemVerilog_paper.pdf)
* VHDL standards [IEEE Std 1076-2000](http://edg.uchicago.edu/~tang/VHDLref.pdf)
* SystemC standards [IEEE Std 1666-2011](http://paginas.fe.up.pt/~ee07166/lib/exe/fetch.php?media=1666-2011.pdf)


## HDL simulators and compilers

   * Verilog
      - [Verilator](https://www.veripool.org/wiki/verilator) Verilog to C++ transpiler
      - [Icarus Verilog](http://iverilog.icarus.com/) - simulator
      - [Yosys](http://www.clifford.at/yosys/) - RTL synthesis
   * VHDL
      * [nvc](https://github.com/nickg/nvc) - GPLv3 VHDL compiler and simulator, IEEE 1076-2002, writen in C
      * [GHDL](https://github.com/ghdl/ghdl) - VHDL compiler and simulator, IEEE 1076-2002, writen in ADA

## Meta HDL and Transpilers

* C/C++
   - [autopiper](https://github.com/google/autopiper)

* Haskel
   - [concat](https://github.com/conal/concat) Haskell to hardware, 2016+
   - https://github.com/conal/talk-2015-haskell-to-hardware
   - [CλaSH](https://github.com/clash-lang/clash-compiler) - A functional hardware description language
   - [pipelineDSL](https://github.com/p12nGH/pipelineDSL) - A Haskell DSL for describing hardware pipelines

* Java
   - [jhdl](http://www.jhdl.org/) ..2006
   - [PSHDL](http://pshdl.org/)

* JavaScript
   - [reqack](https://github.com/drom/reqack) -  elastic circuit toolchain
   - [hdl-js](https://github.com/DmitrySoshnikov/hdl-js) - Hardware description language (HDL) parser, and Hardware simulator.
   - [shdl](https://github.com/jcbuisson/shdl) - Simple Hardware Description Language

* Julia
   - [Julia-Verilog](https://github.com/interplanetary-robot/Verilog.jl) - a Verilog-generation DSL for Julia., 2017

* Python
  - [HWT](https://github.com/Nic30/hwt) Meta HDL, verification env. IP-core generator, analysis tools, HDL glue
  - [garnet](https://github.com/StanfordAHA/garnet) Coarse-Grained Reconfigurable Architecture generator based on magma, 2018+
  - [magma](https://github.com/phanrahan/magma/) - Meta HDL, 2017+
  - [migen](https://github.com/m-labs/migen) - Meta HDL, 2013+
  - [MyHDL](https://github.com/myhdl/myhdl) - Process based HDL, verification framework included, 2004+
  - [PyRTL](https://github.com/UCSBarchlab/PyRTL) - Meta HDL, simulator suitable for research.
  - [PyMTL](https://github.com/cornell-brg/pymtl) - Process based HDL, verification framework included, 2014+
  - [veriloggen](https://github.com/PyHDI/veriloggen) - 2015-?, Python, Verilog centric meta HDL with HLS like features

* Rust
   - [hoodlum](https://github.com/tcr/hoodlum) - Meta HDL, 2016+

* Scala
   - [chisel](https://github.com/freechipsproject/chisel3) - Meta HDL, 2012+
   - [SpinalHDL](https://github.com/SpinalHDL/SpinalHDL) - Meta HDL 2012+

## HLS

* [legup](http://legup.eecg.utoronto.ca/) - 2011-2015, LLVM based c->verilog
* [bambu](http://panda.dei.polimi.it/?page_id=31) - 2003-?, GCC based c->verilog
* [augh](http://tima.imag.fr/sls/research-projects/augh/) - c->verilog, DSP support
* https://github.com/utwente-fmt - abstract hls, verification libraries
* [Shang](https://github.com/etherzhhb/Shang) - 2012-2014, LLVM based, c->verilog
* [xronos](https://github.com/endrix/xronos) - 2012, java, simple HLS
* [Potholes](https://github.com/SamuelBayliss/Potholes) - 2012-2014 - polyhedral model preprocessor, Uses Vivado HLS, PET
* [hls_recurse](https://github.com/m8pple/hls_recurse) - 2015-2016 - conversion of recursive fn. for stackless architectures
* [hg_lvl_syn](https://github.com/funningboy/hg_lvl_syn) - 2010, ILP, Force Directed scheduler
* [abc](https://people.eecs.berkeley.edu/~alanmi/abc/) <2008-?, A System for Sequential Synthesis and Verification
* [polyphony](https://github.com/ktok07b6/polyphony) - 2015-2017, simple python to hdl
* [DelayGraph](https://github.com/ni/DelayGraph) - 2016, C#, register assignment algorithms
* [coreir](https://github.com/rdaly525/coreir) - 2016-?, LLVM HW compiler## License

## Other HDL languages

* [act](https://github.com/asyncvlsi/act) - asynchronous circuit/compiler tools

## Synthesis tools

* [vtr-verilog-to-routing](https://github.com/verilog-to-routing/vtr-verilog-to-routing)
* [yosys](https://github.com/YosysHQ/yosys) - RTL synthesis framework


## Libraries with informations about boards/chips

* [loam](https://github.com/phanrahan/loam) - Buildsystem for magma
* [litex](https://github.com/enjoy-digital/litex) - Buildsystem for migen


## Visualization and Documentation generators

* [bitfield](https://github.com/drom/bitfield) - Javascript bit field diagram renderer
* [d3-wave](https://github.com/Nic30/d3-wave) - Javascript wave graph visualizer for RTL simulations
* [d3-hwschematic](https://github.com/Nic30/d3-hwschematic) - Javascript hierarchycal schematic visualizer for HDLs
* [wavedrom](https://github.com/drom/wavedrom) - Javascript wave graph visualizer for documentations and sim.
* [netlistsvg](https://github.com/nturley/netlistsvg) - Javascript schematic visualizer
* [sphinx-hwt](https://github.com/Nic30/sphinx-hwt) - Plugin for sphinx documentation generator which adds shematic into html documentaion.


## HDL parsers

* [hdlConvertor](https://github.com/Nic30/hdlConvertor) - Fast (System) Verilog/VHDL parser writen as C++ extension for Python
* [pyVHDLParser](https://github.com/Paebbels/pyVHDLParser) - VHDL parser written in Python
* [rust_hdl](https://github.com/kraigher/rust_hdl) - VHDL parser and language server written in Rust

## Other Simulation tools

* [midas](https://github.com/ucb-bar/midas) - FPGA-Accelerated Simulation Framework Automatically Transforming Arbitrary RTL
* [cocotb](https://github.com/potentialventures/cocotb) - A coroutine based cosimulation library for writing VHDL and Verilog testbenches in Python

# Open Hardware

* [opencores.org](https://opencores.org/) - webpage which hosts many openhardware projects
* [enjoy-digital repositories](https://github.com/enjoy-digital?tab=repositories) - Migen, SoC level modules
* [ZipCPU repositories](https://github.com/ZipCPU?tab=repositories) - Verilog, mostly peripherals, DSP
* [rhea](https://github.com/cfelton/rhea) - MyHDL, SoC level modules
* [FPGAwars FPGA-peripherals](https://github.com/FPGAwars/FPGA-peripherals) - Verilog, simple peripherals
* [PoC](https://github.com/VLSI-EDA/PoC) - VHDL, utils
* [picorv32](https://github.com/cliffordwolf/picorv32) - Verilog, A Size-Optimized RISC-V SoC
* [openrisc](https://github.com/openrisc) - OpenRISC, FuseSoC, peripherals and cpu parts
* [NyuziProcessor](https://github.com/jbush001/NyuziProcessor) - GPGPU
* [VexRiscv](https://github.com/SpinalHDL/VexRiscv) - RISC-V written in SpinalHDL
* [Awesome Open Hardware Verification](https://github.com/ben-marshall/awesome-open-hardware-verification/) - A list of open source tools and frameworks for hardware verification.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Aliaksei Chapyzhenka](http://drom.io) has waived all copyright and related or neighboring rights to this work.
