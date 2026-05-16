# Payload-Carrying Fixed-Wing Drone — CFD & Structural Analysis

Designed and fabricated a fixed-wing UAV capable of carrying a 1 kg payload on an 800 g airframe.

## What I did

- Full electronics assembly in CAD before fabrication to accurately locate the centre of gravity
- Full-airframe CFD in ANSYS Fluent — iterative design revisions achieved **30% drag reduction** and **10% lift increase** over the baseline
- Grid independence study on the full-airframe mesh to verify solution accuracy
- Transient propeller CFD using sliding mesh to estimate thrust and validate motor selection
- Two-way FSI coupling to quantify wing deformation under aerodynamic loading; structural modifications implemented to limit aeroelastic performance degradation

## Tools

ANSYS Fluent · SolidWorks · Fusion 360

## Key results

| Metric | Baseline | Optimised |
|---|---|---|
| Drag | 1.298N | −36% |
| Lift | 12.268N | +12% |
| Payload capacity | 0.6kg | 1 kg on 800 g airframe |

<img width="722" height="331" alt="image" src="https://github.com/user-attachments/assets/e8a3f0f8-57eb-4446-8dd7-419d4a957277" />
<img width="723" height="301" alt="image" src="https://github.com/user-attachments/assets/cce1c420-71a0-4e58-b73b-517e1225a9a6" />
<img width="751" height="348" alt="image" src="https://github.com/user-attachments/assets/7aa8a307-74da-465c-8745-db8d8a7fbf83" />


