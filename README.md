# Rithvik Vadlamani

I'm an Electrical and Computer Engineering student at UT Austin, graduating in May 2028. I build software tools and embedded systems, and work on power electronics with Guadaloop.

I'm looking for Summer 2027 internships in software engineering, robotics, embedded software, and hardware engineering.

[LinkedIn](https://www.linkedin.com/in/rithvik-vadlamani/) · [Project repositories](https://github.com/Rithvik-Vadlamani?tab=repositories)

## Start here

For **software engineering**, start with the code review tool and robot task simulator. For **hardware and embedded systems**, start with Guadaloop's wireless power design and Battleship.

| Project | What it does | Built with |
| --- | --- | --- |
| [Code review CLI](https://github.com/Rithvik-Vadlamani/ai-code-reviewer#readme) | Reads a Git diff and flags potential bugs and security issues. Includes rule-based checks and an optional language-model backend. | Python, Git, pytest |
| [Robot task simulator](https://github.com/Rithvik-Vadlamani/behavior-tree-robot#readme) | Uses a behavior tree to run patrol and pick-and-place scenarios, including recovery when the simulated robot needs to charge. | Python, behavior trees, pytest |
| [Guadaloop wireless power transfer](https://github.com/Rithvik-Vadlamani/guadaloop-wireless-power-transfer#readme) | Models a four-section wireless charging track with a 60 V, 20 A output target. Includes coil calculations, circuit models, and saved simulation results. | MATLAB, Simulink, Simscape, Python |
| [Embedded Battleship](https://github.com/Rithvik-Vadlamani/Battleship-Game#readme) | Runs a two-player game on an MSPM0G3507 microcontroller with an LCD, physical controls, and English/Spanish text. | C, microcontrollers, ST7735 display |

### A closer look at the hardware work

On Guadaloop's power electronics team, I've designed buck-converter and LDO boards for a 60 V battery system and co-designed a four-layer H-bridge for magnetic levitation. The public wireless power repository covers a separate design and simulation project. Its output and efficiency results are simulated; prototype measurements are still needed.

[Read the wireless power design report](https://github.com/Rithvik-Vadlamani/guadaloop-wireless-power-transfer/blob/main/DD_TRACK_DESIGN.md) · [Open the project guide](https://github.com/Rithvik-Vadlamani/guadaloop-wireless-power-transfer/blob/main/START_HERE.md)

## More projects

- [LiDAR point-cloud encoder](https://github.com/Rithvik-Vadlamani/lidar-sensor-encoder#readme): a PyTorch implementation of a masked autoencoder for reconstructing missing point-cloud geometry.
- [Demand forecasting](https://github.com/Rithvik-Vadlamani/supply-chain-forecasting#readme): compares ARIMA, Prophet, and XGBoost on synthetic demand data, with a [Colab notebook](https://colab.research.google.com/github/Rithvik-Vadlamani/supply-chain-forecasting/blob/main/demo_colab.ipynb).
- [CartPole policy gradient](https://github.com/Rithvik-Vadlamani/rl-cartpole#readme): implements REINFORCE with NumPy and Gymnasium.
- [ROS 2 publisher/subscriber](https://github.com/Rithvik-Vadlamani/ros2-pub-sub#readme): a small Python example of topic-based communication between nodes.

## Other work

I've also built a personal internship discovery tool with FastAPI, PostgreSQL, and ONNX; an LC-3b processor simulator in C; and a datasheet retrieval assistant for circuit design. My HDMI/USB KVM project combines a four-layer PCB design with STM32 firmware. These projects aren't linked here because their code isn't currently public.

## Skills

**Software:** Python, C, Java, SQL, FastAPI, PostgreSQL, Git, Linux, automated testing.

**Hardware and embedded:** microcontrollers, embedded firmware, PCB design, power electronics, MATLAB/Simulink, KiCad.
