# Awesome GNSS 

<p align=center>
 <a href="https://github.com/karimi-hadi/awesome-gnss">
  <img alt="awesome" src="https://awesome.re/badge-flat.svg"/>
 </a>
 <a href="https://github.com/karimi-hadi/awesome-gnss">
  <img alt="PRs Welcome" src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg"/>
 </a>
</p>

## About
A collection of awesome GNSS/RNSS related sources, tools, data, MOOC's course, etc. 

## Content
- [Open Source Software or Tools](#open-source-software-or-tools)
  - [Desktop Tools](#desktop-tools)
  - [Mobile Tools](#mobile-tools)
  - [Web Tools](#web-tools)
- [Data and Products Archives](#data-and-products-archives)
- [GPS](#gps)
- [GLONASS](#glonass)
- [Galileo](#galileo)
- [BeiDou](#beidou)


## Open Source Software or Tools
### Desktop Tools
- [RTKLIB](https://github.com/tomojitakasu/RTKLIB) - An open source program for standard and precise positioning.
- [GNSS-SDR](https://github.com/gnss-sdr/gnss-sdr) - An open source GNSS software defined receiver.
- [GNSS-SDRLIB](https://github.com/taroz/GNSS-SDRLIB) - An Open Source GNSS Software Defined Radio Library
- [GPSTk](https://github.com/SGL-UT/GPSTk) - A library and suite of applications to the satellite navigation.
- [GNSS-DSP-tools](https://github.com/pmonta/GNSS-DSP-tools) - Python-GNSS code generators, acquisition, and tracking
- [GNSS-matlab](https://github.com/danipascual/GNSS-matlab) - Matlab codes to generate GNSS PRNs, secondary codes, dataless signals and spectra. Includes real data captures and a theory summary. GPS (L1CA, L2C, L5), Gaileo (E1OS, E5), BeiDou-2 (B1I)


### Mobile Tools
- [GPSLogger](https://github.com/mendhak/gpslogger) - A Lightweight GPS Logging Application For Android.
- [GNSSLogger](https://github.com/google/gps-measurement-tools) - Sample GNSS Logging App From Google.
- [GPSTest](https://github.com/barbeau/gpstest) - An open-source Android GNSS/GPS test program.
- [RTKGPS+](https://github.com/eltorio/RtkGps) - RTKLIB (RTKNAVI) port on android.
- [GNSS_Compare](https://github.com/TheGalfins/GNSS_Compare) - A framework for processing raw GNSS measurements.

### Web Tools
- [CSRS-PPP](https://webapp.geod.nrcan.gc.ca/geod/tools-outils/ppp.php?locale=en) - *Canadian Precise Point Positioning* (NRCan).
- [APPS](http://apps.gdgps.net/) - *Automatic Precise Positioning Service* (JPL). 
- [GAPS](http://gaps.gge.unb.ca/) - *GNSS Analysis and Positioning Software* (UNB).
- [OPUS](https://www.ngs.noaa.gov/OPUS/) - *Online Positioning User Service* (NGS).
- [AUSPOS](http://www.ga.gov.au/bin/gps.pl) - *A free online GPS data processing facility* (GA).


## Data and Products Archives
- [CDDIS](https://cddis.nasa.gov/) - NASA's Archive of Space Geodesy Data
- [GSSC](https://gssc.esa.int/) - ESA's GNSS Science Support Center
- [WHU](http://www.igs.gnsswhu.cn/) - Wuhan University Data Center
- [BKG](https://igs.bkg.bund.de/) - Federal Agency for Cartography and Geodesy 


## GPS 
:satellite: :us:
- [NavCen](https://www.navcen.uscg.gov/) - GPS Constellation status 


## GLONASS 
:satellite: :ru:
- [GLONASS-IAC](https://www.glonass-iac.ru/en/) - GLONASS Constellation status
 
 
## Galileo 
:satellite: :eu:
- [GSC](https://www.gsc-europa.eu/) - Galileo Constellation status


## BeiDou 
:satellite: :cn:
- [CSNO-TARC](http://www.csno-tarc.cn/) - BeiDou Constellation status

-----------------------------------------------------------------------------
## GNSS-Metadata-Standard
- GNSS Sofware Defined Receiver Metadata Standard http://sdr.ion.org/
- https://github.com/IonMetadataWorkingGroup/GNSS-Metadata-Standard

## GMT
- 全称Generic Mapping Tools，中文一般译为“通用制图工具”，是地球科学最广泛使用的制图软件之一，具有强大的绘图功能和数据处理功能。如今 GMT 也支持通过 Python 调用了。
- A Python interface for the Generic Mapping Tools (https://github.com/GenericMappingTools/pygmt)

## GNSSpy
- Python Toolkit for GNSS Data (https://github.com/GNSSpy-Project/gnsspy)
- GNSSpy 是一个能处理多星座、2和3 不同版本 RINEX 观测值文件的免费开源的库。
- 提供了基于精密星历、钟差和最小二乘算法的 SPP 和 PPP 功能；
- 支持文件编辑（切割、降采样、合并）；
- 支持质量检核（统计多路径、电离层延迟、SNR）；
- GNSS数据可视化（天空图、方位-高度角、时间-高度角、星下点轨迹、观测弧段可视化）
- ......

## Laika
- Simple Python GNSS processing library (https://github.com/commaai/laika)
-Laika is an open-source GNSS processing library. Laika is similar to projects like RTKlib and GPSTK, but in Python and with a strong focus on readibility, usability and easy integration with other optimizers. Laika can process raw GNSS observations with data gathered online from various analysis groups to produce data ready for position/velocity estimation. Laika is designed to produce accurate results whilst still being readable and easy to use. Laika is the perfect tool to develop accurate GNSS-only or GNSS-fusion localisation algorithms.

## GPS Measurement Tools
- from Google (https://github.com/google/gps-measurement-tools)
- The GNSS Measurement Tools code is provided for you to:
- read data from GnssLogger App,
- compute and visualize pseudoranges,
- compute weighted least squares position and velocity,
- view and analyze carrier phase (if it is present in the log file).

## NaveGo
- an open-source MATLAB/GNU Octave toolbox for processing integrated navigation systems and performing inertial sensors analysis.
- https://github.com/rodralez/NaveGo
- Main features of NaveGo are:
- Processing of an inertial navigation system (INS).
- Processing of a loosely-coupled integrated navigation system (INS/GNSS).
- Simulation of inertial sensors and GNSS.
- Zero Velocity Update (ZUPT) detection algorithm.
- Allan variance technique to characterize inertial sensors' both deterministic and stochastic errors.

## goGPS_MATLAB
- goGPS MATLAB is an advanced GNSS observation processing software. http://www.gogps-project.org/
- https://github.com/goGPS-Project/goGPS_MATLAB
- goGPS is a software package designed to perform GPS positioning, either in post-processing or real-time. It is developed in MATLAB and it is aimed at providing a tool useful for studying GPS positioning, implementing and testing new algorithms and interacting in general with GPS-related aspects.

## Nequick-G
- https://github.com/Fraunhofer-IIS/NequickG
- This is a python implementation of the Nequick-G ionospheric correction model described in European Space Agency's Galileo Ionospheric Model. Ionospheric disturbance flags are not implemented

## gps-sdr-sim 
- GPS-SDR-SIM generates GPS baseband signal data streams, which can be converted to RF using software-defined radio (SDR) platforms, such as ADALM-Pluto, bladeRF, HackRF, and USRP.
- https://github.com/osqzss/gps-sdr-sim
- GPS-SDR-SIM for Microsoft Windows(https://github.com/camtas/gps-sdr-sim-Windows)



