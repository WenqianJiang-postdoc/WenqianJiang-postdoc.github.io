---
layout: archive
title: <span style="font-size:19px;">Sample-Oriented Robust Strategy Design with Performance Guarantees</span>
permalink: /research1/
author_profile: true
# redirect_from:
#   - /resume
---
To account for growing uncertainties in decision-making, researchers have developed different modeling and solution techniques, such as scenario-based optimization, chance-constrained programming (CCP), robust optimization (RO), and distributionally robust optimization (DRO). In practice, stakeholders rely on samples/data for uncertain realizations to select representative scenarios, estimate probability distributions, or construct uncertainty/ambiguity sets, which are then used in the above methods to derive optimal decisions. As such, the performance of these decisions is fundamentally influenced by the quantity and quality of employed samples. However, the mechanisms through which samples influence various uncertainty modeling and solution techniques remain poorly understood. Therefore, stakeholders lack clear guidance on tailoring sample collection/selection strategies to implement the chosen techniques effectively. 

* **Performance-guaranteed data collection for probability distribution dependent tasks**
<br>
Estimating probability distribution information from historical data is an essential tool for decision-making under parameter uncertainty. An insufficient amount of collected data may lack representativeness, potentially leading to over-optimistic or over-pessimistic decisions, whereas an excessive volume of data can be costly to collect. To guide this trade-off, we establish the sample complexity required to guarantee, with high probability, that the achieved objective value using empirical distributions lies within an acceptable deviation from its optimum with perfect distributions. [paper link](https://doi.org/10.1109/TSG.2023.3308686)

* **Statistically feasible data selection for robust optimization tasks**
<br>
Classical methods to deal with uncertainties include CCP, RO, and DRO. The performance of CCP heavily relies on the accuracy of distributional information about uncertainty, RO optimizes the worst-case realization of uncertainty and its solution is often too conservative, while DRO requires a well-specified ambiguity set and often suffers from computational challenges. To overcome these limitations, we develop a statistically feasible RO framework by designing a “good" uncertainty set, which leads to an effective trade-off between solution optimality and robustness. Specifically, we first identify a high-probability region for the uncertain parameters. We then strategically calibrate this region to obtain an uncertainty set with finite-sample statistical guarantees. To enhance performance, we further tailor the construction of this set by incorporating the specific constraint information of downstream problems. Empirical evaluations across applications, such as thermostatically controlled loads schedule [paper link](https://doi.org/10.1109/TSG.2023.3238997), economic dispatch [paper link](https://doi.org/10.1109/TPWRS.2023.3267097), and unit commitment [paper link](https://doi.org/10.1109/TPWRS.2024.3351435), demonstrate that our method achieves lower costs with acceptable constraint violation compared to conventional methods.
<br>
See more details in my [Presentation](/stafeapresentation.pdf){:target="_blank"}.