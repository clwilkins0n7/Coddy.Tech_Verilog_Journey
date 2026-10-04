# First Module

A "module" is the basic building block in Verilog, every piece of code sits inside a module.

## Module Syntax
```verilog
module module_name (
  // inputs, outputs here
);

  // Behaviour inside here

endmodule
```
- Every module starts with `module` and ends with `endmodule` (in the same indentation)

## Input and Outputs of Modules

```verilog
module and_gate(
  input   a,     // a comes INTO the module
  input   b,     // b comes INTO the module
  output  c     // c goes OUT of the module
);

  // Behaviour goes here

endmodule
```

## Behaviour of Modules

- The behaviour of modules is what the module is designed to do, so in the following example this module represents an AND gate

```verilog
module and_gate(
  input   a,
  input   b,
  output  c
);

  assign c = a & b;  // c is 1 only when a AND b are 1

endmodule
```

- `assign` continuously connects the right side of the `=` to the left side
- `&` means AND in Verilog
