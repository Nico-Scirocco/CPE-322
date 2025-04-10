# Lab 1 GHDL & GTKWave

*I pledge my honor I have abided by the Stevens Honor System - Nicholas Scirocco*

## Half Adder Example

> Code

```
ghdl -a ha.vhdl
ghdl -a ha_tb.vhdl
ghdl -e ha_tb
ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
gtkwave ha.vcd
```

![HA](https://github.com/user-attachments/assets/72bc51e2-d792-4065-a8c1-d8bda282c525)



## 4-to-1 Multiplexer

> Code

```
ghdl -a mux.vhdl
ghdl -a mux_tb.vhdl
ghdl -e mux_tb
ghdl -r mux_tb --vcd=mux.vcd
gtkwave mux.vcd
```
![MUX](https://github.com/user-attachments/assets/7c02eee8-f18a-4f3a-b337-d971f9b50656)
