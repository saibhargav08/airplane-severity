# airplane-severity

Machine Learning model to anticipate and classify the severity of any airplane accident based on past incidents

Public Rank - 386

Leaderboard: https://www.hackerearth.com/challenges/competitive/airplane-accident-severity-hackerearth-machine-learning-challenge/leaderboard/how-severe-can-an-airplane-accident-be-03e7a3f1/

# Data Description:

Accident_ID	- unique id assigned to each row

Accident_Type_Code	- the type of accident (factor, not numeric)

Cabin_Temperature	- the last recorded temperature before the incident, measured in degrees fahrenheit

Turbulence_In_gforces	- the recorded/estimated turbulence experienced during the accident

Control_Metric	- an estimation of how much control the pilot had during the incident given the factors at play

Total_Safety_Complaints	- number of complaints from mechanics prior to the accident

Days_Since_Inspection	- how long the plane went without inspection before the incident

Safety_Score	- a measure of how safe the plane was deemed to be

Violations	- number of violations that the aircraft received during inspections

Severity	- a description (4 level factor) on the severity of the crash [Target]
