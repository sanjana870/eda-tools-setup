# eda-tools-setup
The lecture slides describe the System-on-Chip (SoC) design flow, from initial specification to real-world applications. Here’s a summary based on the provided screenshots:

Overview of SoC Design Flow
The design process starts with chip modeling and advances through key stages managed by chip modeling engineers and RTL architects:

O1 (Specs in C model): The initial step involves defining specifications using a C model, with the testbench also written in C.

O2 (RTL Description): The hardware is next described in RTL (such as Verilog), providing a "soft copy" of the intended hardware.

O3 (SoC Integration): Components like processors and peripherals/IPs are integrated, leading to a gate-level netlist after synthesis. Analog and macro IPs are also included, moving towards a finalized GDSII file for manufacturing.

O4 (Physical Implementation): The finished chip, with peripherals, runs at practical speeds (100MHz–130MHz) and can be applied to various real-world applications, such as smartwatches, Arduino boards, TV panels, and AC systems.

Key Processes and Outputs
Each stage produces a validated output tested by a C-language testbench, ensuring consistency from modeling to hardware implementation.

The steps O1 to O4 represent different design phases but ultimately converge to create the final SoC, adaptable to many applications.

Practical Applications
The design methodology allows a single chip to serve as the basis for various consumer electronics.

The same workflow ensures strong verification, modularity, and adaptability by reusing comparable design practices for different products.

In summary, the lecture slides present a comprehensive overview of the industry-standard SoC design process, emphasizing simulation, modular integration, and end-use versatility.
