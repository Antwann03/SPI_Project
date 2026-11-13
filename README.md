# Overview
We will be integrating a top level module into a custom AXI-Lite Peripheral whcih will be connected to the Zynq PS in Vivado and then we will write a Vitis Applicaiton in C where we will be able to read ambient light data from a PMOS ALS(Ambient Light Sensor) Sensor.
# Design Summary
There will be 5 modules howevver foru of them will be suporting the TOP module. The following modules are spi_clk_div, spi_shift_reg, spi_cs_ctrl, spi_fsm and spi_master.

Spi_master will be the top-level integration module. The rest will be submodules.

# Verificaiton and Results

# Known Issues or Limitations

# References
ece520L_fall26_design_project_part1_spi_master.pdf
