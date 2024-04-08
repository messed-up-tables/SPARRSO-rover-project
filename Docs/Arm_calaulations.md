# Electrical Calculations

## Shoulder Base, Shoulder, Elbow
|Parameter|Value| Comments|
|---|---|---|
|Stepper motor model | NEMA 17HS8401 |---|
|Per phase currnet | 1.7A |---|
|Driver| TMC2209|TMC2208 delivers lower current and TB6600 is overkill|
|Driver max current| 2A (rms)| ---|
|Motor wire AWG|26|the wire is included with the motor|

# Mechanical Calculations
distance between shoulder and actuator links $d_s$
humerus length $h$
humerus actuator length (retracted) $h_r$
humerus actuator length (extended) $h_e$
shoulder angle (retracted) $'(d_s^2+h^2-h_r^2)/(2*d_s*h)'$
