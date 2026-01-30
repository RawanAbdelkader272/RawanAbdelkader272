<div align="center">

<pre style="font-family:monospace; line-height:1.5; color:#00f000; background-color:#0d1117; padding:15px; border-radius:10px; text-align:left; border: 1px solid #30363d;">
clk      _|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_|_
rst_n    _________________________________________________________________________
         
data_out <font color="#58a6ff">====&lt; R A W A N &gt;====================&lt; A B D E L K A D E R &gt;====</font>
status   <font color="#FFD700">      [Design Valid]                  [Verification Coverage: 100%]     </font>
</pre>

[![Analog Devices](https://img.shields.io/badge/Analog%20Devices-FF0000?style=for-the-badge&logo=analogdevices&logoColor=white)](https://www.analog.com/)
[![E-JUST](https://img.shields.io/badge/E--JUST-004080?style=for-the-badge&logo=education&logoColor=white)](https://www.ejust.edu.eg/)

<div style="background:linear-gradient(135deg,#1a2a6c,#2c3e50,#4a00e0); border-radius:16px; padding:30px; margin:20px 0; color:white; width:95%; max-width:900px; box-shadow: 0 10px 30px rgba(0,0,0,0.5);">
  <h1 style="margin:0; color:#00f3ff; text-shadow:0 0 10px rgba(0,243,255,0.5); font-family:sans-serif;">Rawan Abdelkader</h1>
  <h3 style="margin:10px 0; color:#ff6b6b; font-weight:300; font-family:sans-serif;">Digital IC Design & Verification Engineer</h3>
  <p style="margin:15px 0 0; font-size:18px; font-family:sans-serif;">
    <span style="background:rgba(255,204,0,0.2); padding:6px 15px; border-radius:20px; border: 1px solid #ffcc00; color:#ffcc00"><strong>Analog Devices</strong> GP Fellow</span>
    &nbsp; • &nbsp; E-JUST S'27 &nbsp; • &nbsp; Senior Year
  </p>
</div>

<div style="background:#0f172a; border:1px solid #30363d; border-radius:16px; padding:25px; width:95%; max-width:900px; margin:25px 0">
  <div style="display:grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap:20px;">
    
    <div style="background:#1e293b; border:1px solid #8b5cf6; border-radius:12px; padding:20px; text-align:center">
      <div style="font-size:32px; margin-bottom:10px">⚙️</div>
      <div style="font-weight:bold; color:#8b5cf6; margin-bottom:8px; letter-spacing:1px">RTL DESIGN</div>
      <div style="color:#cbd5e1; font-size:14px; line-height:1.5">Verilog • SystemVerilog<br/>Pipelined Datapaths • FSMs</div>
    </div>
    
    <div style="background:#1e293b; border:1px solid #ef4444; border-radius:12px; padding:20px; text-align:center">
      <div style="font-size:32px; margin-bottom:10px">✅</div>
      <div style="font-weight:bold; color:#ef4444; margin-bottom:8px; letter-spacing:1px">VERIFICATION</div>
      <div style="color:#cbd5e1; font-size:14px; line-height:1.5">UVM Frameworks • cocotb<br/>Coverage-Driven (CDV)</div>
    </div>
    
    <div style="background:#1e293b; border:1px solid #10b981; border-radius:12px; padding:20px; text-align:center">
      <div style="font-size:32px; margin-bottom:10px">🚀</div>
      <div style="font-weight:bold; color:#10b981; margin-bottom:8px; letter-spacing:1px">ACCELERATION</div>
      <div style="color:#cbd5e1; font-size:14px; line-height:1.5">ML Kernels • Systolic Arrays<br/>PPA Optimization</div>
    </div>
    
    <div style="background:#1e293b; border:1px solid #f59e0b; border-radius:12px; padding:20px; text-align:center">
      <div style="font-size:32px; margin-bottom:10px">🛠️</div>
      <div style="font-weight:bold; color:#f59e0b; margin-bottom:8px; letter-spacing:1px">EDA TOOLS</div>
      <div style="color:#cbd5e1; font-size:14px; line-height:1.5">QuestaSim • Vivado<br/>Quartus • Linux CLI</div>
    </div>
  </div>
  
  <div style="text-align:center; margin-top:25px; color:#94a3b8; font-style:italic; font-family:serif">
    "Silicon is poetry written in transistors — I verify every stanza."
  </div>
</div>

<div style="background:#0d1117; border-left:4px solid #8b5cf6; border-radius:8px; padding:20px; width:95%; max-width:900px; margin:25px 0; text-align:left; font-family:monospace; box-shadow: inset 0 0 10px rgba(0,0,0,0.5);">
  <div style="color:#64748b; margin-bottom:12px">// ml_accelerator_uvm_test.sv</div>
  <span style="color:#f87171">class</span> <span style="color:#38bdf8">ml_accel_coverage</span> <span style="color:#f87171">extends</span> <span style="color:#38bdf8">uvm_subscriber</span>;
    <span style="color:#f87171">covergroup</span> <span style="color:#38bdf8">cg</span>;
      <span style="color:#10b981">// Target: 100% Functional Coverage for ADI Sponsored GP</span>
      <span style="color:#f1f5f9">weight_cp: </span><span style="color:#f87171">coverpoint</span> <span style="color:#f1f5f9">tr.weight {</span>
        <span style="color:#f87171">bins</span> <span style="color:#f1f5f9">legal = {[-128:127]};</span>
      <span style="color:#f1f5f9">}</span>
    <span style="color:#f87171">endgroup</span>
  <span style="color:#f87171">endclass</span>
</div>

<div style="width:95%; max-width:900px; margin:20px 0;">
  <p align="center">
    <img width="48%" src="https://github-readme-stats.vercel.app/api?username=RawanAbdelkader272&show_icons=true&theme=tokyonight&count_private=true&border_radius=10" />
    <img width="48%" src="https://github-readme-streak-stats.herokuapp.com/?user=RawanAbdelkader272&theme=tokyonight&border_radius=10" />
  </p>
</div>

<div style="background:linear-gradient(135deg,#0f172a,#1e293b); border-radius:16px; padding:30px; width:95%; max-width:900px; margin:30px 0; border: 1px solid #30363d;">
  <h3 style="color:#38bdf8; margin-top:0; font-family:sans-serif;">Let's Build Verified Silicon Together</h3>
  <div style="margin-top:20px">
    <a href="https://www.linkedin.com/in/rawan-abdelkader-28a8092b2" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
    </a>
    <a href="mailto:rawan.abdelkader2722@gmail.com" target="_blank">
      <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
    </a>
  </div>
  <div style="margin-top:20px; font-family:monospace; color:#10b981;">
    <span style="color:#8b5cf6">rawan@ejust:~$</span> sample_and_hold --success
  </div>
</div>

<img src="https://komarev.com/ghpvc/?username=RawanAbdelkader272&color=00f3ff&style=flat-square&label=CHIP_VISITS" alt="Profile views" />

</div>
