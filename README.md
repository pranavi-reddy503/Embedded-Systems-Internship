<h1 align="center">Embedded Systems & Microcontroller Internship</h1>
<p align="center"><strong>"The journey from knowing to understanding"</strong></p>

---

<h2> Table of Contents</h2>
<ul>
  <li><a href="#hardware-section">1. Hardware Section</a></li>
  <li><a href="#software-section">2. Software Section</a></li>
  <li><a href="#microcontroller-section">3. 8051 Microcontroller Section</a></li>
  <li><a href="#mini-project">4. Mini Project: Round-Robin Traffic Signal</a></li>
  <li><a href="#gallery">5. Internship Gallery</a></li>
  <li><a href="#presentation">6. Internship PPT</a></li>
  <li><a href="#certificate">7. Internship Certificate</a></li>
</ul>

---

<h2 id="hardware-section"> 1. Hardware Section</h2>
<p>Hands-on development starting from foundational power electronics to modular circuit design and hardware testing.</p>

<table width="100%">
  <tr>
    <th width="40%">Task / Step Description</th>
    <th width="40%">Key Learning & Testing Methods</th>
    <th width="20%">Execution Media-Photo</th>
    <th width="20%">Execution Media-Video</th>
  </tr>
  <tr>
    <td><b>Power Supply Design & Soldering</b></td>
    <td>Designed a stable power supply board and verified output voltages using a digital multimeter.</td>
    <td><a href="https://drive.google.com/file/d/1v834PPZ-4BRlP0YKmQZ-3DX5124yJeRE/view?usp=sharing" target="_blank">View Photo</a></td>
    <td><a href="https://drive.google.com/file/d/1EXgSh5Y19Xiy4fUV1AiPObD1VE_b49Kw/view?usp=sharing" target="_blank">View Video</a></td>
  </tr>
  <tr>
    <td><b>LED Breakout Board Testing</b></td>
    <td>Validated custom LED breakout board functionality utilizing our newly constructed power supply.</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/1-0xeh0fBfODWQqK5j-atnbAHsBJH2Yoi/view?usp=sharing" target="_blank">View Video</a></td>
  </tr>
  <tr>
    <td><b>Switch Breakout Board</b></td>
    <td>Designed, soldered, and interface-tested our custom switch breakout board with the LED board.</td>
    <td><a href="https://drive.google.com/file/d/1wJ-EvX5wBwXF_Wgt27J1-c3K5EM-z1BL/view?usp=sharing" target="_blank">View Photo</a></td>
    <td><a href="https://drive.google.com/file/d/1wTD2YTU64vry8FrjzploI-m7EH4Ija3v/view?usp=sharing" target="_blank">View Video</a></td>
  </tr>
  <tr>
    <td><b>Relay Module Integration</b></td>
    <td>Integrated a relay module into the switch board to study isolated switching activity and high-power load handling.</td>
    <td></td>
    <td><a href="https://drive.google.com/file/d/1zFNQhPTuZRsg7KpDzxpcHSxrAtVtFLzA/view?usp=sharing" target="_blank">View Video</a></td>
  </tr>
</table>

---

<h2 id="software-section"> 2. Software Section (Simulation Showcase)</h2>
<p>Extensive simulation and firmware verification utilizing <b>Keil uVision</b> for compilation and <b>Proteus Design Suite</b> for hardware emulation. Below are the verified video demonstrations of the compiled logic scripts:</p>

<table width="100%">
  <tr>
    <th width="10%">S.No</th>
    <th width="65%">Experiment / LED Pattern Programmed</th>
    <th width="25%">Simulation Output</th>
  </tr>
  <tr><td>1</td><td>Blinking of a single LED</td><td><a href="https://drive.google.com/file/d/1lvuIca8w8DK1wZKhiejNy2g_0ZSuLFqB/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
  <tr><td>2</td><td>Blinking of all LEDs simultaneously</td><td><a href="https://drive.google.com/file/d/1YDTSoLhiDXszth9LQatrIYrxl6MxCp9N/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
  <tr><td>3</td><td>Blinking of even-positioned LEDs</td><td><a href="https://drive.google.com/file/d/1fuhsCEPvgQAeYnLJInVBsRSJ4xGYZTto/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
  <tr><td>4</td><td>Blinking of odd-positioned LEDs</td><td><a href="https://drive.google.com/file/d/1CxdC42MlUNh7LBqqdoagAj0OVLa1Zxt6/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
  <tr><td>5</td><td>Blinking pattern: Bottom to Top sequence</td><td><a href="https://drive.google.com/file/d/11TLCpTqVxjaSbmJ_8zknigUd4bD7BjhK/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
  <tr><td>6</td><td>Blinking pattern: Top to Bottom sequence</td><td><a href="https://drive.google.com/file/d/19aJDiI5SRuObTA07Uh8XJ3G7O7_5u4B-/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
  <tr><td>7</td><td>Scrolling LED effect: Left to Right</td><td><a href="https://drive.google.com/file/d/1RGzoESISC6c0Qh02JVKEWhneLwZvMAQ7/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
  <tr><td>8</td><td>Scrolling LED effect: Right to Left</td><td><a href="https://drive.google.com/file/d/1_46q9LYy1CK7KI2XCkEHBc2ljJmjhZz6/view?usp=sharing" target="_blank">Watch Video</a></td></tr>
</table>

---

<h2 id="microcontroller-section"> 3. 8051 Microcontroller Section</h2>
<p>Transitioned from standalone simulation to physical hardware execution. Programmed the 8051 microcontroller using <b>Keil</b> and <b>Programiz</b> platforms to interface with our custom switch breakout board.</p>
<ul>
  <li><b>Logic Configuration:</b> Active-Low hardware implementation.</li>
  <li><b>Operation:</b> Dynamic hardware-level LED response patterns dictated by real-time manual inputs via a 3-bit switch configuration.</li>
</ul>

<h3>Switch Input to LED Pattern Mapping:</h3>
<ul>
  <li><code>000</code> &mdash; Glow lower four LEDs</li>
  <li><code>001</code> &mdash; Glow upper four LEDs</li>
  <li><code>010</code> &mdash; Even-positioned LEDs blinking</li>
  <li><code>011</code> &mdash; Odd-positioned LEDs blinking</li>
  <li><code>100</code> &mdash; Left scrolling sequence</li>
  <li><code>101</code> &mdash; Right scrolling sequence</li>
  <li><code>110</code> &mdash; Out-to-Middle pattern transition</li>
  <li><code>111</code> &mdash; Middle-to-Out pattern transition</li>
</ul>

<p>🔗 <a href="https://drive.google.com/file/d/1jRxQ0am1ryG0hQSkSxwVK3x2ptCNgh6H/view?usp=sharing" target="_blank"><b>Watch Hardware Execution Video</b></a></p>

---

<h2 id="mini-project"> 4. Mini Project: Round-Robin Traffic Signal</h2>
<p>Implemented a functional multi-junction traffic signaling system based on the <b>Round-Robin scheduling flow model</b> controlled entirely via the 8051 architecture.</p>

<h3>Core Logic & Timing Design:</h3>
<ul>
  <li><b>Interjunction Safety Interlocking:</b> Programmed the controller to guarantee strict lane isolation &mdash; whenever one lane transitions to <b>Green</b>, all remaining lanes are explicitly forced to <b>Red</b> to prevent collision paths.</li>
  <li><b>Asymmetric Delay Sequences:</b> Implemented accurate timing intervals where the transitional <b>Yellow</b> clearance delay is significantly shorter compared to the main <b>Green</b> (active flow) and <b>Red</b> (hold) timing windows, accurately mimicking real-world traffic patterns.</li>
</ul>

<p>🔗 <a href="https://drive.google.com/file/d/1p_N67e-ppAFT6HHRXQDMSfHrc3QRTob3/view?usp=sharing" target="_blank"><b>Watch Project Demonstration Video</b></a></p>

---

<h2 id="gallery"> 5. Internship Gallery</h2>
<p>A glimpse into our daily learning environment, practical lab infrastructure, and guidance sessions with our mentors.</p>
<blockquote>
   <a href="https://drive.google.com/drive/folders/1xXyrEClXn9fhqc26tY9dqtcwzKZvTjme?usp=sharing" target="_blank"><b>Access Full Internship Media Album (Google Drive)</b></a>
</blockquote>

---

<h2 id="presentation"> 6. Internship Presentation (PPT)</h2>
<p>The definitive technical slide deck summarizing our methodology, circuit schematics, project execution milestone details, and final learning outcomes.</p>
<blockquote>
   <a href="https://docs.google.com/presentation/d/1VeTmZWyd8dZEtODHRlj_ONgwgtSf3oK_/edit?usp=sharing&ouid=105477366807246064737&rtpof=true&sd=true" target="_blank"><b>View Internship PPT</b></a>
</blockquote>

---

<h2 id="certificate"> 7. Internship Certificate</h2>
<p>Credential awarded upon successful completion of the internship requirements, practical hardware evaluations, and project milestones.</p>

<p align="center">
  <a href="https://drive.google.com/file/d/1P9fjeMZ672lMdvp944bG4MK_WrZp0sds/view?usp=sharing" target="_blank">
    <img src="certificate.png" alt="Official Internship Certificate" width="75%" style="border: 1px solid #ddd; border-radius: 6px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  </a>
</p>

<p align="center">
  🔗 <b><a href="https://drive.google.com/file/d/1P9fjeMZ672lMdvp944bG4MK_WrZp0sds/view?usp=sharing" target="_blank">Verify Official Internship Certificate</a></b>
</p>
