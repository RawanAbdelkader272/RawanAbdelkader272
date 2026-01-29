
<!--
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
  Rawan Abdelkader  |  Digital IC Design & Verification Engineer
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
-->

<div align="center">

### Digital IC Design & Verification Engineer
  
**GP Sponsored by Analog Devices** • E-JUST S'27 • Senior Year
  
```
   _______                     ___________    _____      _____ 
  |   _   |.--.--.-----.-----|   |   |   |  |   | |.--.|   __|
  |.  |___||  |  |  -__|     |       |   |__| | | ||  ||__   |
  |.  |   ||_____|_____|__|__|__|_|__|______|___|_||__||_____|
  |:  1   |
  |::.. . |
  `-------'
  Hardware doesn't lie. Verification proves it.
```

</div>

---

### 🔍 What I Build

- **Digital ICs** verified with UVM/cocotb testbenches
- **Hardware accelerators** for ML inference workloads
- **Pipelined datapaths** with signed/unsigned arithmetic units
- **RTL-to-GDSII** flows using industry-standard EDA tools

---

### ⚙️ Technical Stack

| Category       | Tools & Languages                                  |
|----------------|----------------------------------------------------|
| **RTL**        | Verilog • SystemVerilog • RISC-V ISA              |
| **Verification**| UVM • cocotb • constrained-random • coverage-driven |
| **Languages**  | Python (verification automation) • C++ • MATLAB   |
| **EDA Tools**  | QuestaSim • Vivado • Quartus Prime • Linux CLI    |
| **Flow**       | Synthesis • Timing Analysis • FPGA Prototyping    |

---

### 🧪 Current Focus

```systemverilog
// Target: ML accelerator microarchitecture
always_ff @(posedge clk) begin
  if (rst_n == 1'b0) begin
    state <= IDLE;
    acc_result <= '0;
  end else begin
    case (state)
      COMPUTE:  acc_result <= mac(a, b, acc_result);
      TRANSFER: dma_write(acc_result);
      default:  state <= IDLE;
    endcase
  end
end
```

- Optimizing systolic arrays for convolution kernels
- Building UVM environments with scoreboards & coverage collectors
- Characterizing power/area/performance tradeoffs in accelerator designs

---

### 🎓 Academic Background

**Electronics & Communication Engineering**  
Egypt-Japan University of Science and Technology (E-JUST)  
Expected Graduation: 2027  

**Industry Sponsorship**  
🎓 GP Program — Analog Devices  
*(Hands-on exposure to mixed-signal verification methodologies and silicon validation flows)*

---

### 💡 Engineering Philosophy

> *"A chip is only as good as its verification. I don't just write RTL prove it works under every corner case."*

- Strong C++/Python fundamentals → efficient testbench automation
- Obsessed with coverage closure and bug hunting
- Believe hardware accelerators are the future of efficient ML

---

### 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rawan-abdelkader-28a8092b2?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
[![Analog Devices](https://img.shields.io/badge/Analog%20Devices-FF0000?style=flat&logo=analogdevices&logoColor=white)](https://www.analog.com/)

*Open to design/verification internships & hardware accelerator research opportunities*

---

<div align="center">
  
`$ git log --author="Rawan" --oneline | head -5`  
```
a1b2c3d fix: resolved metastability in async FIFO handshake
e4f5g6h feat: added coverage groups for ALU corner cases
i7j8k9l docs: verification plan for ML accelerator core
m0n1o2p perf: 23% latency reduction in MAC pipeline
q3r4s5t init: UVM environment for signed multiplier DUT
```

</div>
