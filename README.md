# MRT-3 Passenger Traffic Analysis

## Introduction
In this analysis, our primary focus is on unraveling the intricate patterns of passenger traffic over time across all MRT-3 stations. By delving into the temporal dynamics of passenger counts, we aim to identify both the lulls and peaks in activity, providing actionable insights for strategic operational adjustments.

Specifically, we seek to pinpoint the times when each station experiences the least passenger load, offering opportunities for system maintenance and optimization during these downtimes. Simultaneously, we aim to identify the peak hours when stations, especially the busiest one, witness the highest passenger influx. This dual-pronged approach not only aids in operational planning for downtime but also equips the MRT-3 system to proactively prepare for and manage increased passenger demands during peak hours.

## Overview of Variables
Our research is based on the dataset **DOTC-MRT3 HOURLY RIDERSHIP REPORT** obtained from the Freedom of Information (FOI). It compiles **17,520 observations** collected from January to December 2022. The following **18 factors** are used as explanatory variables:

- **ID**: Unique identification for each data point of entry/exit.
- **Date**: Date of the collected data from 1 January 2022 to 31 December 2022.
- **Start Time**: Start of the ridership duration.
- **End Time**: End of the ridership duration.
- **Type**: Categorical type of ridership (entry/exit).
- **North Ave**: Number of riders who entered/exited North Avenue Station.
- **Quezon Ave**: Number of riders who entered/exited Quezon Avenue Station.
- **GMA Kamuning**: Number of riders who entered/exited GMA Kamuning Station.
- **Cubao**: Number of riders who entered/exited Cubao Station.
- **Santolan**: Number of riders who entered/exited Santolan Station.
- **Ortigas**: Number of riders who entered/exited Ortigas Station.
- **Shaw Blvd**: Number of riders who entered/exited Shaw Blvd Station.
- **Boni Ave**: Number of riders who entered/exited Boni Ave Station.
- **Guadalupe**: Number of riders who entered/exited Guadalupe Station.
- **Buendia**: Number of riders who entered/exited Buendia Station.
- **Ayala Ave**: Number of riders who entered/exited Ayala Ave Station.
- **Magallanes**: Number of riders who entered/exited Magallanes Station.
- **Taft**: Number of riders who entered/exited Taft Station.

These variables collectively offer a comprehensive view of MRT-3 ridership traffic, laying the groundwork for optimization modeling and analysis.

## Goal
The Data Science team's goal is to leverage the timestamp data per station, along with insights into the busiest station and its corresponding high-traffic times. Our analysis aims to deliver valuable recommendations for enhancing the overall efficiency and responsiveness of the MRT-3 system.
