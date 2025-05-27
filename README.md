# UART-FPGA-Communication

This project demonstrates UART communication between two Edge Artix-7 FPGA boards using Verilog.

## 🔧 Hardware Used
- 2× Edge Artix-7 FPGA boards
- USB-to-UART cables
- 7-Segment Display / LCD (optional)
- Power supply, jumper wires

## 📂 Files
- `UART-FPGA-Communication.zip`: Contains the Verilog code and implementation files for UART Tx and Rx modules.

## ⚙️ Functionality
- UART Tx module on one FPGA sends data serially.
- UART Rx module on the second FPGA receives the data.
- Data is displayed via LED or 7-segment display.

## 🛠️ Tools Used
- Xilinx Vivado (for synthesis and implementation)
- Verilog HDL

## 🚀 How to Use
1. Clone or download the ZIP.
2. Open the project in Vivado.
3. Generate bitstream and upload to both FPGA boards.
4. Connect UART Tx of board 1 to UART Rx of board 2.
5. Observe the output.

## 📬 Contact
Created by [MARRAPU PRADEEP KUMAR] – feel free to connect for collaboration or questions!
