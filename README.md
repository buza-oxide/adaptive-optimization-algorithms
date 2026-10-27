# Adaptive Optimization Algorithms

## Research Overview
This project was conducted under the BIT-SIPAR (Summer Internship Program for Advanced Research) at Birla Institute of Technology, Mesra, under the supervision of Dr. Lakhsman Mahto, Assistant Professor, Department of Quantitative Economics & Data Science.

The research studies gradient-based optimization methods and adaptive step-size strategies, comparing their convergence behaviour and computational performance using Python.

## Research Objectives
- Study Gradient Descent, Steepest Descent, and Newton's Method.
- Examine adaptive step-size strategies, including Exact Line Search, Bisection Line Search, and Backtracking Line Search.
- Investigate Step Size Hedging as an adaptive learning-rate strategy.
- Compare implemented algorithms using iteration count, execution time, and final Mean Squared Error (MSE).

## Methods and Tools
- **Methods:** Gradient-based optimization and adaptive step-size selection
- **Python libraries:** NumPy, Pandas, Matplotlib
- **Evaluation metrics:** Iterations, runtime, final objective value (MSE)
- **Dataset:** MA201 academic dataset

## Experimental Results
The report records the following results for the implemented algorithms:

| Algorithm | Iterations | Final MSE | Runtime (seconds) |
|---|---:|---:|---:|
| Gradient Descent | 1000 | 0.043727 | 0.04618 |
| Exact Line Search | 1000 | 0.043406 | 0.07190 |
| Bisection Line Search | 95 | 0.043406 | 0.10579 |
| Backtracking Line Search | 95 | 0.043406 | 0.01958 |
| Step Size Hedging | 89 | 0.043406 | 0.00776 |

In this experiment, Step Size Hedging achieved the lowest reported runtime and required the fewest iterations among the compared methods. These results apply to the specific dataset and implementation described in the report.

## Repository Contents
- Research report
- Python implementation and supporting analysis, where available
- Experimental results and visualizations, where available

## Author
**Abuzar Faisal Mazhar**  
Integrated MSc Quantitative Economics & Data Science  
Birla Institute of Technology, Mesra

**Research programme:** BIT-SIPAR — Summer Internship Program for Advanced Research
