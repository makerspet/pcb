# PCB for makerspet.com DIY Robots
PCB boards for [Maker's Pet](https://github.com/makerspet/makerspet_loki/) robots compatible with [Kaia.ai](https://kaia.ai) [platform](https://github.com/kaiaai/kaiaai/). All PCBs are designed using KiCAD.

- ESP32 breakout [board](/esp32_breakout/)
- Raspberry Pi Pico breakout [board](/pico_breakout_head/) for robot's head
- Raspberry Pi Pico breakout [board](/pico_breakout_body/) for robot's lower body
- adapter [board](/lds02rr_adapter/) for Xiaomi 1st gen LDS02RR laser distance scan sensor
- adapter [board](/neato_delta_adapter/) for Neato XV11, 3irobotix Delta-2A, Delta-2G laser distance scan sensors
- adapter [board](/hls_adapter/) for Hitachi-LG HLS-LFCD2

These LiDAR/LDS sensors do not need an adapter board and connect to the robot [ESP32 breakout board](/esp32_breakout/) directly using a custom cable:
- YDLIDAR X4, X3, X3 PRO, X2/X2L
- Hitachi-LG HLS-LFCD3
- SLAMTEC RPLIDAR A1
