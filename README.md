# PCB for makerspet.com DIY Robots
PCB boards for [Maker's Pet](https://github.com/makerspet/makerspet_loki/) robots compatible with [Kaia.ai](https://kaia.ai) [platform](https://github.com/kaiaai/kaiaai/). All PCBs are designed using KiCAD.

Please visit the [Support Forum](https://github.com/makerspet/support/discussions/)!

- ESP32 breakout [board](/esp32_breakout/)
- Raspberry Pi Pico breakout [board](/pico_breakout_head/) for robot's head
- Raspberry Pi Pico breakout [board](/pico_breakout_body/) for robot's lower body (TODO)
- adapter [board](/lds02rr_adapter/) for Xiaomi 1st gen LDS02RR and Xiaomi 2nd gen LDS01RR laser distance scan sensors
- adapter [board](/neato_delta_adapter/) for Neato XV11, 3irobotix Delta-2A, Delta-2B and Delta-2G laser distance scan sensors
- adapter [board](/hls_adapter/) for Hitachi-LG HLS-LFCD2

LiDAR/LDS software support inludes the [Arduino LDS library](https://github.com/kaiaai/LDS) and the companion [kaiaai_telemetry ROS2 package](https://github.com/kaiaai/kaiaai).

## LiDAR/LDS that DON'T need an adapter
These LiDAR/LDS sensors connect to the robot [ESP32 breakout board](/esp32_breakout/) directly and
(coneniently) do not need an adapter board. You do still need a cable between the LiDAR and the ESP32 board.
- YDLIDAR X4, X3, X3 PRO, X2/X2L
- Hitachi-LG HLS-LFCD3
- SLAMTEC RPLIDAR A1
- LDROBOT LD14P
