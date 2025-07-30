# UART System Verilog Design

## Overview
This project implements a UART (Universal Asynchronous Receiver/Transmitter) communication protocol in System Verilog. It includes a configurable transmitter and receiver module, verified through testbench simulation in Xilinx Vivado.

## **Key Features**
- UART Transmitter and Receiver modules
- Configurable baud rate via parameters
- Complete RTL design in System Verilog
- Synthesizable and FPGA testable
- Functional verification using testbench

---

## **Technologies Used**
- *Verilog HDL*
- *Xilinx Vivado*
- *Simulation & Timing Analysis*
- *Testbench Design*

---

## **Files Included**
- `uart_top.v` – Top-level module connecting TX and RX
- `uarttx.v` – UART Transmitter
- `uartrx.v` – UART Receiver
- `tb_uart_top.v` – Testbench for simulation
- `README.md` – This documentation
