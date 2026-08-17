# 3.5 kW Dual Active Bridge Converter 

DAB prototype developed as part of the Master's thesis, *"Design and Implementation of a Dual Active Bridge DC-DC Converter for Photovoltaic Integration in a DC Microgrid"*, awarded the maximum grade (20/20) ([thesis](https://hdl.handle.net/10216/174149)).

| Parameter | Value |
|:---|---:|
| Rated power | 3.5 kW |
| Input voltage | 200–450 V |
| Input current (DC) | 0–9 A |
| Output voltage | 700 V nominal (640–760 V) |
| Output current (DC) | 0–5 A |
| Maximum efficiency | >90% |
| Primary transformer current | 22 A RMS / 34 A pk-pk |
| Switching frequency | 100 kHz |
| Phase-shift range | 0–90° |
| Transformer turns ratio | 6:21 |
| Leakage inductance | 30.21 μH (2 × 15 μH) |
| Primary SiC MOSFET | IMZA65R026M2H (650 V) |
| Secondary SiC MOSFET | IMZC120R078M2H (1200 V) |
| Gate driver | Infineon 1ED3250MC12H |
| Control board | TI TMS320F280039C ControlCARD |
| Cooling method | Heatsink / air |
 
## Prototype

![DAB3k5W Front View](images/DAB3k5W_front-view.jpeg)

![DAB3k5W Side View](images/DAB3k5W_side-view.jpeg)

## PCB 3D Views

#### Power board

![Power Board 3D Top View](images/power_board_3D_top-view.png)

![Power Board 3D Bottom View](images/power_board_3D_bottom-view.png)

#### Gate driver board

<p align="center">
  <img src="images/gate_driver_board_3D_top-view.png" width="60%">
</p>
