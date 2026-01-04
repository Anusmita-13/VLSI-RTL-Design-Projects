💡 **RTL Design & Synthesis using Open-Source EDA Tools** 

This repository demonstrates my hands-on experience with RTL design, functional verification, waveform analysis, and logic synthesis using industry-relevant open-source VLSI tools.
The projects focus on building strong fundamentals in digital design and hardware description using Verilog, following a complete RTL-to-netlist flow.

🔧 **Tools & Technologies**

•  **Verilog HDL** – RTL design and testbench development

•	**Icarus Verilog** – Compilation and simulation

•	**GTKWave** – Signal waveform visualization and debugging

•  **Yosys** – RTL synthesis and gate-level netlist generation

•	**Graphviz / xdot** – Logic-level schematic visualization

•	**Linux (Ubuntu)** – Command-line based design flow

📂 **Repository Structure**

Each module ( e.g. ALU, MUX, Gates, Counter, etc.) is located in its own folder and contains:

•	**module.v**: Verilog RTL code

•	**module_tb.v**: Testbench

•	**module.vcd**: Output waveform from Icarus + Gtkwave simulation

•	**waveform.png**: GTKWave screenshot

•	**module.ys**: Yosys synthesis script

•	**module_synth.v**: Gate-level netlist

•	**module.blif**: Logic netlist format

•	**module.json**: JSON netlist (for OpenROAD/backend)

•	**module_yosys_show.png**: Gate-level logic schematic (Yosys show)

🧩 **Designs Implemented**

The repository includes a variety of foundational digital blocks, such as:

•	Basic logic gates

•	Multiplexers (2:1, 4:1)

•	Adders (Half Adder, Full Adder)

•	Arithmetic Logic Units 

•	Counters and flip-flops

•	Comparators and supporting combinational logic

Each module is implemented with:

•	Clean RTL coding style

•	Separate and readable testbenches

•	Proper waveform dumping

•	Successful synthesis using Yosys

🔄 **Design Flow Followed**

For every module, the following industry-standard flow is applied:

1.	**RTL Design**
   
👉Modular, synthesizable Verilog

👉Parameterized where applicable

2.	**Functional Verification**
   
👉Testbench-driven simulation

👉Verification through GTKWave signal analysis

3.	**Synthesis**
   
👉RTL elaboration using Yosys

👉Generation of gate-level netlists and logic representations

This demonstrates an understanding of how RTL translates into actual hardware logic.

🎯 **Skills Demonstrated**

✅RTL coding best practices in Verilog

✅Writing meaningful and structured testbenches

✅Debugging designs using waveform analysis

✅Understanding of synthesis concepts and netlist generation

✅Familiarity with Linux-based VLSI workflows

✅End-to-end digital design execution using open-source tools

💻 **About This Repository**

This repository reflects my practical learning and implementation of digital design concepts, beyond theory.
All designs are written, simulated, and synthesized manually, ensuring clarity on how hardware behaves at both RTL and gate levels.

📇 **Contact**

📧Email:anusmitadasgupta1305@gmail.com

🔗Linkedin: www.linkedin.com/in/anusmita-dasgupta







