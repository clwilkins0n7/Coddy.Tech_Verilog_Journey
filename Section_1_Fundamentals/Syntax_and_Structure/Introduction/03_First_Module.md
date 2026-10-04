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


## Challenge

Quoted from Coddy.Tech: 
```text
In this challenge, you need to create a simple module that performs the OR operation.

What to do:

1. The module should be named or_gate
2. It should have an input called x
3. It should have an input called y
4. It should have an output called z
5. Inside the module, use assign to make z equal to x OR y

- The module header and its three ports are already in the editor. The line you need to add is the assign statement inside the module.
- Note: In Verilog, OR is written with the pipe symbol |. It outputs 1 (true) if at least one of the inputs is 1 (true).
```

```verilog
// The module header and its ports are already written for you
module or_gate(
  input x,
  input y,
  output z
);

  // Your turn: use assign to set z to x OR y
  // In Verilog, OR is written as |

  assign z = x | y;

endmodule
```

Output:
- 0 | 0 = 0
- 0 | 1 = 1
- 1 | 0 = 1
- 1 | 1 = 1
