# UTS-Hackathon

## Scenario:
A crew member on a naval ship encounters one or multiple alarms on the primary engine. They lack immediate access to an expert or the required technical documentation. Your system, which has ingested the required documentation and extracted the necessary insights, will provide a diagnosis and recommended actions.

## Challenge:
Design and build a system to assist crew on a naval ship in diagnosing and determining actions following alarms from the ship's primary Engine. This system must use code to dynamically identify and describe information related to these alarms without a simple "lookup" prompt on the PDF.

## Task:
Using the alarms on the Excel File: "ALARMS.xlsx", you are required to design and code a system to identify the following information from the technical documentation (PDF files):
- Sensor(s) the alarm is related to.
- Sensor measuring point(s).
- Sensor description.
- Sensor measuring range.
- System the sensor is related to.
- System the sensor is dependent on.
- Related sensors to given sensor.
- Potential triggers of the alarm:
  - Temperature/Pressure/Power exceeding threshold setpoint?
  - Engine shutdown?
  - Sensor failure?
- What possible actions could a crew member take given the alarm?
- What technical knowledge is required to solve the problem?
- What parts (if any) would be required to solve the problem?
- What drawings or diagrams (if any) are present in the technical documentation that related to this alarm?

## Resources in this Repository:
1. "MAN_32-40_IMO_TierIII–Marine_.pdf" ------> Diesel Engine Technical Manual
2. "MAN_32-40_Troubleshooting_Guide.pdf" --> Diesel Engine Troubleshooting Guide
3. "ALARMS.xlsx" --------------------------------> List of alarms of which to identify and answer the questions in "Task".
