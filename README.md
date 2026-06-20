# AeroStream – Aerospace Telemetry Analytics & Anomaly Detection Platform

AeroStream is a telemetry analytics platform that simulates aircraft sensor data, monitors flight parameters, and identifies abnormal operating conditions using machine learning-based anomaly detection techniques.

## Overview

AeroStream is an end-to-end telemetry analytics pipeline that generates and processes simulated aircraft sensor data to detect anomalous operating conditions using machine learning techniques.

## Key Features

* Synthetic telemetry data generation
* Telemetry preprocessing and analysis
* Isolation Forest-based anomaly detection
* Telemetry visualization and trend analysis
* Anomaly statistics and reporting
* CSV export of detected anomalies

## Technical Approach

The pipeline generates synthetic telemetry data, preprocesses sensor measurements, applies Isolation Forest for anomaly detection, and visualizes anomalous patterns through statistical reports and plots.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

## Project Structure

* `telemetry_generator.py` – Synthetic telemetry generation
* `anomaly_detector.py` – Isolation Forest anomaly detection
* `visualize.py` – Telemetry visualization
* `run_pipeline.py` – End-to-end analytics pipeline
* `telemetry_data.csv` – Sample telemetry dataset
* `requirements.txt` – Project dependencies

## Getting Started

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the telemetry analytics pipeline:

```bash
python run_pipeline.py
```

## Sample Output

![Telemetry Output](assets/telemetry_output.png)

## Potential Applications

* Aerospace telemetry monitoring
* Predictive maintenance support
* Flight operations analytics
* Sensor anomaly detection
* Safety monitoring systems

## Future Enhancements

* Real-time telemetry stream ingestion
* Live monitoring dashboards
* Automated anomaly alerting
* Integration with real-world telemetry datasets
* Advanced predictive analytics models

## Author

**Aishwarya S Ningappanavar**

B.E. Electronics and Communication Engineering
Nitte Meenakshi Institute of Technology (NMIT), Bengaluru

* GitHub: https://github.com/aishwarya-15sn
* LinkedIn: https://www.linkedin.com/in/snaishwarya
