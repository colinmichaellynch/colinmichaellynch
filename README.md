<img src="https://raw.githubusercontent.com/colinmichaellynch/images/main/Picture3.png" align="right" width="300" style="margin-left:20px;">

<table>
<tr>
<td><strong><sub></sub></strong><strong>Dr. Colin Lynch</strong></td>
</tr>
</table>

Postdoctoral Fellow — Collective Logic Lab, Arizona State University  
Working with Dr. Bryan Daniels

Statistical Consultant — Terra Integrated Solutions     
Working with Dr. Rene Villalobos

My research integrates statistical methodology, optimal experimental design, empirical behavioral ecology, and computational modeling to study complex adaptive systems. Across biological and engineered systems, I develop methods for designing more informative experiments, reducing sampling costs, and uncovering the mechanisms that generate collective behavior.

---

# Research Clusters

## Empirical Studies of Social Insects

<img src="https://raw.githubusercontent.com/colinmichaellynch/images/main/Picture1.png" align="right" width="420" style="margin-left:20px;">

My early research focused on empirical behavioral ecology, particularly how division of labor emerges in ant colonies. These studies combined behavioral observation, spatial analysis, and statistical modeling to understand how colony-level organization emerges from the interactions of individuals.

Relevant publications:

- [Ants in isolation: obstacles to testing worker responses to task stimuli outside of the colony context](https://link.springer.com/article/10.1007/s00040-019-00692-1)
  
- [Synergistic negative effects between a fungicide and high temperatures on homing behaviours in honeybees](https://royalsocietypublishing.org/rspb/article/291/2019/20240040/104420)
  
- [Ontogeny of energy use in harvester ant colonies, and the metabolic expense of colony growth](https://royalsocietypublishing.org/rspb/article/292/2039/20242534/105559)

Working closely with empirical behavioral datasets revealed how difficult it can be to design experiments that reliably detect the mechanisms underlying collective behavior. Field and laboratory studies are often constrained by limited observation time, limited numbers of colonies, and high variability among individuals and environments. These experiences highlighted a broader methodological gap: while many statistical tools exist for analyzing data after it has been collected, there are comparatively few practical frameworks that guide researchers in designing experiments that maximize the information obtained from limited observations. These challenges motivated much of my later work on optimal experimental design and statistical methodology.

---

## Optimal Design of Experiments

<img src="https://raw.githubusercontent.com/colinmichaellynch/images/main/flowDiagram.webp" align="right" width="450">

A major focus of my research is the development of (and the dissemination of existing) experimental design methods that reduce the cost and sample size required for scientific experiments while maintaining strong inferential power.

Relevant publications:

- [More individuals or more groups? Incorporating sampling effort, statistical power, and model accuracy when designing experiments](https://link.springer.com/article/10.1007/s00265-025-03640-1)

- [Piecewise-Continuous Sampling: A Method for Minimizing Bias and Sampling Effort for Estimated Metrics of Animal Behavior](https://onlinelibrary.wiley.com/doi/full/10.1111/eth.70021)  

- [Optimal experimental designs for hypothesis testing with multiple factors: maximising power for the biological sciences](https://www.inderscienceonline.com/doi/abs/10.1504/IJEDPO.2024.140455)  

- [Guidelines for the use and reporting of experimental statistics in additive manufacturing: An assessment of current practices](https://accscience.com/journal/ESAM/1/4/10.36922/ESAM025340021)

- [A User's Guide for a Power Analysis by Simulation](https://www.researchgate.net/publication/377842822_A_User's_Guide_for_a_Power_Analysis_by_Simulation)
  
These projects develop methods for determining how experimental effort should be distributed across individuals, treatments, and time in order to maximize statistical power while minimizing sampling cost. The approaches draw heavily on techniques from industrial engineering and operations research, including control charts, power analysis, and optimization algorithms. These methods have applications across biological field studies, behavioral ecology, engineering research, and data-driven R&D environments.

---

## Statistical Frameworks for Methodological Problems

<img src="https://raw.githubusercontent.com/colinmichaellynch/images/main/figure1Composite.png" align="right" width="500" style="margin-left:20px;">

Another major thread of my work focuses on developing statistical frameworks that address methodological challenges across disciplines, particularly in cases where experimental design, sampling strategies, and inference interact in subtle ways.

One example is the development of improved sampling strategies for behavioral observations. Behavioral data are often collected through time‐budget sampling protocols that trade off observational effort against bias in estimated behavioral metrics. To address this problem, I developed piecewise-continuous sampling methods that reduce inferential bias while dramatically lowering the observation effort required to estimate behavioral statistics.  

The algorithmic framework for selecting sampling intervals is implemented in the open-source repository:

- https://github.com/colinmichaellynch/Selecting-Intervals-for-Piecewise-Continuous-Sampling  

This package provides tools for identifying optimal sampling schedules that preserve statistical accuracy while minimizing the amount of data that must be collected.

Another methodological contribution addresses the design of nutritional experiments. In the paper

- [Minimizing inferential bias in the theory and design of nutritional experiments through the application of the equilateral mixture triangle](https://www.biorxiv.org/content/10.64898/2025.12.06.692245v1.abstract)

I reintroduce the equilateral mixture triangle (EMT) framework for experimental design within the geometric framework of nutrition. Traditional mixture experiments are often implemented using right-angled mixture triangles, which can introduce distortions in the interpretation of nutritional landscapes and bias inference about nutrient interactions. The EMT framework provides a geometrically consistent representation of mixture spaces that preserves the underlying structure of compositional data and improves interpretability of nutritional response surfaces.

A second line of work focuses on equivalency testing frameworks for engineering qualification and requalification, particularly in additive manufacturing. In these systems, process changes such as machine replacement, powder changes, facility relocation, or environmental drift can trigger costly requalification procedures.

To address this problem, I have developed statistical frameworks for both univariate and multivariate equivalency testing that allow manufacturers to determine whether two processes produce statistically equivalent parts while minimizing the number of required test builds. A manuscript describing this framework is currently in preparation.

The associated tools are implemented in the following repositories:

- https://github.com/colinmichaellynch/AMEquivalency  

This package implements statistical methods for assessing equivalency between additive manufacturing processes using tolerance intervals and hypothesis testing frameworks tailored to engineering qualification problems.

- https://github.com/colinmichaellynch/MultivariateEquivalency  

This repository extends equivalency testing to multivariate settings, allowing multiple correlated quality metrics to be evaluated simultaneously when determining whether a manufacturing process remains within acceptable performance bounds.

Together, these frameworks aim to improve experimental rigor, reduce unnecessary testing costs, and support more reliable decision-making in both scientific research and industrial engineering applications.

---

## Modeling Complex Adaptive Systems and Collective Transitions

<img src="https://raw.githubusercontent.com/colinmichaellynch/images/main/Figure2%20(1).png" align="right" width="420" style="margin-left:20px;">

My current research focuses on modeling collective behavior and phase transitions in biological systems, particularly social insect colonies.

Confronting empirical systems also revealed that many commonly used models assume forms of optimality that may not hold in real biological systems. Investigating these discrepancies motivated the development of alternative modeling approaches. This includes exploring how machine learning ensembles can be reorganized to better represent collective dynamics, examining how stopping thresholds interact with starting thresholds in task allocation models, and investigating how different thresholding functions influence properties such as system scalability and robustness.

- [Casting: A Bio-Inspired Method for Restructuring Machine Learning Ensembles](https://www.comses.net/codebases/471369f9-a7e2-4519-844c-cf1afebc1d43/releases/1.0.0/)  

- [Generalizing the response and satisfaction threshold models for multiple task types: A maximal entropy approach](https://www.biorxiv.org/content/10.1101/2024.04.26.591219v1.abstract)  

- [Stop and go: exploring alternative mechanisms for task allocation in social insects - response and satisfaction thresholds trade off cost, accuracy, and speed differently](https://www.biorxiv.org/content/10.1101/2024.05.13.593812v1.abstract)

Although much of this work is motivated by social insect systems, my modeling efforts extend beyond these biological examples. For example, I have also investigated how environmental variability and resource heterogeneity may have shaped the persistence of cooperation in human societies, including models exploring the ecological conditions that may have supported cooperative behavior on Easter Island:

- [Environmental stochasticity, resource heterogeneity, and the evolution of cooperation](https://www.comses.net/codebases/4aff6e81-62fd-45b6-9182-feafd2768a75/releases/1.3.0/)

Currently, I am working as part of a larger effort to understand collective systems using the language of nonlinear dynamics, phase transitions, and bifurcation theory. In many biological collectives, small changes in environmental conditions, interaction strengths, or individual thresholds can cause abrupt transitions between macroscopic behavioral regimes, such as the onset of coordinated foraging, alarm cascades, or collective decision-making. This perspective is developed further in:

- [Tuning regimes in ant foraging dynamics depend on the existence of bistability](https://royalsocietypublishing.org/rsif/article/23/235/20250838/480257)

This line of research contributes to a broader framework for studying collective transitions across biological systems, where individual-level interactions generate emergent system-level states that can shift between regimes in response to changing environmental or internal conditions.
  
---

# Integrating These Research Areas

Although these research programs span biology, engineering, and statistics, they address a common question:

How can we efficiently uncover the mechanisms driving complex systems?

-Empirical studies reveal the structure and variability of real biological systems.  
-Experimental design methods ensure that limited observational resources are used efficiently.  
-Statistical frameworks allow rigorous inference from complex datasets.  
-Computational models allow exploration of mechanisms that cannot easily be manipulated experimentally.

Together, these approaches provide an integrated strategy for understanding collective phenomena in complex adaptive systems.

---

# Contact

| Platform | Link |
|---|---|
| Email | cmlynch2@asu.edu |
| LinkedIn | https://www.linkedin.com/in/colinmichaellynch/ |
| ResearchGate | https://www.researchgate.net/profile/C-Lynch |

---

<p align="center">
  <img width="420" src="https://raw.githubusercontent.com/colinmichaellynch/images/main/netlogoSim.gif">
  <img width="420" src="https://user-images.githubusercontent.com/61156429/211726471-9fee64e6-1dc8-4719-9aea-530528ec39a1.gif">
</p>

<p align="center">
  <img width="400" src="https://user-images.githubusercontent.com/61156429/211883975-0946d5e5-95f6-47ae-81f8-74b415f5cdc7.gif">
  <img width="400" src="https://user-images.githubusercontent.com/61156429/227611733-72318322-7845-475b-a4f4-497e3b092d33.gif">
</p>
