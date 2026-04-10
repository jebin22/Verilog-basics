# AND Gate using Verilog

## 📌 Description
This project implements a basic AND gate using Verilog HDL.

## ⚙️ Inputs and Output
- **Inputs:** a, b  
- **Output:** y  

## 🔍 Functionality
The output `y` is HIGH (1) only when both inputs `a` and `b` are HIGH (1).

## 💻 Code
```verilog
module and_gate(out, a, b);
  input a,b;
  output out;
  assign out = a & b;
endmodule
```
### Author - JEBIN
