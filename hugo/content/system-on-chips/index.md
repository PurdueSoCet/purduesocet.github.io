---
date: 2017-03-03T09:53:14-08:00
title: System-On-Chips
weight: 20 
---

## AFT-X04

```toml
Goal: AFT-X04 is an attempt at creating a simple microcontroller centered around a RISC-V core.  
It features a richer set of peripherals than AFT-X03 and includes interrupts.
```

**Status:**

AFT-X04 is currently under design and verification.  

![aft_x04](/images/aft_x04_small.jpg)


## AFT-X03

```toml
Goal: AFT-X03's main focus was to create an SoC with basic functionality.  The only supported
peripheral is GPIO. This was the team's first attempt at on-chip SRAM.  The simplicity of the
chip allows us to focus on establishing a team design flow before moving onto more complex designs. 
```

**Status:**

AFT-X03 is taped out and is currently under bring-up.

![aft_x03](/images/aft_x03_small.png)


## AFT-X01/AFT-X02

```toml
Goal: AFT-X01 and AFT-X02 wwere the team's first attempt at designing and taping-out an SoC.  
Both chips have the same architecture. The bus structure of this chip was adopted by all of
our current SoCs. 
```

**Status:**

AFT-X01 had an error in the power distribution and could not successfully be powered up.

AFT-X02 was successfully powered on during bring-up.  We were able to communicate with the debugger through UART.


![aft_x01](/images/aft_x01_small.png)



