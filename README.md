# 4-in-rocket-fin-optimization
An aerodynamic sensitivity analysis evaluating 

--

## Final Report
View the complete single-page trade study
**[4_in_high_power_rocket_aero_performance_sensitivity.pdf](./4_in_high_power_rocket_aero_performance_sensitivity.pdf)**

--

## Key Takeaways
**Span Dominance:** Fin span is the primary driver of vehicle stability, accounting for up to a **90% drop** in stability margin when reduced below baseline. 
**Sweep Sensitivity:** Fin sweep provides moderate stability control (**61% variation** relative to baseline) with only minor velocity drag penalties. 
**Tip Chord Tuning:** Tip chord exhibits minimal overall performance impact (**16% sensitivity**), making it an ideal parameter for structural and manufacturing fine-tuning.

## Parameters Evaluated
| Parameter | Test Range | Baseline Value | Stability Impact |
**Fin Span** | 7 - 14 cm | 10 cm | High (90% change) |
**Fin Sweep** | 3 - 18 cm | 15 cm | Moderate (61% change) |
**Tip Chord** | 4 - 30 cm | 7.5 cm | Low (16% change) |

## Project Structure
'''text
4_in_high_power_rocket_design_review.pdf   # Standardized 3x3 matrix PDF report
README.md                                  # Project overview and key takeaways
4_in_rocket_design.ork                     # Rocket design and simulation
