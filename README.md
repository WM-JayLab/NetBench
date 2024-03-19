# NetBench
Dataset: [Link](https://drive.google.com/drive/u/2/folders/1dYGHKKJR5WS4cXISk9AtfW_gB9mdC2ED)

Our Benchmark Dataset are collected from the following sources:
|                   Dataset                   |   #Flow   |   #Packet  |                 Task                 | #Label |
|:-------------------------------------------:|:---------:|:----------:|:------------------------------------:|:------:|
|                 ISCXVPN 2016                |  311,390  |  1,040,354 | 1 - VPN Detection                    |    2   |
|                                             |           |            | 2 - VPN Service Detection            |    6   |
|                                             |           |            | 3 - VPN Application Classification   |   17   |
|                 ISCXTor 2016                |   55,523  |  1,163,495 | 4 - Tor Detection                    |    2   |
|                                             |           |            | 5 - Tor Service Detection            |    7   |
|                USTC-TFC 2016                |  489,139  |  4,564,519 | 6 - Malware Detection                |    2   |
|                                             |           |            | 7 - Application Classification       |   20   |
|       Cross Platform   (Android) 2020       |   66,346  |  1,358,292 | 8 - Application Classification       |   212  |
|                                             |           |            | 9 - Country Detection                |    3   |
|         Cross Platform (iOS)   2020         |   34,912  |   971,762  | 10 - Application Classification      |   196  |
|                                             |           |            | 11 - Country Detection               |    3   |
|             CIRA-CIC-DoHBrw-2020            |  831,497  | 32,962,034 | 12 - DoH Attack Detection            |    2   |
|                                             |           |            | 13 - DoH Query Method Classification |    5   |
|             CIC IoT Dataset 2023            | 1,163,495 | 27,738,736 | 14 - IoT Attack Detection            |    2   |
|                                             |           |            | 15 - IoT Attack Method Detection     |    7   |
| Consecutive Packets   from above 7 datasets |     -     | 12,786,490 | 16 - Source IP Generation            |    -   |
|                                             |           |            | 17 - Destination IP Generation       |        |
|                                             |           |            | 18 - Source Port Generation          |        |
|                                             |           |            | 19 - Destination Port Generation     |        |
|                                             |           |            | 20 - Packet Length Generation        |        |
|                    Total                    | 2,952,302 | 69,799,192 | -                                    |    -   |


If you use our benchmark, please cite the following paper.
```
@article{wang2024lens,
  title={Lens: A Foundation Model for Network Traffic in Cybersecurity},
  author={Wang, Qineng and Qian, Chen and Li, Xiaochang and Yao, Ziyu and Shao, Huajie},
  journal={arXiv e-prints},
  pages={arXiv--2402},
  year={2024}
}
```
```
@inproceedings{qian2024netbench,
  title={NetBench: A Large-Scale and Comprehensive Network Traffic Benchmark Dataset for Foundation Models}, 
  author={Chen Qian and Xiaochang Li and Qineng Wang and Gang Zhou and Huajie Shao},
  booktitle={International Workshop on Foundation Models for Cyber-Physical Systems \& Internet of Things (FMSys)},
  organization={IEEE},
  year={2024}
}
```
