# Rawan Abdelkader
### Digital IC Design & Verification Engineer | Analog Devices GP Scholar

<div align="center">

```
clk   ━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓    ┏━━━┓
      ━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛    ┗━━━┛
data  ━━━R━━━━━A━━━━━W━━━━━A━━━━━N━━━━━ ━━━━A━━━━━B━━━━━D━━━━━E━━━━━L━━━━━K━━━━━A━━━━━D━━━━━E━━━━━R━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
```

[![Analog Devices](https://img.shields.io/badge/Analog%20Devices-FF0000?logo=analogdevices&logoColor=white)](https://www.analog.com/)
[![E-JUST](https://img.shields.io/badge/E--JUST-004080?logo=edu&logoColor=white)](https://www.ejust.edu.eg/)

</div>

---

## Silicon Validation Profile

Verification engineer specializing in **coverage-driven development** for digital datapaths and ML acceleration cores. Currently developing pipelined arithmetic units with signed/unsigned operand handling under Analog Devices' GP Scholars Program. My workflow: write verification plan → achieve 100% functional coverage → implement RTL → close timing. Not the other way around.

---

## Signal Integrity Report

```
┌──────────────────────────────────────────────────────────────────────────────┐
│  TIMING DIAGRAM: ML ACCELERATOR PIPELINE                                     │
├──────────────────────────────────────────────────────────────────────────────┤
│ clk   ━━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━━┓  ┏━ │
│ rst_n ━━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━━┛  ┗━ │
│ in    ━━━━━[R]━━[A]━━[W]━━[A]━━[N]━━[ ]━━[A]━━[B]━━[D]━━[E]━━[L]━━[K]━━[A]━ │
│ stage1━━━━━━━━[R]━━[A]━━[W]━━[A]━━[N]━━[ ]━━[A]━━[B]━━[D]━━[E]━━[L]━━[K]━━[A] │
│ stage2━━━━━━━━━━━━[R]━━[A]━━[W]━━[A]━━[N]━━[ ]━━[A]━━[B]━━[D]━━[E]━━[L]━━[K] │
│ stage3━━━━━━━━━━━━━━━━[R]━━[A]━━[W]━━[A]━━[N]━━[ ]━━[A]━━[B]━━[D]━━[E]━━[L] │
│ out   ━━━━━━━━━━━━━━━━━━━[R]━━[A]━━[W]━━[A]━━[N]━━[ ]━━[A]━━[B]━━[D]━━[E]━━[L] │
└──────────────────────────────────────────────────────────────────────────────┘
Coverage: 94.7% functional | 89.2% code | 91.5% toggle
```

---

## Technical Implementation Stack

| Layer | Tools & Methodologies |
|-------|------------------------|
| **Microarchitecture** | Pipelined MAC arrays • Systolic dataflow • Operand forwarding • Hazard detection |
| **RTL Implementation** | Verilog • SystemVerilog • Signed/unsigned arithmetic • Clock domain crossing (async FIFOs) |
| **Verification** | UVM • cocotb • Constrained-random stimulus • Scoreboards with C++ golden models • Coverage closure |
| **Physical Validation** | Vivado (Artix-7) • Quartus Prime (Cyclone) • Timing analysis • FPGA prototyping |

---

## Academic Credentials

**B.Sc. Electronics & Communication Engineering**  
Egypt-Japan University of Science and Technology (E-JUST) | Expected 2027  

**Industry Immersion**  
Analog Devices GP Scholars Program — silicon validation workflows, mixed-signal test methodologies, and production verification practices under ADI mentorship.

---

## Verification Philosophy

> *"I don't verify designs — I validate specifications. Every coverage point maps to a requirement. Every test vector has a purpose. Silicon doesn't negotiate with timing violations, and neither do I."*

- Architect testbenches before RTL exists (spec-driven verification)
- Automate regression management to detect regressions within 15 minutes of commit
- Characterize PPA tradeoffs during microarchitecture exploration, not post-synthesis
- Treat metastability not as a corner case but as a first-class design constraint

---

## Professional Channels

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rawan-abdelkader-28a8092b2)

<div align="center">
  
*Seeking design/verification roles shipping production silicon — ML accelerators, DSP cores, or high-speed interfaces*

</div>

