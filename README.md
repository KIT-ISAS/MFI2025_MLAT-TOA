# MFI2025_MLAT-TOA

Very fast efficient multilateration algorithm. 
Directly uses the TOA measurements, without ever froming TDOA. 
Optimization via Levenberg-Marquardt algorithm. 
Objective function can be easily implemented in-place. 

Please cite as follows:
```
@inproceedings{MFI25_Frisch,
 address = {College Station, Texas},
 author = {Daniel Frisch and Uwe D. Hanebeck},
 booktitle = {Proceedings of the 2025 IEEE International Conference on Multisensor Fusion and Integration for Intelligent Systems (MFI 2025)},
 month = {September},
 title = {Why You Shouldn't Use TDOA for Multilateration},
 year = {2025}
}
```