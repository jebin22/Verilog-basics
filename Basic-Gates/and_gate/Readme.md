# AND Gate using Verilog

## 📌 Description
This project implements a basic AND gate using Verilog HDL.

<img align="right bottom" width="370" height="290" src = "https://i.pinimg.com/1200x/b1/8a/56/b18a56a586c85f79f0443de881941b15.jpg">

## Inputs and Output
- **Inputs:** a, b  
- **Output:** y  

##  Functionality
The output `y` is HIGH (1) only when both inputs `a` and `b` are HIGH (1).

##  Code
```verilog
module and_gate(out, a, b);
  input a,b;
  output out;
  assign out = a & b;
endmodule
```
### Author - jebin
