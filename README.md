<div align="center">

<pre style="font-family:monospace; line-height:1.3; color:#00f000">
clk ━━━━━━━━━━━━━━━━━━━━━━━━━━┓                                     ┏━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
┗━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━┛
rst_n     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
data_out  ━━━━━━━━━━━━━━━━━━━━━< R A W A N >━━━━━━━━━━━━━━━━━━━━━━━━━━< A B D E L K A D E R >━━━━━━━━━━━━━━━━━
</pre>

[![Analog Devices](https://img.shields.io/badge/Analog%20Devices-FF0000?logo=analogdevices&logoColor=white)](https://www.analog.com/)
[![E-JUST](https://img.shields.io/badge/E--JUST-004080?logo=education&logoColor=white)](https://www.ejust.edu.eg/)

</div>
<!--
  ██████╗  █████╗ ██╗   ██╗██╗     ███████╗██████╗ 
  ██╔══██╗██╔══██╗██║   ██║██║     ██╔════╝██╔══██╗
  ██████╔╝███████║██║   ██║██║     █████╗  ██████╔╝
  ██╔══██╗██╔══██║╚██╗ ██╔╝██║     ██╔══╝  ██╔══██╗
  ██║  ██║██║  ██║ ╚████╔╝ ███████╗███████╗██║  ██║
  ╚═╝  ╚═╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝╚══════╝╚═╝  ╚═╝
-->

<div align="center">
  <h1>Rawan Abdelkader</h1>
  <h3>Digital IC Design & Verification Engineer</h3>
  
  <p>
    <strong>GP Sponsored by Analog Devices</strong> • E-JUST S'27 • Senior Year
  </p>
  
  <div style="background:#000;color:#0f0;font-family:monospace;border:1px solid #444;padding:16px;border-radius:4px;text-align:left;display:inline-block;margin:20px 0;max-width:800px">
    ┌─────────────────────────────────────────────────────┐
    │  Digital IC Design & Verification Engineer          │
    │  Focused on:                                      │
    │  • UVM/cocotb verification                        │
    │  • Hardware accelerators for ML                   │
    │  • RTL design (Verilog/SystemVerilog)             │
    │  • EDA tools: QuestaSim, Vivado, Quartus          │
    └─────────────────────────────────────────────────────┘
    Hardware doesn't lie. Verification proves it.
  </div>
</div>

<div align="center">
  <hr style="border:0;border-top:1px solid #444;margin:30px auto;width:80%">
</div>

<h2 align="center">🔍 Technical Expertise</h2>

<div align="center">
  <table align="center" style="margin:20px auto;width:80%;border-collapse:collapse">
    <tr>
      <td style="padding:15px;border:1px solid #ddd;text-align:center;vertical-align:top">
        <strong>RTL Design</strong><br/>
        <span style="color:#555">Verilog • SystemVerilog • RISC-V</span><br/>
        <span style="color:#555">Pipelined datapaths • FIFOs • FSMs</span>
      </td>
      <td style="padding:15px;border:1px solid #ddd;text-align:center;vertical-align:top">
        <strong>Verification</strong><br/>
        <span style="color:#555">UVM • cocotb • constrained-random</span><br/>
        <span style="color:#555">Coverage-driven • Scoreboards • Assertions</span>
      </td>
      <td style="padding:15px;border:1px solid #ddd;text-align:center;vertical-align:top">
        <strong>Tools</strong><br/>
        <span style="color:#555">QuestaSim • Vivado • Quartus Prime</span><br/>
        <span style="color:#555">Linux CLI • Git • MATLAB</span>
      </td>
    </tr>
  </table>
</div>

<div align="center">
  <hr style="border:0;border-top:1px solid #444;margin:30px auto;width:80%">
</div>

<h2 align="center">🧪 Current Work: ML Accelerator Verification</h2>

<div align="center">
  <div style="background:#1e1f29;color:#88c0d0;font-family:monospace;font-size:14px;border-radius:6px;padding:20px;width:80%;text-align:left;overflow-x:auto">
    <div style="color:#81a1c1">// UVM testbench structure</div>
    <div style="color:#d8dee9">class</div> <div style="color:#8fbcbb">ml_accelerator_test</div> <div style="color:#d8dee9">extends</div> <div style="color:#8fbcbb">uvm_test</div>;
      <div style="color:#d8dee9">ml_accelerator_env</div> <div style="color:#8fbcbb">env</div>;
      
      <div style="color:#d8dee9">virtual</div> <div style="color:#81a1c1">function</div> <div style="color:#d8dee9">void</div> <div style="color:#8fbcbb">build_phase</div>(<div style="color:#d8dee9">uvm_phase phase</div>);
        <div style="color:#d8dee9">super.build_phase</div>(phase);
        <div style="color:#8fbcbb">env</div> = <div style="color:#d8dee9">ml_accelerator_env</div>::<div style="color:#8fbcbb">type_id</div>::<div style="color:#d8dee9">create</div>("env", <div style="color:#d8dee9">this</div>);
      <div style="color:#81a1c1">endfunction</div>
      
      <div style="color:#d8dee9">virtual</div> <div style="color:#81a1c1">task</div> <div style="color:#8fbcbb">run_phase</div>(<div style="color:#d8dee9">uvm_phase phase</div>);
        <div style="color:#d8dee9">phase.raise_objection</div>(<div style="color:#d8dee9">this</div>);
        <div style="color:#8fbcbb">env</div>.<div style="color:#8fbcbb">run_test</div>();
        <div style="color:#d8dee9">#1000</div>;
        <div style="color:#d8dee9">phase.drop_objection</div>(<div style="color:#d8dee9">this</div>);
      <div style="color:#81a1c1">endtask</div>
    <div style="color:#d8dee9">endclass</div>
  </div>
</div>

<div align="center">
  <hr style="border:0;border-top:1px solid #444;margin:30px auto;width:80%">
</div>

<h2 align="center">🎓 Academic & Industry</h2>

<div align="center" style="max-width:800px;margin:0 auto;text-align:left;font-family:monospace">
  <p>
    <strong>Electronics & Communication Engineering</strong><br/>
    Egypt-Japan University of Science and Technology (E-JUST)<br/>
    Expected Graduation: 2027
  </p>
  
  <p>
    <strong>Industry Sponsorship</strong><br/>
    🎓 GP Program — <strong>Analog Devices</strong><br/>
    <em>Hands-on exposure to mixed-signal verification methodologies and silicon validation flows</em>
  </p>
</div>

<div align="center">
  <hr style="border:0;border-top:1px solid #444;margin:30px auto;width:80%">
</div>

<h2 align="center">💡 Engineering Mindset</h2>

<div align="center" style="max-width:800px;margin:0 auto;font-style:italic;font-family:monospace;color:#555">
  "Verification isn't just about finding bugs—it's about proving correctness under all corner cases."<br/><br/>
  • Strong C++/Python fundamentals for testbench automation<br/>
  • Obsessed with coverage closure and bug hunting<br/>
  • Hardware accelerators are the future of efficient ML
</div>

<div align="center">
  <hr style="border:0;border-top:1px solid #444;margin:30px auto;width:80%">
</div>

<h2 align="center">📫 Let's Connect</h2>

<div align="center" style="margin:20px 0">
  <a href="https://www.linkedin.com/in/yourprofile" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" style="margin:0 5px">
  </a>
  <a href="https://www.analog.com/" target="_blank">
    <img src="https://img.shields.io/badge/Analog%20Devices-FF0000?style=flat&logo=analogdevices&logoColor=white" alt="Analog Devices" style="margin:0 5px">
  </a>
</div>

<div align="center" style="font-family:monospace;color:#777;margin-top:10px">
  Open to design/verification internships & hardware accelerator research opportunities
</div>

<div align="center">
  <hr style="border:0;border-top:1px solid #444;margin:30px auto;width:80%">
</div>

<div align="center" style="font-family:monospace;color:#777;font-size:14px">
  <div style="background:#000;color:#0f0;padding:12px;border-radius:4px;display:inline-block;margin:15px 0;width:80%">
$ git log --author="Rawan" --oneline | head -5<br/>
a1b2c3d fix: resolved metastability in async FIFO handshake<br/>
e4f5g6h feat: added coverage groups for ALU corner cases<br/>
i7j8k9l docs: verification plan for ML accelerator core<br/>
m0n1o2p perf: 23% latency reduction in MAC pipeline<br/>
q3r4s5t init: UVM environment for signed multiplier DUT
  </div>
</div>

<div align="center" style="margin-top:30px;color:#777;font-family:monospace;font-size:13px">
  <!-- Profile views -->
  <img src="https://komarev.com/ghpvc/?username=RawanAbdelkader272&color=blueviolet" alt="Profile views" />
  <br/><br/>
  Digital IC Design & Verification Engineer • E-JUST • Analog Devices GP
</div>
