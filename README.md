# Efficient Data Stream Anomaly Detection

## Overview
This project implements an anomaly detection system using the Random Cut Tree (RCT) Forest algorithm. It focuses on detecting anomalies in a simulated data stream that incorporates regular patterns, seasonal elements, and random noise. The algorithm is optimized for real-time performance, ensuring efficient detection without requiring extensive computational resources.

## Algorithm: Random Cut Tree (RCT) Forest
- **Description:** The RCT forest consists of multiple random cut trees that identify anomalies in data streams. Each tree models the underlying distribution of the data by making random cuts in the feature space. The co-displacement measure of a point indicates its deviation from normal patterns, with higher values signaling potential anomalies.
- **Effectiveness:** This method is well-suited for streaming data as it allows real-time updates and fast anomaly detection without requiring the entire dataset to be stored in memory. It is robust against noise and adapts to changes in data patterns over time.

## Features
- Simulates a data stream with sinusoidal patterns and added anomalies.
- Implements real-time anomaly detection using the RCT Forest algorithm.
- Includes robust error handling and data validation mechanisms.
- Provides visualization of the data stream and detected anomalies.

## Installation
To run this project, ensure you have Python installed along with the required libraries. You can install the necessary libraries using pip:

```bash
pip install numpy rrcf matplotlib
