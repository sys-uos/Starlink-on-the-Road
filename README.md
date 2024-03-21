[![License: CC BY-SA 4.0](https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
# Starlink-on-the-Road Data Set
This repository contains the data used in our paper 
[Starlink on the Road: A First Look at Mobile Starlink Performance in Central Europe (Preprint)](https://arxiv.org/abs/2403.13497). Due to privacy reasons, we do only offer data without locations. All measurements were conducted in and around Osnabrück City (Germany). The number of samples varies depending on the type of measurement. Details of the measurement setup are presented in our paper.

## Files
All collected data is in the `data` folder. 

| Filename | Description | No. Samples |
| -------- | -------- | ---------------|
| iperf| Througput measurment data for download and upload measured using iperf3. The Measurements are annotated with the according driving speeds. | 17479 |
| ping | RTT measurements matched with the according driving speed. | 1191 |
| power_data.csv | Power consumption (in W) of the Starlink dish measured with a ZigBee socket. Data is annoted with driving speed, download throughput, upload throughput and outdoor temperature [(DWD TT_10)](https://opendata.dwd.de/climate_environment/CDC/observations_germany/climate/10_minutes/air_temperature/recent/10minutenwerte_TU_00342_akt.zip) | 519 | 



## Citation 
D. Laniewski, E. Lanfer, S. Beginn, J. Dunker, M. Dückers, N. Aschenbruck, “Starlink on the Road: A First Look at Mobile Starlink Performance in Central Europe”, arXiv preprint arXiv:2403.13497, 2024.
```
@misc{laniewski2024starlink,
    title={Starlink on the Road: A First Look at Mobile Starlink Performance in Central Europe},
    author={Dominic Laniewski and Eric Lanfer and Simon Beginn and Jan Dunker and Michael Dückers and Nils Aschenbruck},
    year={2024},
    eprint={2403.13497},
    archivePrefix={arXiv},
    primaryClass={cs.NI}
}
```
## License
This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

