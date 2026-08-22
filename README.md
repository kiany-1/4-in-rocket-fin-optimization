# 4-in-rocket-fin-optimization
An aerodynamic sensitivity analysis evaluating the trade-offs between stability, apogee, and maximum velocity across varying fin geometries for a 4-inch airframe rocket. 

--

## Final Report
View the complete single-page study<br/>
**[4_in_high_power_rocket_aero_performance_sensitivity.pdf](./4_in_high_power_rocket_aero_performance_sensitivity.pdf)**

--

## Key Takeaways
**Span Dominance:** Fin span is the primary driver of vehicle stability, accounting for up to a **90% drop** in stability margin when reduced below baseline. <br/> 
**Sweep Sensitivity:** Fin sweep provides moderate stability control (**61% variation** relative to baseline) with only minor velocity drag penalties.<br/>
**Tip Chord Tuning:** Tip chord exhibits minimal overall performance impact (**16% sensitivity**), making it an ideal parameter for structural and manufacturing fine-tuning.<br/>

## Parameters Evaluated
| **Parameter** | Test Range | Baseline Value | Stability Impact |<br/>
| **Fin Span** | 7 - 14 cm | 10 cm | High (90% change) |<br/>
| **Fin Sweep** | 3 - 18 cm | 15 cm | Moderate (61% change) |<br/>
| **Tip Chord** | 4 - 30 cm | 7.5 cm | Low (16% change) |<br/>

## Project Structure

**[4_in_high_power_rocket_design_review.pdf](./4_in_high_power_rocket_design_review.pdf)**   # Standardized 3x3 matrix PDF report<br/>
**[README.md](./README.md)**                                                                 # Project overview and key takeaways<br/>
**[4_in_rocket_design.ork](./4_in_rocket_design.ork)**                                       # Rocket design and simulation<br/>
**[Aero_Performance/Graphs](./Aero_Performance/Graphs)**                                     # Graphs of varying geometries vs apogee, max velocity, and stability <br/>
