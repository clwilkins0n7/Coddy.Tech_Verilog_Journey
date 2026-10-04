# What is Verilog?

* Verilog is a hardware description language (HDL) used to model, design adn simulate digital electronics.
* Unlike software languages that run **sequentially** on a CPU, Verilog describes hardware that operates in **parallel**


```verilog
module main;
  initial begin
    $display("Hello World!");
    $finish;
  end
endmodule
```

The code above simply prints "Hello World" onto the output console.
