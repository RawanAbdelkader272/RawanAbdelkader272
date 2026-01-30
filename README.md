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
  ╔═══════════════════════════════════════════════════════════════════════════════╗
  ║  RAWAN ABDELKADER • Digital Silicon Artist                                   ║
  ║  Crafting verified silicon for ML acceleration • Analog Devices GP Fellow    ║
  ╚═══════════════════════════════════════════════════════════════════════════════╝
-->

<div align="center">

  <!-- Hero banner with gradient -->
  <div style="background:linear-gradient(135deg,#1a2a6c,#2c3e50,#4a00e0);border-radius:16px;padding:24px;margin:20px 0;color:white;width:90%;max-width:900px">
    <h1 style="margin:0;color:#00f3ff;text-shadow:0 0 10px rgba(0,243,255,0.5)">Rawan Abdelkader</h1>
    <h3 style="margin:8px 0 0;color:#ff6b6b;font-weight:300">Digital IC Design & Verification Engineer</h3>
    <p style="margin:12px 0 0;font-size:18px">
      <span style="background:rgba(0,0,0,0.2);padding:4px 12px;border-radius:20px">GP Fellow @ <strong style="color:#ffcc00">Analog Devices</strong></span>
      • E-JUST S'27 • Senior Year
    </p>
  </div>

  <!-- Silicon floorplan visualization -->
  <div style="background:#0f172a;border:2px solid #38bdf8;border-radius:16px;padding:24px;width:90%;max-width:900px;margin:25px 0">
    <div style="display:flex;justify-content:center;gap:16px;flex-wrap:wrap">
      
      <!-- Core 1: Design -->
      <div style="background:#1e293b;border:2px solid #8b5cf6;border-radius:12px;padding:16px;width:180px;text-align:center">
        <div style="font-size:48px;margin-bottom:8px">⚙️</div>
        <div style="font-weight:bold;color:#64748b;margin-bottom:4px">RTL DESIGN</div>
        <div style="color:#cbd5e1;font-size:14px">Verilog • SystemVerilog<br/>Pipelining • FSMs</div>
      </div>
      
      <!-- Core 2: Verification -->
      <div style="background:#1e293b;border:2px solid #ef4444;border-radius:12px;padding:16px;width:180px;text-align:center">
        <div style="font-size:48px;margin-bottom:8px">✅</div>
        <div style="font-weight:bold;color:#64748b;margin-bottom:4px">VERIFICATION</div>
        <div style="color:#cbd5e1;font-size:14px">UVM • cocotb<br/>Coverage-driven</div>
      </div>
      
      <!-- Core 3: Acceleration -->
      <div style="background:#1e293b;border:2px solid #10b981;border-radius:12px;padding:16px;width:180px;text-align:center">
        <div style="font-size:48px;margin-bottom:8px">🚀</div>
        <div style="font-weight:bold;color:#64748b;margin-bottom:4px">HW ACCELERATION</div>
        <div style="color:#cbd5e1;font-size:14px">ML kernels • Systolic<br/>PPA optimization</div>
      </div>
      
      <!-- Core 4: Tools -->
      <div style="background:#1e293b;border:2px solid #f59e0b;border-radius:12px;padding:16px;width:180px;text-align:center">
        <div style="font-size:48px;margin-bottom:8px">🛠️</div>
        <div style="font-weight:bold;color:#64748b;margin-bottom:4px">EDA ECOSYSTEM</div>
        <div style="color:#cbd5e1;font-size:14px">QuestaSim • Vivado<br/>Quartus • Linux</div>
      </div>
      
    </div>
    
    <div style="text-align:center;margin-top:20px;color:#94a3b8;font-style:italic">
      "Silicon is poetry written in transistors — I verify every stanza"
    </div>
  </div>

  <!-- Code snippet with vibrant syntax highlighting -->
  <div style="background:#0f172a;border-left:4px solid #8b5cf6;border-radius:8px;padding:20px;width:90%;max-width:900px;margin:25px 0;font-family:monospace">
    <div style="color:#64748b;margin-bottom:12px">// ml_accelerator_tb.sv — UVM testbench with coverage closure</div>
    <div style="color:#f87171">class</div> <span style="color:#38bdf8">ml_accel_coverage</span> <span style="color:#f87171">extends</span> <span style="color:#38bdf8">uvm_subscriber</span><span style="color:#f1f5f9"> #(transaction)</span>;
      <span style="color:#f87171">covergroup</span> <span style="color:#38bdf8">cg</span> <span style="color:#f1f5f9">@sample;</span>
        <span style="color:#10b981">// Cover corner cases for ML inference</span>
        <span style="color:#f87171">weight_dist</span>: <span style="color:#f1f5f9">coverpoint</span> <span style="color:#f1f5f9">tr.weight</span> {
          <span style="color:#f1f5f9">bins</span> <span style="color:#f1f5f9">small</span> <span style="color:#f1f5f9">=</span> {<span style="color:#fbbf24">-8</span>, <span style="color:#fbbf24">-4</span>, <span style="color:#fbbf24">0</span>, <span style="color:#fbbf24">4</span>, <span style="color:#fbbf24">8</span>};
          <span style="color:#f1f5f9">bins</span> <span style="color:#f1f5f9">large</span> <span style="color:#f1f5f9">=</span> {<span style="color:#fbbf24">-128</span>, <span style="color:#fbbf24">127</span>};
        }
        <span style="color:#f1f5f9">cross</span> <span style="color:#f1f5f9">weight_dist</span>, <span style="color:#f1f5f9">input_dist</span>;
      <span style="color:#f87171">endgroup</span>
    <span style="color:#f87171">endclass</span>
  </div>

  <!-- Academic & Sponsorship -->
  <div style="display:flex;align-items:center;justify-content:center;gap:30px;width:90%;max-width:900px;margin:30px 0;background:#0f172a;border-radius:16px;padding:20px">
    <div style="text-align:center">
      <div style="font-weight:bold;font-size:20px;color:#38bdf8">🎓 E-JUST</div>
      <div style="color:#94a3b8;margin-top:4px">Electronics & Comm. Eng.</div>
      <div style="color:#64748b;font-size:14px;margin-top:2px">Expected 2027</div>
    </div>
    <div style="font-size:32px">⚡</div>
    <div style="text-align:center">
      <div style="font-weight:bold;font-size:20px;color:#ffcc00">🔬 Analog Devices</div>
      <div style="color:#94a3b8;margin-top:4px">GP Fellowship</div>
      <div style="color:#64748b;font-size:14px;margin-top:2px">Silicon Validation</div>
    </div>
  </div>

  <!-- Call to action -->
  <div style="background:linear-gradient(135deg,#0f172a,#1e293b);border-radius:16px;padding:25px;width:90%;max-width:900px;margin:30px 0">
    <h3 style="color:#38bdf8;margin-top:0">Let's Build Verified Silicon Together</h3>
    <p style="color:#cbd5e1;margin:15px 0">
      Open to verification internships • ML accelerator research • RISC-V projects • Open-source hardware
    </p>
    <div style="margin-top:20px">
      <a href="https://www.linkedin.com/in/yourprofile" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&color=0077B5" alt="LinkedIn">
      </a>
      <a href="mailto:your.email@example.com" target="_blank">
        <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white&color=EF4444" alt="Email">
      </a>
    </div>
  </div>

  <!-- Terminal signature -->
  <div style="color:#64748b;font-family:monospace;font-size:14px;margin:30px 0;width:90%;max-width:900px">
    <div style="background:#0a0f1d;padding:12px;border-radius:8px;display:inline-block">
      <span style="color:#10b981">$</span> <span style="color:#38bdf8">whoami</span><br/>
      <span style="color:#f87171">Digital IC Engineer</span> • E-JUST S'27 • <span style="color:#fbbf24">Analog Devices GP Fellow</span>
    </div>
  </div>

  <!-- Profile views -->
  <img src="https://komarev.com/ghpvc/?username=RawanAbdelkader272&color=blueviolet&style=flat" alt="Profile views" />

</div>

<!--
  ╔═══════════════════════════════════════════════════════════════════════════════╗
  ║  This profile renders perfectly on GitHub • No external CSS • Mobile-friendly ║
  ║  Inspired by silicon floorplans • Designed for verification engineers         ║
  ╚═══════════════════════════════════════════════════════════════════════════════╝
-->
