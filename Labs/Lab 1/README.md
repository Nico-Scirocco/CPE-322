# Lab 1 GHDL & GTKWave


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




