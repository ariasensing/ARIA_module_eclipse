<h2>Source code for the AMHx boards</h2>
This repository contain source code for develop application based on Hydrogen SoC.<br>

Boards supported:<br>
&nbsp;&nbsp;AHM2D<br>
&nbsp;&nbsp;AHM3D<br>
&nbsp;&nbsp;AHM2DSC<br>
&nbsp;&nbsp;AHM3DSC<br>
&nbsp;&nbsp;AHM2DL<br>

Toolchain:<a href="https://github.com/pulp-platform/pulp-riscv-gnu-toolchain.git">pulp-riscv-gnu-toolchain</a>

<b>Processor configuration ISA options:</b> rv32imfc_xcorev_xfhalf

<h3>Global preprocessor defines</h3>
Assembler<br>
&nbsp;&nbsp;INCLUDE_COPRBIN<br>
<br>
C preprocessor<br>
&nbsp;&nbsp;HWREV=0x00010001<br>
&nbsp;&nbsp;CORE_CV<br>

<h4>Include file list</h3>
&nbsp;&nbsp;"common"<br>
&nbsp;&nbsp;"ipc"<br>
&nbsp;&nbsp;"comunication"<br>
&nbsp;&nbsp;"comunication_SPIS"<br>
&nbsp;&nbsp;"driverUser"<br>
&nbsp;&nbsp;"dsp/inc"<br>
&nbsp;&nbsp;"hal/inc"<br>
&nbsp;&nbsp;"hw"<br>
&nbsp;&nbsp;"processing"<br>
&nbsp;&nbsp;"reconstruction"<br>
&nbsp;&nbsp;"src"<br>
&nbsp;&nbsp;"startup"<br>
&nbsp;&nbsp;"utils"<br>
<br>

<h4>Linker scripts</h4>
&nbsp;&nbsp;"ld/link_sectors.ld"<br>
&nbsp;&nbsp;"ld/link_hydr_cv32e40_wcopr.ld"<br>


<h4>Libraries</h4>
&nbsp;&nbsp;m<br>
&nbsp;&nbsp;hal_libs_cv32e40_priv_periph<br>

Doxygen documentation source file is available inside "doc" folder
