# MUDE-PD

Logs from MUDE-PD scenarios simulations executed in [GrADyS-SIM NextGen](https://github.com/Project-GrADyS/gradys-sim-nextgen), a Python framework designed to simulate distributed algorithms in a network environment comprising communication and mobile nodes. GrADyS-SIM NextGen enhances the original GrADyS-SIM framework by allowing users to simulate the same code in both integrated modes using OMNeT++ for more realistic simulations of network interactions. This framework was employed to model and observe the movement and message exchanges of UAV swarms, thereby validating communication and cooperation among UAVs, ground stations, and mobile PoIs.

A comprehensive set of scenarios was modeled to assess the effectiveness of the MUDE-PD search algorithm across various parameter configurations as presented in the table below. 

### All values that are used to define each simulation scenario

| **Category**               | **Parameter** | **Values**                       | **Unit**   |
|---------------------------|-----------|----------------------------------|------------|
| **Environment Parameters** | A         | 16, 36, 64                       | hectares   |
|                           | k         | 1, 2, 8, 16, 50, 100             | units      |
|                           | c_k       | 0, 1, 5, 10                      | clusters   |
|                           | v_o       | 5                                | m/s        |
| **Mission Parameters**     | n        | 2, 4, 8, 16, 32, 64              | units      |
|                           | T         | 900, 1200, 1800                  | seconds    |
|                           | r_c       | 20                               | meters     |
|                           | h         | 20                               | meters     |
|                           | v         | 10                               | m/s        |

### Directory structure
The repository is divided into two parts:

```
.mudepd_logs_dataset
├── logs/       # Raw log data for each simulation
└── dataset/    # Consolidated CSV logs for groups of simulations
```
