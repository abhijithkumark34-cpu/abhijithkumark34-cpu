�

�

�

�

██╗  ██╗ █████╗ ██████╗ ██████╗ ██╗      ██╗ ██╗████████╗██╗  ██╗
██║  ██║██╔══██╗██╔══██╗██╔══██╗██║      ██║ ██║╚══██╔══╝██║  ██║
███████║███████║██████╔╝██║  ██║██║█████╗██║ ██║   ██║   ███████║
██╔══██║██╔══██║██╔══██╗██║  ██║██║╚════╝██║ ██║   ██║   ██╔══██║
██║  ██║██║  ██║██║  ██║██████╔╝███████╗ ╚█████╔╝  ██║   ██║  ██║
╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝ ╚══════╝  ╚════╝   ╚═╝   ╚═╝  ╚═╝
⚡ ABHIJITH
[ Bridging Software ↔ Hardware ]
Digital · Analog · FPGA · CPU Architecture · Edge AI
�


🧠 CPU builder mindset — thinking in registers, gates, and clock cycles
🔬 System-level thinker — from transistors to intelligent systems
⚡ Circuit-to-AI engineer — where electrons meet algorithms
�


�
Load image
�

�

�

�

�

╔══════════════════════════════════════════════════════════════════╗
║          ⚡  LIVE SYSTEM ARCHITECTURE VISUALIZATION  ⚡          ║
╠══════════════════════════════════════════════════════════════════╣
║                                                                  ║
║   [ANALOG IN] ──┐                                                ║
║   ~~~∿∿∿∿∿~~~   │                                                ║
║   Signal Flow   ├──► [ADC] ──► [DIGITAL CORE] ──► [OUTPUT]      ║
║                 │        ↑           │                           ║
║   [SENSOR]  ───┘         │           ▼                           ║
║                      [CLOCK]    [REGISTER FILE]                  ║
║                      ⏱️ Tick      R0 ████████ 0xFF              ║
║                                  R1 ████░░░░ 0xA3              ║
║                                  R2 ░░░░░░░░ 0x00              ║
║                                       │                          ║
║   ┌───────────────────────────────────┘                          ║
║   │          FPGA FABRIC                                         ║
║   │   ┌──────┐  ┌──────┐  ┌──────┐  ┌──────┐                   ║
║   └──►│ LUT  │──│ LUT  │──│  FF  │──│ LUT  │──►                ║
║       └──────┘  └──────┘  └──────┘  └──────┘                   ║
║          ▲         ▲         ▲         ▲                         ║
║       ~~~●~~~~~~~~~●~~~~~~~~~●~~~~~~~~~●~~~ current flow ⚡       ║
║                                                                  ║
║   [ALU]  ──► [CONTROL UNIT] ──► [EDGE AI INFERENCE ENGINE]      ║
║    ADD         FSM States           Neural Network Weights       ║
║    SUB         ┌─┐┌─┐┌─┐           ████▓▓▒▒░░ → Prediction      ║
║    AND         └─┘└─┘└─┘                                         ║
║                                                                  ║
╚══════════════════════════════════════════════════════════════════╝
�

�

�

�

�

�
�
�
�
Load image
Load image
Load image
Load image
�

�

�

�

🖥️ < About Me />
const ABHIJITH = {

  role        : "Hybrid Hardware-Software Engineer",
  status      : "Engineering Student | Builder | Explorer",

  identity    : [
    "Circuit designer who writes code",
    "Software thinker who builds hardware",
    "System architect from gate-level to AI"
  ],

  domains     : [
    "Digital Electronics",
    "Analog Electronics",
    "FPGA Design",
    "CPU Architecture",
    "Edge AI Systems"
  ],

  languages   : {
    hardware  : [ "Verilog", "VHDL" ],
    software  : [ "C", "Python" ],
    scripting : [ "Bash", "MATLAB" ]
  },

  tools       : [
    "Raspberry Pi",     // Edge compute + prototyping
    "Arduino IDE",      // Embedded rapid development
    "MATLAB",           // Signal analysis + simulation
    "ModelSim",         // HDL simulation & verification
    "Git",              // Version control
    "Linux",            // Native dev environment
    "VS Code"           // Code editor
  ],

  currentLearning : [
    "Flip-Flop design & timing analysis",
    "Finite State Machines (FSM)",
    "RTL Design & synthesis",
    "Analog circuit design",
    "Edge AI & TinyML deployment"
  ],

  flagshipProject : {
    name        : "Hybrid CPU",
    description : "FPGA-based control logic + External Hardware ALU",
    bridge      : "Physical circuits ↔ Programmable logic"
  },

  vision      : "Circuits  →  Systems  →  Intelligence",

  currentlyBuilding : () => "The future, one gate at a time ⚡"

};
�

�

�

⚙️ Tech Arsenal
�

💻 Programming Languages
�
�
Load image
Load image
🔷 Digital Design
�
�
�
Load image
Load image
Load image
📡 Analog Electronics
�
�
�
Load image
Load image
Load image
🤖 Edge AI
�
�
�
Load image
Load image
Load image
🛠️ Hardware Platforms
�
�
Load image
Load image
🔧 Tools & Software
�
�
�
�
�
Load image
Load image
Load image
Load image
Load image
🚀 Future Stack — Semiconductor & VLSI Roadmap
[ ACTIVELY LEARNING / NEXT ON THE MAP ]
�
�
�
�
�
�
�
�
�
�
Load image
Load image
Load image
Load image
Load image
Load image
Load image
Load image
Load image
Load image
�

�

�

�

🔩 Projects
�

⚡ 4-Bit ALU
Digital Design · Gate-Level Logic
Implements arithmetic (ADD, SUB, INC) and logic (AND, OR, XOR, NOT) operations across 4-bit operands
Built from fundamental digital design principles — cascaded full adders, multiplexed outputs, carry logic
Foundation project demonstrating deep understanding of combinational circuit design and hardware computation
�

🔗 Ripple Carry Adder
Arithmetic Circuits · Carry Propagation
Models carry propagation through cascaded full adder stages — critical concept in hardware arithmetic
Explores the fundamental speed-vs-simplicity tradeoff in digital addition circuits
Serves as the architectural foundation for ALU design and binary arithmetic hardware
�

🧠 Hybrid CPU (Flagship Project)
FPGA · Hardware ALU · CPU Architecture
FPGA handles control logic — FSM, instruction decode, register file, and datapath orchestration
External hardware ALU built from discrete logic performs physical computation alongside programmable logic
True hardware-software co-design — bridges programmable FPGA fabric with real-world circuit integration
�

📡 Edge AI Inference System (In Progress)
Edge AI · Embedded Systems · Raspberry Pi
Deploying TinyML models on resource-constrained hardware platforms for real-time inference
Exploring hardware accelerator concepts — how neural network inference maps to digital logic
Bridging algorithm design with hardware constraints: latency, power, and memory trade-offs
�

�

�

�

📊 GitHub Stats
�

�
￼ ￼
�


�
Load image
�

�

�

�

🌌 System Vision
�

THE HIERARCHY OF INTELLIGENCE
═══════════════════════════════════════════════════════════════════════

   ⚛️  ELECTRONS
         │
         ▼
   🔲  TRANSISTORS  →  switching, amplifying, controlling
         │
         ▼
   🔀  LOGIC GATES  →  AND, OR, NOT, XOR — the atoms of computation
         │
         ▼
   🧩  CIRCUITS     →  adders, multiplexers, flip-flops, registers
         │
         ▼
   🏗️  CPU           →  control unit + ALU + memory + datapath
         │
         ▼
   🖥️  SYSTEMS       →  OS, compilers, firmware, drivers
         │
         ▼
   🤖  EDGE AI       →  intelligent inference at the hardware boundary
         │
         ▼
   🌐  INTELLIGENT SYSTEMS  →  autonomous, adaptive, aware

═══════════════════════════════════════════════════════════════════════

         "Hardware is not the bottleneck — it is the foundation."
         "Every algorithm runs on silicon. I build the silicon."
         "From electrons to AI: this is the full stack."

═══════════════════════════════════════════════════════════════════════
�

�

�

�

🎯 Career Vision & Open Source
┌─────────────────────────────────────────────────────────────────┐
│                    WHERE I'M HEADING                            │
├─────────────────────────────────────────────────────────────────┤
│                                                                 │
│  🏭  SEMICONDUCTOR INDUSTRY                                     │
│      RTL design, verification, physical design, VLSI flows     │
│                                                                 │
│  ⚙️  LOW-LEVEL SYSTEMS                                          │
│      CPU microarchitecture, custom instruction sets, firmware  │
│                                                                 │
│  🤝  HARDWARE-SOFTWARE CO-DESIGN                                │
│      Where compilers meet silicon, where code meets circuits   │
│                                                                 │
│  🌍  OPEN SOURCE CONTRIBUTIONS                                  │
│      OpenROAD • OpenLane • RISC-V ecosystem • LibreCores       │
│      Learning through real open silicon — not just textbooks   │
│                                                                 │
│  📐  DESIGN PHILOSOPHY                                          │
│      Understand the physics → Design the logic                 │
│      Build the system → Verify the behavior                    │
│      Optimize the architecture → Ship real hardware            │
│                                                                 │
└─────────────────────────────────────────────────────────────────┘
�

�

�

📡 Connect & Collaborate
�

If you're working on:
  ⚡ Digital or Analog Electronics
  🔷 FPGA / HDL Projects
  🧠 CPU Architecture or RISC-V
  🤖 Edge AI / Embedded Intelligence
  🔬 Semiconductor or VLSI Design

→ Let's build something real.
�


�
�
�
Load image
Load image
Load image
�


⚡ "Not just an engineer. A builder of thinking machines — starting from the gate." ⚡
�
Load image
�

�
⚡ Built with circuits, logic, and caffeine · Abhijith · Hardware × Software × AI ⚡
