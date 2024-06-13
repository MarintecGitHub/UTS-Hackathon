# UTS-Hackathon

## Scenario:
A crew member on a naval ship encounters one or multiple alarms on the primary engine. They lack immediate access to an expert or the required technical documentation. Your system, which has ingested the required documentation and extracted the necessary insights, will provide a diagnosis and recommended actions.

## Challenge:
Design and build a system to assist crew on a naval ship in diagnosing and determining actions following alarms from the ship's primary Engine. This system must use code to dynamically identify and describe information related to these alarms without a simple "lookup" prompt on the PDF.

## Task:
Using the Alarms on the Excel File: "ALARMS.xlsx", you are required to design and code a system to identify the following information from the Technical Documentation (PDF files):
- Sensor(s) the Alarm is related to.
- Sensor Measuring Point(s).
- Sensor Description.
- Sensor Measuring Range.
- System the Sensor is Related to.
- System the Sensor is Dependant on.
- Related Sensors to Given Sensor.
- Potential Triggers of the Alarm:
  - Temperature/Pressure/Power Exceeding Threshold Setpoint?
  - Engine Shutdown?
  - Sensor Failure?
- What possible Actions could a Crew Member Take given the Alarm?
- What Technical Knowledge is Required to Solve the Problem?
- What Parts (if any) would be Required to Solve the Problem?
- What Drawings or Diagrams (if any) are Present in the Technical Documentation that Related to this Alarm?

## Resources in this Repository:
1. "MAN_32-40_IMO_TierIII–Marine_.pdf" ------> Diesel Engine Technical Manual
2. "MAN_32-40_Troubleshooting_Guide.pdf" --> Diesel Engine Troubleshooting Guide
3. "ALARMS.xlsx" --------------------------------> List of Alarms of which to identify and answer the questions in "Task".
