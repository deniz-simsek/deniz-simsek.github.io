---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
redirect_from:
  - /publications
---

## Journal Publications
---
**Deniz Şimşek**, M. Selim Aktürk. Resilient Airline Scheduling while Minimizing Delay Risks. *Transportation Research Part C*, 2022.  
Available at: <a href="https://doi.org/10.1016/j.trc.2022.103734" target="_blank">https://doi.org/10.1016/j.trc.2022.103734</a>

<details>
  <summary>Abstract</summary>
  <div style="font-size: 0.8em; font-weight: 400; margin: 15px;"> 
  Airlines tend to design their flights schedules with the primary concern of the minimization of operational costs. However, the recently emerging idea of resilient scheduling defined as staying operational in case of unexpected disruptions and adaptability should be of great importance for airlines as well due to the high opportunity costs caused by the flight cancellations and passenger inconvenience caused by delays in the schedule. In this study, we integrate resilient airline schedule design, aircraft routing and fleet assignment problems with uncertain non-cruise times and controllable cruise times. We follow a data-driven method to estimate flight delay probabilities to calculate the airport congestion coefficients required for the probability distributions of non-cruise time random variables. We formulate the problem as a bi-criteria nonlinear mixed integer mathematical model with chance constraints. The nonlinearity caused by the fuel consumption and CO2 emission function associated with the controllable cruise times in our first objective is handled by second order conic inequalities. We minimize the total absolute deviation of the aircraft path variability’s from the average in our second objective to generate balanced schedules in terms of resilience. We compare the recovery performances of our proposed schedules to the minimum cost schedules by a scenario-based posterior analysis.
  </div>
</details>

  * Finalist, 2022 INFORMS AAS Student Presentation Competition

## Working Papers
---
**Deniz Şimşek**, Chenguang (Allen) Wu, Achal Bassamboo, Ohad Perry. A Unified Fluid Model for Large Service Systems with Patience- or Delay-Dependent Service Times.  (Job Market Paper)

<details>
  <summary>Abstract</summary>
  <div style="font-size: 0.8em; font-weight: 400; margin: 15px;"> 
  We consider queueing systems with a single pool with many servers, assuming the service time of each customer depends on the delay of that customer in queue. Such dependence can be due to the customers having patience for waiting that depends on their individual service requirement, or due to having their service-time distribution be a function of the time spent in queue. We refer to the former dependence mechanism as "exogenous dependence" and to that latter as "endogenous dependence." Since exact analysis of the stochastic system under either dependence mechanism is intractable, we propose a deterministic approximation for the (mean) queueing dynamics, and refer to that approximation as a Unified Fluid Model (UFM), since it captures both dependence mechanisms simultaneously. When the arrival rates are constant, we characterize conditions for the existence of a unique stationary point for the UFM, and prove that those conditions always hold when the dependence is exogenous. However, the UFM may possess multiple equilibria, with each equilibrium point being either locally stable so that any trajectory of the UFM passing through a neighborhood of that point will converge to it or unstable, so that any trajectory is repelled away from that point. The implications for the stochastic system of the UFM having multiple equilibrium points are two-fold. First, the stochastic fluctuations in steady state may be an order of magnitude larger than the typical fluctuations in many-server queueing systems. Second, the system may experience congestion collapse, namely, the system is substantially more congested than it should be under the current staffing and arrival rate, e.g., an underloaded system may get "stuck" in a severe overload state. Simulation examples verify the accuracy of the UFM, and demonstrate the implications of our analyses to the stochastic system that the UFM approximates.
  </div>
</details>

## Works in Progress
---
**Deniz Şimşek**, Achal Bassamboo, Ohad Perry. Design and Control of Large Service Systems with Delay-Dependent Service Times.

<details>
  <summary>Abstract</summary>
  <div style="font-size: 0.8em; font-weight: 400; margin: 15px;"> 
Service systems often exhibit complex dynamics when customer service times depend on the delay experienced in queue, a phenomenon observed across various settings such as healthcare and hospitality. This delay-dependent service time introduces non-Markovian dynamics that render exact analysis of large service systems intractable. Deterministic fluid models approximating the system dynamics uncover some operational challenges arising from delay-dependence. These systems can exhibit multi-stability, where the queue fluctuates between multiple equilibria. In large systems, these transitions become infrequent, potentially leading to prolonged periods of severe congestion referred as congestion collapse. Conversely, in smaller systems, the system frequently shifts between equilibria, causing high variability. To mitigate these issues, we propose two tailored strategies: For large systems, we introduce the “slingshot policy”, a dynamic control that alternates between first-come-first-served (FCFS) and last-come-first-served (LCFS) scheduling to stabilize the system at the more desirable equilibrium. For smaller systems, we propose a “depooling mechanism”, where the service pool is strategically divided into smaller, uni-stable subsystems, effectively eliminating multi-stability at the design stage. Our framework provides actionable solutions for system design and control. The proposed approaches are supported by both theoretical analysis and simulation studies, offering practical insights to improve the stability, reliability, and efficiency of service systems affected by delay-dependent dynamics.
  </div>
</details>

**Deniz Şimşek**, Achal Bassamboo, Martin Lariviere. Burning Daylight: Rational Abandonments under a Time Budget.
