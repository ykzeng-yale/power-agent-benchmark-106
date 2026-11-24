# Power Agent Benchmark

106 reference problems for statistical study design, power, sample size, and prediction-model validation.

| Tier | Topic | Tasks |
| --- | --- | ---: |
| 1 | Basic comparisons | [30](tasks/tier-1.json) |
| 2 | Regression and other models | [35](tasks/tier-2.json) |
| 3 | Advanced study designs | [20](tasks/tier-3.json) |
| 4 | Prediction-model development or validation | [21](tasks/tier-4.json) |

Each JSON record contains an `id`, a `question`, and a `ground_truth` answer. Questions state the assumptions and analysis method used for the reference. Sample sizes are counts in the units indicated by the answer fields. Power and risks are proportions. Simulation-based reference values include Monte Carlo uncertainty when requested.

The companion [Power Agent research workflow](https://github.com/ykzeng-yale/power-agent-public) is available separately.
