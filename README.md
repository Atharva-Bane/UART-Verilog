# UART Transceiver in Verilog

A UART (Universal Asynchronous Receiver-Transmitter) implemented in Verilog HDL featuring a Transmitter, Receiver, Baud Rate Generator, and a testbench for functional verification using Xilinx Vivado.

## Features

- FSM-based UART Transmitter and Receiver
- Configurable Baud Rate Generator
- Modular RTL design in Verilog HDL
- Functional verification using Vivado Simulator
- End-to-end UART communication

## Project Structure

```
rtl/
├── uart_tx.v
├── uart_rx.v
├── baud_rate_generator.v
└── uart_top.v

tb/
└── uart_top_tb.v
```

## Tools

- Verilog HDL
- Xilinx Vivado
- Vivado Simulator

## Future Improvements

- Parity Bit Support
- FIFO Buffer
- Configurable Data Width
- Error Detection
