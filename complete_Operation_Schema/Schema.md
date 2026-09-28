| ID | Operation | Precondition | Input | Postcondition |
|---|---|---|---|---|
| OP-01 | Perform Sensor Self-Check | Chamber is powered on. | Sensor status and control-device status | Essential sensors and control devices are verified. |
| OP-02 | Start Environmental Monitoring | Sensor self-check has successfully completed. | Sensor readings | Continuous environmental monitoring begins. |
| OP-03 | Register Artifact Information | Artifact has been placed inside the chamber. | Artifact identification information | Artifact information is recorded. |
| OP-04 | Load Environmental Profile | Artifact information has been registered. | Required environmental limits | Artifact's required environmental profile is loaded. |
| OP-05 | Verify Chamber Door Status | Artifact is inside and monitoring is active. | Door-status reading | Door condition is confirmed for conservation processing. |
| OP-06 | Start Conservation Control | Door is closed and environmental profile is loaded. | Environmental profile and sensor readings | Normal conservation activities begin. |
| OP-07 | Compare Environmental Readings | Conservation monitoring is active. | Temperature, humidity and permitted limits | Environmental conditions are determined to be within or outside permitted ranges. |
| OP-08 | Correct Temperature | Temperature is outside the permitted range. | Current temperature and required temperature range | Environmental-control mechanism attempts to restore temperature. |
| OP-09 | Verify Temperature Recovery | Temperature correction has been attempted. | Updated temperature readings | Temperature recovery is confirmed or determined unsuccessful. |
| OP-10 | Correct Humidity | Humidity is outside the permitted range. | Current humidity and required humidity range | Environmental-control mechanism attempts to restore humidity. |
| OP-11 | Verify Humidity Recovery | Humidity correction has been attempted. | Updated humidity readings | Humidity recovery is confirmed or determined unsuccessful. |
| OP-12 | Activate Artifact Protection | Environmental condition cannot be corrected within the allowed recovery period. | Environmental readings and recovery status | Artifact protection measures are activated. |
| OP-13 | Generate Operator Alert | Artifact protection is required. | Protection status and incident information | Museum operator is alerted. |
| OP-14 | Detect Significant Vibration | Artifact is inside and vibration monitoring is active. | Vibration sensor reading | Significant vibration is detected. |
| OP-15 | Suspend Risk-Increasing Activities | Significant vibration has been detected. | Vibration reading and active activities | Risk-increasing activities are temporarily suspended. |
| OP-16 | Verify Vibration Stabilization | Vibration has stopped or reduced. | Vibration readings and stabilization time | Required vibration stabilization is confirmed. |
| OP-17 | Suspend Conservation on Door Opening | Normal conservation is active and the door is opened. | Door-status reading | Normal conservation activities are immediately suspended. |
| OP-18 | Verify Conditions After Door Closure | Chamber door has been closed again. | Environmental readings and sensor status | Conditions are verified before normal conservation resumes. |
| OP-19 | Switch to Emergency Power | Power is lost and emergency power is available. | Power status and emergency-power availability | System switches to emergency power. |
| OP-20 | Record Power Failure Incident | Power is lost and emergency power is unavailable. | Power status and incident details | Power-loss incident is recorded. |
| OP-21 | Perform Safe Shutdown | Normal and emergency power are unavailable. | Power status and system status | System enters a safe shutdown condition. |
| OP-22 | Confirm Safe Artifact Removal | Operator requests artifact removal. | Chamber safety status and protection status | Artifact removal is permitted only when the chamber is safe and no active protection response exists. |
