# 4-Inch-Rocket-Fin-Optimization
An aerodynamic sensitivity analysis evaluating the trade-offs between stability, apogee, and maximum velocity across varying fin geometries for a 4-inch airframe rocket. 


## Final Report
View the complete single-page study<br/>
**[4-Inch High-Power Rocket Aero Performance Sensitivity](.Aero_Performance/4_in_high_power_rocket_aero_performance_sensitivity_study.pdf)**


## Key Takeaways
* **Span Dominance:** Fin span is the primary driver of vehicle stability, accounting for up to a **90% drop** in stability margin when reduced below baseline. <br/> 
* **Sweep Sensitivity:** Fin sweep provides moderate stability control (**61% variation** relative to baseline) with only minor velocity drag penalties.<br/>
* **Tip Chord Tuning:** Tip chord exhibits minimal overall performance impact (**16% sensitivity** relative to baseline), making it an ideal parameter for structural and manufacturing fine-tuning.<br/>

## Parameters Evaluated
| Parameter | Test Range | Baseline Value | Stability Impact |
| :--- | :--- | :--- | :--- |
| **Fin Span** | 7 - 14 cm | 10 cm | High (90% change) |
| **Fin Sweep** | 3 - 18 cm | 15 cm | Moderate (61% change) |
| **Tip Chord** | 4 - 30 cm | 7.5 cm | Low (16% change) |

## Project Structure

**[4-Inch High-Power Rocket Design Review](./Documentation/4_in_high_power_rocket_design_review.pdf)**   --> Standardized 3x3 matrix PDF report<br/>
**[4-Inch Rocket Design](./Simulations/4_in_rocket_design.ork)**                                       --> Rocket design and simulation<br/>
**[Graphs](./Aero_Performance/Graphs)**                                     --> Graphs of varying geometries vs apogee, max velocity, and stability <br/>
<br/>
**[README](./README.md)**                                                                 --> Project overview and key takeaways<br/>
