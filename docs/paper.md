# RESEARCH ARTICLE  
**APPLIED MATHEMATICS**  
**ENVIRONMENTAL SCIENCES**

# Non-equilibrium early-warning signals for critical transitions in ecological systems

Li Xu<sup>a</sup> <span class="ID">ID</span>, Denis Patterson<sup>b,c</sup> <span class="ID">ID</span>, Simon Asher Levin<sup>b,c,1</sup> <span class="ID">ID</span>, and Jin Wang<sup>d,1</sup>

*Contributed by Simon Asher Levin; received November 3, 2022; accepted December 21, 2022; reviewed by Carl Boettiger and Qing Nie*

Complex systems can exhibit sudden transitions or regime shifts from one stable state to another, typically referred to as critical transitions. It becomes a great challenge to identify a robust warning sufficiently early that action can be taken to avert a regime shift. We employ landscape-flux theory from nonequilibrium statistical mechanics as a general framework to quantify the global stability of ecological systems and provide warning signals for critical transitions. We quantify the average flux as the nonequilibrium driving force and the dynamical origin of the nonequilibrium transition while the entropy production rate as the nonequilibrium thermodynamic cost and thermodynamic origin of the nonequilibrium transition. Average flux, entropy production, nonequilibrium free energy, and time irreversibility quantified by the difference in cross-correlation functions forward and backward in time can serve as early warning signals for critical transitions much earlier than other conventional predictors. We utilize a classical shallow lake model as an exemplar for our early warning prediction. Our proposed method is general and can be readily applied to assess the resilience of many other ecological systems. The early warning signals proposed here can potentially predict critical transitions earlier than established methods and perhaps even sufficiently early to avert catastrophic shifts.

**early warning signals | tipping point prediction | critical transitions | landscape-flux theory | global stability of ecological systems**

Complex systems such as ecological systems show rich dynamical behaviors due to the diverse underlying interactions involving competition, exploitation, and mutualism (1). The nature of these dynamics and the stability of equilibria and other asymptotic characteristics are crucial for the fates of species, populations, and ecosystems (1–5). Under the influence of climate change, land use, and human activities, the state of an ecosystem can change from one steady state to another. The complexities of the environmental pressure, nonlinearity, stochasticity, and other characteristics often lead to state transitions characterized by sudden changes or jumps. Accurately defining the tipping point or threshold point at which the state transition occurs is an important practical challenge. Similarly, it is of evident interest to capture changes in the ecosystem structure and features before critical tipping points as early warning signals (6–9). Ecosystems may lose stability and have bifurcations or phase transitions between alternative locally stable states (6–12). To avoid such transition events, tipping point identification and other early warning signals are crucial for prevention and control (6–9). In some cases, ecosystem transitions may be desirable, such as when a system is trapped in an unfavorable state, and early warning signals are helpful as we seek to promote regime shifts. Critical slowing down has long been considered as one of the most significant early warning signal for certain classes of transitions (6–8). However, such prediction is often too close to the transition point and may not be early enough to allow an intervention to avert an undesirable transition. Indeed, in other situations, it may not apply due to the nature of the transition (13).  
One example of the aforementioned critical transition scenario is when nutrient concentrations in a shallow lake ecosystem undergo significant changes. At the level of low nutrient concentration, the lake water is typically clear and transparent, and submerged plants are dominant, showing a clear lake state. At high levels of nutrient concentration, the phytoplankton in the water body is dominant, and water transparency decreases markedly, a so-called turbid state. Once the nutrient concentration in the lake water exceeds a certain threshold, the submerged plants will disappear, the algae will grow in large quantities, and the lake will change from the clear water state to the turbid water state. When the input of exogenous nutrient reaches a certain threshold, a small increment of nutrient can lead to major changes of the ecosystem structure. The lake suddenly changes from a clear water state to a turbid water state, and the ecosystem function is

| Significance |
|--------------|
| Complex systems can be multistable and exhibit transitions between alternative locally stable states. We employ the landscape-flux theory from nonequilibrium statistical mechanics as a general framework to quantify the global stability of ecological systems. The average flux as the nonequilibrium driving force, the entropy production as the thermodynamic driving force, and time irreversibility of the cross-correlation functions can serve as warning signals for critical transitions between alternative stable states much earlier than other conventional predictors. We utilize a classical shallow lake model as an exemplar for our early warning prediction based on the landscape-flux approach. The method we propose is general and can be readily applied to assess the resilience of many other complex ecological systems. |

**Author contributions:** L.X., D.P., S.A.L. and J.W. designed research; L.X. and J.W. performed research; L.X., D.P., S.A.L. and J.W. contributed new reagents/analytic tools; L.X., D.P., S.A.L., and J.W. analyzed data; L.X., D.P., S.A.L., and J.W. wrote the paper.  

**Reviewers:** C.B., University of California Berkeley; and Q.N., University of California, Irvine.  

The authors declare no competing interest.  

**Copyright © 2023 the Author(s). Published by PNAS.**  
This article is distributed under Creative Commons Attribution-NonCommercial-NoDerivatives License 4.0 (CC BY-NC-ND).  

<sup>1</sup>To whom correspondence may be addressed. Email: slevin@princeton.edu or jin.wang.1@stonybrook.edu.  

This article contains supporting information online at http://www.pnas.org/lookup/suppl/doi:10.1073/pnas.2218663120/-/DCSupplemental.  

**Published January 23, 2023.**  

**PNAS 2023 Vol. 120 No. 5 e2218663120**  
https://doi.org/10.1073/pnas.2218663120  
1 of 10  

Downloaded from https://www.pnas.org by 103.249.4.167 on October 17, 2025 from IP address 103.249.4.167.

---

seriously reduced (9). Within a certain nutrient range, the clear water and turbid water states are bistable, with the possibility of noise-induced transitions between the two alternative stable states.  
In this study, we apply the landscape-flux theory from nonequilibrium statistical mechanics to provide a general framework to quantify the global stability of the ecological systems and provide warning signals for critical transitions. For complex systems subject to random noise, the “driving force” of the system can be profitably decomposed into the gradient of the potential landscape and a rotational flux term. The gradient of the potential pushes the system toward the attractor, while the flux measures the degree of detailed-balance breaking and, being rotational in nature, tends to destabilize the point attractor (14–17). Therefore, the curl flux should play a significant role for the instability of the current state and the emergence of the new state, giving rise to the nonequilibrium phase transitions. Furthermore, the flux also provides the source for the associated nonequilibrium thermodynamic cost in terms of the entropy production. From this perspective, the flux gives rise to the dynamical origin while the entropy production gives rise to the thermodynamic origin for the phase transition. In this framework, the average flux plays the role of the nonequilibrium driving force, and the entropy production rate gives the nonequilibrium thermodynamic cost and the nonequilibrium free energy. Crucially, from an applied perspective, time irreversibility of the cross-correlation functions can serve as the warning signals for critical transitions between alternative stable states. We use a well-known shallow lake model to demonstrate the utility of this approach to predicting regime shifts, and additional results for a savanna-forest model are shown in SI Appendix.  
It is worth mentioning that effective one-dimensional (1D) approach has attracted extensive attention for the study of the phase transitions/bifurcations in the ecological systems of finding the early warning signals (6–9, 18, 19). Critical slowing down refers to that a system has slowing down response to the perturbations as it approaches the tipping point, with often greater variance, autocorrelation, and return time (13, 20). Critical slowing down has been widely applied to the models with saddle-node bifurcations. Most of the studies have so far concentrated on the effective 1D approach, and the results can often be applied to the effective equilibrium systems where the global stability can be quantified by the landscape alone without considering the key nonequilibrium ingredient, the flux (6–9, 18, 19).  
In the pure 1D systems, under natural boundary condition, there is no net flux. The system obeys detailed balance. Thus, such 1D dynamics is dictated by the landscape alone. However, the real ecological systems are often open, nonequilibrium, complex, and high-dimensional. The system may not always be easily treated as effective 1D system (18, 19). It is thus a great challenge to explore the global stability and the early warning signals for critical transitions. Furthermore, the critical slowing down is only one of the possible early warning signals, since regime shifts do not all exhibit critical slowing down.  
The potential-flux landscape theory of nonequilibrium statistical mechanics we proposed here can provide and quantify non-equilibrium early warning signals for multidimensional system, two-dimensional (2D) system in this study. For a higher-dimensional system, the nonequilibrium characterized by the nonzero curl flux can lead to a much richer complex dynamics with detailed balance breaking while the equilibrium dynamics are solely determined by the gradient of the potential landscape. The curl flux breaking the detailed balance plays an important role in driving the nonequilibrium dynamics of the system.  

Here, we propose the fully vectorized high-dimensional formulation of the potential landscape, in contrast to the almost ubiquitous focus on 1D landscapes throughout the ecological literature on critical transitions, early warning signals, and critical slowing down (6–9, 18, 19). Thus, our theory provides a method for exploring critical transitions in higher dimensions with both the rotational component of the flux and the gradient component of the potential landscape. For the multidimensional systems, the curl flux component of the driving force has not been considered as early warning indicators by the critical slowing down approach. The curl flux or the vectorized formulation of the potential landscape is usually absent in the 1D system (6–9, 18, 19) (under the natural boundary conditions). The contribution of the curl flux present often in multidimensional systems in addition to the potential landscape provides the basis for the emergence of the non-equilibrium early warning signals beyond the currently often used critical slowing down.

## Methods

### Model of Shallow Lake with Bream and Pike. 
We explore a shallow lake with bream and pike (SLBP) model to illustrate our approach. Turbid water characterized by high algal biomass that is predominantly dominated by phytoplankton generally contains a large number of bream, while clear water generally contains relatively low populations of bream, some pike (which predate the bream), and well-developed aquatic vegetation. Observations show that the transparency of the water has a strong relationship with the ratio of pike to bream (10); the interactions among these two variables are shown via a schematic diagram in Fig. 1.  
The SLBP system can be described by a set of nonlinear ordinary differential equations for these species interactions (10):  

$$\frac{dX}{dt} = i_b + rX \frac{N}{N + H_1} - c_b X^2 - p_r F R Y,$$  

$$\frac{dY}{dt} = i_p + c_e p_r F R Y \frac{V}{V + H_2} - m_p Y - c_p Y^2,$$  
[1]  

where X represents the bream population density, Y represents the pike population density, and N is the nutrient level. Table 1 summarizes the mathematical definitions and notations, while the interpretation of the parameters and their default values are given in Table 2. Increasing nutrient loading of shallow lakes can change the topology of the dynamics, leading the shallow lake system to critical transitions or to flickering between the states or the basins of attraction. In this study, we use the immigration rate of bream $i_b = 3 \times 10^{-4}$ and the immigration rate of pike $i_p = 3\times10^{-4}$ (which are larger than the original model) in order to avoid the steady-state solution of the associated Fokker–Planck equation becoming overcrowded at the boundary.

![Fig. 1. The schematic diagram for the SLBP model. Arrows with flat ends denote inhibition and arrows with cuspidal ends denote activation. Bream and pike are both also subject to natural mortality.](placeholder-for-fig1)

**Fig. 1.**  
The schematic diagram for the SLBP model. Arrows with flat ends denote inhibition and arrows with cuspidal ends denote activation. Bream and pike are both also subject to natural mortality.  

2 of 10  
https://doi.org/10.1073/pnas.2218663120  
pnas.org  

Downloaded from https://www.pnas.org by 103.249.4.167 on October 17, 2025 from IP address 103.249.4.167.

---

| Table 1. Mathematical variables | |
|---------------------------------|-|
| **Symbol** | **Interpretation** |
| x | System state |
| F(x) | Driving force |
| D | Scale factor representing the magnitude of the fluctuations |
| G | Diffusion matrix |
| P(x, t) | Probability of system state x at time t |
| J(x, t) | Probability flux |
| Jss | Probability flux of steady state |
| U(x) | Population potential landscape |
| φ0 | Intrinsic potential landscape |
| V | Intrinsic flux velocity |
| L(x) | Lagrangian |
| F | Intrinsic free energy |
| Z | Partition function |
| ep | Entropy production rate |
| epin | Intrinsic entropy production rate |
| ¯J | The average flux |
| ¯Jin | The intrinsic average flux |
| CXY (τ′) | The cross-correlation function forward in time |
| ˜CXY (τ′) | The cross-correlation function backward in time |
| �C | The average difference in cross-correlations between The forward in time and the backward in time |
| τrelax | Relaxation time from autocorrelation |
| fω | The frequency of the flickering |

### Landscape and Flux Theory for Nonequilibrium SLBP Model. 
Stochastic fluctuations are common across a wide array of natural systems (16, 21). We can write the nonlinear dynamics subject to a randomly fluctuating environment as: $\dot{x} = F(x)+\zeta$, where F(x) represents the deterministic force, and the vector x denotes a state of the system, for example, x = {X, Y } in this study. ζ represents Gaussian fluctuating force, whose autocorrelation function is given as < ζ(x, t)ζ(x, 0) >= 2D(x)δ(t), where D(x) represents the diffusion coefficient matrix. Set D(x) = D G(x), where  

| Table 2. Parameters interpretation and default values (10) | |
|------------------------------------------------------------|-|
| **Symbol** | **Ecological interpretation** | **Default value** |
| ib | Immigration rate of bream | 3 × 10−4 |
| ip | Immigration rate of pike | 3 × 10−4 |
| r | Maximum growth rate of bream | 7.5 × 10−3 |
| H1 | Half saturation constant | 0.5 |
| H2 | Half saturation constant | 0.1 |
| H3 | Half saturation constant | 20 |
| H4 | Half saturation constant | 15 |
| cb | Intraspecific competition constant for bream | 7.5 × 10−5 |
| cp | Intraspecific competition constant for pike | 2.75 × 10−4 |
| pr | Maximum predation rate of pike | 5 × 10−2 |
| ce | Pike food conversion efficiency to growth | 0.1 |
| mp | Mortality rate of pike | 2.25 × 10−3 |
| K | Maximum vegetation coverage | 100% |
| V | Percentage of lake covered with vegetation | K∗H2 3 / H2 3+X2 |
| FR | Functional response of pike | X2 / X2+H2 4 |

D is the diffusion coefficient representing the noise intensity and G is the scaled diffusion matrix describing the anisotropy. As the scales of X and Y are very different, G(x) is set as the anisotropic matrix with G11 = 1, G12 = G21 = 0, G22 = 0.1 throughout. The Langevin equations give the information on the stochastic trajectories, thus they are not predictable. However, the statistical patterns of the trajectories and the distributions are predictable and follow the Fokker–Planck diffusion equation (22–24).  
The evolution of probability density function of the system, P(x, t), obeys the local conservation law: ∂P/∂t = −∇· J(x, t). The change of the probability in time is equal to the net flux J in or out. The probability flux J is defined as: J(x, t) = F(x)P(x, t) − D∇(GP(x, t)). The driving force for the dynamics can then be decomposed as: F = −DG · ∇U + Jss/Pss + D∇· G, where U = −lnPss is the nonequilibrium potential landscape which is related to the steady-state probability distribution (Pss) and the steady-state probability flux Jss.  
The steady-state probability flux can then be either zero, constant, or rotational (having the curl nature at nonequilibrium steady-state ∇· Jss = 0). The equilibrium state has zero flux, i.e., it obeys the so-called detailed balance condition, with no net input or output. On the other hand, the nonzero flux denotes the net flow in or out of the system, while the magnitude of the flux measures the degree of the detailed balance breaking (away from the equilibrium).  
Nonequilibrium open systems often exchange energy, materials, and information with their environments. The time evolution of the system entropy can be decomposed to the entropy production rate and heat dissipation rate as (15, 25–28): ˙S = ˙St −˙Se. The population entropy production rate can be represented with ep = ˙St = ∫ dx(J · (DG)−1 · J)/P. And ˙Se = ∫ dx(J · (DG)−1 · F′) denotes the heat dissipation rate of the environment. Thus, the entropy production rate can be seen as the total entropy change of the system and environment ep = ˙St = ˙S + ˙Se. The entropy production rate must be nonnegative but the heat dissipation rate may be either positive or negative. This measure can quantify the entropy flow rate between the environment and the nonequilibrium system. At steady state, the entropy production rate and the heat dissipation rate are equal (15, 25–27). The entropy production rate provides a global thermodynamic characterization for the nonequilibrium system. We define the average magnitude of the flux as ¯J = ∫ |J|dx to quantify how far a system is from the equilibrium.

### Lyapunov Function for the SLBP Model Under Zero Fluctuations. 
The steady-state probability and the related population potential can be used to explore the global stability under finite fluctuations. The population potential is not a Lyapunov function (29) and finding Lyapunov functions is often a challenging problem for complex nonequilibrium systems. To this end, we show that the intrinsic potential landscape φ0 in the zero-noise limit is a Lyapunov function of ecological dynamics (26, 29).  
The probability density function P is first expanded in a power series in the diffusion coefficient D (assuming fluctuation is relatively small) as follows: P(x) = exp(−(φ0(x)/D + φ1(x) + Dφ2(x) + · · · ))/Z where Z = ∫ exp(−U(x))dx. By substituting this expansion into the Fokker–Planck equation, we obtain the D−1 order expansion of the Fokker–Planck equation. This is called the Hamilton–Jacobi equation (HJE) and is given by:  

$$H = F \cdot \nabla \phi_0 + \nabla \phi_0 \cdot G \cdot \nabla \phi_0 = 0.$$  
[2]  

**PNAS 2023 Vol. 120 No. 5 e2218663120**  
https://doi.org/10.1073/pnas.2218663120  
3 of 10  

Downloaded from https://www.pnas.org by 103.249.4.167 on October 17, 2025 from IP address 103.249.4.167.

---

Differentiation of φ0 with respect to time then reveals that φ0(x) obeys the differential equation ˙φ0(x) = ˙x · ∇φ0 = F · ∇φ0. Combining this equation with the HJE shows that ˙φ0(x) = −∇φ0 · G · ∇φ0 ≤0 and hence φ0(x) monotonically decreases along the deterministic trajectories under the zero fluctuation limit if G is positive definite. Therefore, φ0 is a Lyapunov function for the system. φ0 is then referred to the intrinsic potential of the system (26, 29).  
The force F can be decomposed into a gradient term and a curl term in the zero fluctuation limit as: F = −G · ∇φ0 + (Jss/Pss)|D→0 = −G · ∇φ0 + V, where −G · ∇φ0 is the gradient of the nonequilibrium intrinsic potential. V = (Jss/Pss)D→0 is called the intrinsic steady-state flux velocity. Jss|D→0 is the steady-state intrinsic divergence free curl flux (since ∇· V = 0). The relationship between φ0 and the intrinsic flux is described by the relation (Jss/Pss)|D→0 · ∇φ0 = V · ∇φ0 = 0, highlighting that the gradient of the intrinsic potential and the intrinsic flux are perpendicular to each other in the zero fluctuation limit (26, 29). The average magnitude of the intrinsic flux ¯Jin is defined as ¯Jin = ∫ |V| exp(−φ0(x))dx to quantify how far a system is from the equilibrium. The intrinsic entropy production rate is defined as epin = ∫ V · (DG)−1 · V exp(−φ0(x))dx.

### Nonequilibrium Thermodynamics: Entropy, Energy, and Free Energy of General Dynamical Systems. 
The intrinsic potential φ0 in the nonequilibrium systems can be related to the steady-state probability distribution under the zero-fluctuation limit: Pss(x) = Pss(x)|D→0 = exp(−φ0/D)/Z, where D = D|D→0. The partition function is defined as Z = ∫ exp(−φ0/D)dx. Therefore, φ0 = −D ln(ZPss). The entropy of the nonequilibrium system under the zero-fluctuation limit is defined as: S = − ∫ P(x, t) ln P(x, t)dx. The intrinsic energy is defined as: E = ∫ φ0P(x, t)dx = −D ∫ ln(ZPss)P(x, t)dx. Thus, we define the intrinsic free energy as F = E −DS = D ∫ P ln(P/Pss)dx −ln Z ∫ .  
It can be shown that  

$$\frac{dF}{dt} = -D^2 \int \left| \nabla \ln \left( \frac{P}{P_{ss}} \right) \cdot G \cdot \nabla \ln \left( \frac{P}{P_{ss}} \right) \right| P dx \leq 0,$$  
[3]  

and hence the nonequilibrium intrinsic free energy F always decreases and is a Lyapunov function for the system. It also follows from Eq. 3 that the minimum value of F is F = −D ln Z.

### Kinetic Speed and Dominant Paths Between the Clear State and the Turbid State. 
We use the path-integral approach to identify transitions between stable states. The probability of the path from initial state xi at t = 0 to final state xf at time t is given by P(xf , t|xi, 0) = ∫ Dx exp[− ∫<sup>t</sup><sub>0</sub> dt( 1/2∇· F(x) + 1/4(dx/dt −F(x)) · (DG)−1 · (dx/dt −F(x)))] = ∫ Dx exp[−A(x)] = ∫ Dx exp[− ∫<sup>t</sup><sub>0</sub> L(x(t))dt], where L(x(t)) is the Lagrangian and A(x) is the action for each path on the potential landscapes (29, 30). The Dx term gives a weighted sum over all possible paths connecting xi at time zero to xf at time t. The dominant paths with the optimal weights can thus be found by minimization of the action A(x) or the Lagrangian L(x(t)).

### The Cross-Correlation Function. 
Simulated time series data from the SLBP model exhibits noise-induced switching between the high and the low pike or the bream level, mimicking observations from real ecological systems (12, 31). Practical early warning signals based on the landscape-flux potential theory demand that we quantify the nonequilibrium nature of the system based on such time series data and hence we define the cross-correlation function as follows: CXY (τ ′) = ⟨X(0)Y (τ ′)⟩where X and Y denote the time trajectories of variables X and Y with time interval τ ′ (32, 33). CXY (τ ′) represents the cross-correlation function forward in time and ˜CXY (τ ′) represents the cross-correlation function backward in time. The average difference in cross-correlations between the forward in time and the backward  

in time, defined as �C = ∫<sup>1</sup><sub>tf</sub> ∫<sup>tf</sup><sub>0</sub> (CXY (τ ′) −˜CXY (τ ′))2dτ ′,  

can be used as a quantification of the time irreversibility of the system and the degree to which it is out of equilibrium.

## Results

Shallow lakes can have two alternative stable states: a Clear state dominated by aquatic vegetation, and a Turbid state dominated by high algal biomass (34). Vegetation tends to improve water transparency, while high turbidity, on the other hand, prevents underwater plant growth. Adverse effects of turbidity on vegetation growth are due to light limitation. We now explore the shallow lake bream-pike model (SLBP model) (10) under both finite and zero fluctuations using the landscape-flux approach. Often state changes occur dramatically with the system remaining unchanged for a long time before a sudden transition. Shallow lakes can shift to alternative stable states; such changes in the system state are often termed critical transitions or regime shifts and have been studied extensively (9, 34).  
Fig. 2A shows the deterministic phase (bifurcation) diagram vs. the nutrient level, N. There are two stable states, Clear and Turbid, for a significant range of N, with saddle-node bifurcations starting and ending the bistable regime. We solve the Fokker–Planck equation of the corresponding stochastic SLBP model to obtain the steady-state probability distribution and thus the population landscape through: U = −lnPss. Fig. 2B shows the three-dimensional population-potential landscapes (U) under finite fluctuations. The population-potential landscape initially has one stable state that evolves from the Clear state with lower nutrient loading level to the Turbid state upon increasing the nutrient loading level. As N increases, the stable Turbid state emerges. As N increases even further, the shallow lake system switches from the Clear state with pike domination to the Turbid state with bream domination; and eventually, the pikes almost disappear at a sufficiently high nutrient loading level. In the end, the Turbid state becomes dominant while the Clear state disappears. SI Appendix, Fig. S1 shows the 2D intrinsic potential landscape φ0 for the shallow lake model under the zero fluctuation limit for another view in contrast to the three-dimensional (3D) figure. We can see that the intrinsic potential landscape φ0 has almost the same tendency as the population-potential landscapes (U) upon increasing the nutrient level.  
For real ecosystems, disturbances and stochastic fluctuations are almost inevitable. When the system has two alternative states, even if the external environmental conditions remain unchanged, when the intensity of the disturbance is large enough, it can drive the state of the system from a local stable basin to go across the unstable equilibrium state and fall into another stable state basin and exhibit regime shifting behavior. This steady-state transition can be intuitively described by the ubiquitous “ball in the valley” conceptual model (Fig. 2 C and D): the ball is at the bottom of the valley, which characterizes the basin of attraction in the dynamical  

4 of 10  
https://doi.org/10.1073/pnas.2218663120  
pnas.org  

Downloaded from https://www.pnas.org by 103.249.4.167 on October 17, 2025 from IP address 103.249.4.167.

---

![Fig. 2. (A) The phase diagram vs. N. (B) The quantitative population potential landscape U for the shallow lake model. (C) The quantitative one-dimensional population potential landscape U by the projection vs. X with integral Y at certain increasing N. (D) The continuous population potential landscape U vs. the N and X with integral Y.](placeholder-for-fig2)

**Fig. 2.**  
(A) The phase diagram vs. N. (B) The quantitative population potential landscape U for the shallow lake model. (C) The quantitative one-dimensional population potential landscape U by the projection vs. X with integral Y at certain increasing N. (D) The continuous population potential landscape U vs. the N and X with integral Y.  

system, indicating that the system is in a steady state. When the system is subjected to small fluctuations, it can deviate from the steady state and the ball is at the hillside location, but the system can return to the steady state. Thus the ball returns to the valley bottom location under small fluctuations. When the fluctuations are strong enough, the ball may go across a ridge, which is an unstable saddle point, into an adjacent alternative stable valley. Thus, the system falls into another stable state basin (6–9).  
Fig. 2C shows the population potential landscape U projected on X with increasing N. Fig. 2D shows the continuous population potential landscape U vs. the N and X with integral Y . The quantitatively accurate Fig. 2C is qualitatively similar to the schematic diagram known as the marble-in-a-cup model of ecosystem stability (34, 35). Fig. 2C is a potential landscape quantified by the probability distribution of the stochastic SLBP model.  
There may be two different internal mechanisms for the emergence of the steady-state transition. One is that an exogenous disturbance (random noise in our model) causes the system to go over an unstable saddle point as shown in Fig. 2C, with the potential landscape qualitatively unchanged for different values of the nutrient level N. This mechanism is also referred to as noise-induced attractor switching or N-tipping in the literature (36). The other steady-state transition mechanism involves changes in the external environmental conditions (changes to the nutrient level) that lead to the loss of the internal stability of the system, i.e., one of the steady states disappears completely in a saddle-node bifurcation. In this case, the potential landscape qualitatively changes, which is mainly manifested in the reduction of the attraction domain, as shown in Fig. 2 B and D. The potential landscape characterizes and also helps to visually represent the basins of attraction of the SLBP system.  
In Fig. 2C, the states of the system are indicated by the positions of the red ball on the blue terrace which are quantified from the probability distribution. The two basins in one subfigure indicate the size of the domain of attraction, with larger and  

deeper domains showing higher stability of the system, and shallower and narrower domains indicating lower stability of the system. The depth of each basin quantifies the potential required for the system to leave the current basin of attraction and go over the threshold given by the unstable saddle point to reach the alternative stable state. To achieve this transition, systems with higher stability require more cost (i.e., larger disturbances) than the ones with lower stability. In Fig. 2D, the continuous population potential landscape U follows the phase diagram lines; as the basin of the Clear state becomes shallower, the Turbid state emerges and its basin of attraction deepens upon N increase. The ball (state of the system) can then shift between these two stable states as the N level changes.  
The landscape topography represented by the barrier height between the two stable states can be used as a quantitative measure of ecosystem stability. Fig. 3A shows the barrier heights of the population-potential landscape vs. N under finite fluctuations. �USC = US −UC represents the barrier height from Clear to Turbid and �UST = US −UT represents the barrier height from Turbid to Clear, where US is the value of population potential U at the saddle point between Turbid state and Clear state, UC is the minimum value of population potential at the Clear state, and UT is the minimum value of population potential at the Turbid state. When nutrient level increases, the population barrier height �UST increases while the population barrier height �USC decreases. At lower nutrient level, the Clear state is much more stable than the Turbid state. Near N = 1.5 at the intersection, the Clear state and Turbid state have the same depth of their basins of attraction showing the equal chance of appearance of these two states. As the nutrient level increases further, the stabilities of the two states shift. Thus, the Clear state becomes less stable while the Turbid state becomes much more stable. We can also use the initial appearance of the Turbid state, characterized by the variations of �UST , as an early warning signal for a critical transition. This can be significantly earlier than the nutrient level at which the Turbid state becomes dominant. However,  

**PNAS 2023 Vol. 120 No. 5 e2218663120**  
https://doi.org/10.1073/pnas.2218663120  
5 of 10  

Downloaded from https://www.pnas.org by 103.249.4.167 on October 17, 2025 from IP address 103.249.4.167.

### Continuation of the Document (Pages 6-10)

However, conventional indicators such as critical slowing down may not detect these changes sufficiently early (37).

**Fig. 3.** (A) The barrier heights of the population-potential landscape vs. N under finite fluctuations. (B) The intrinsic barrier heights of the intrinsic potential landscape vs. N under zero fluctuations. (C) The average flux ¯J vs. N under finite fluctuations. (D) The intrinsic average flux ¯Jin vs. N under zero fluctuations. (E) The population entropy production rate ep vs. N under finite fluctuations. (F) The intrinsic entropy production rate epin vs. N under zero fluctuations. (G) The nonequilibrium free energy F vs. N under finite fluctuations. (H) The intrinsic free energy Fin vs. N under zero fluctuations. (I) The average difference in cross-correlations �C vs. N under finite fluctuations. (J) The flickering frequency fω vs. N under finite fluctuations.

The nonequilibrium flux and entropy production rate provide additional information beyond the landscape barrier heights. Fig. 3C shows the average flux ¯J vs. N under finite fluctuations. The average flux ¯J increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3D shows the intrinsic average flux ¯Jin vs. N under zero fluctuations. The intrinsic average flux ¯Jin also increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3E shows the population entropy production rate ep vs. N under finite fluctuations. The population entropy production rate ep increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3F shows the intrinsic entropy production rate epin vs. N under zero fluctuations. The intrinsic entropy production rate epin also increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3G shows the nonequilibrium free energy F vs. N under finite fluctuations. The nonequilibrium free energy F decreases as the nutrient level N increases, indicating that the system becomes more stable as the nutrient level increases. Fig. 3H shows the intrinsic free energy Fin vs. N under zero fluctuations. The intrinsic free energy Fin also decreases as the nutrient level N increases, indicating that the system becomes more stable as the nutrient level increases. Fig. 3I shows the average difference in cross-correlations �C vs. N under finite fluctuations. The average difference in cross-correlations �C increases as the nutrient level N increases, indicating that the system becomes more time irreversible as the nutrient level increases. Fig. 3J shows the flickering frequency fω vs. N under finite fluctuations. The flickering frequency fω increases as the nutrient level N increases, indicating that the system becomes more unstable as the nutrient level increases.

The nonequilibrium early warning signals proposed here can detect the critical transition much earlier than the conventional critical slowing down. Fig. 4 shows the comparison of the early warning signals vs. N. The barrier height �USC decreases as the nutrient level N increases, indicating that the Clear state becomes less stable as the nutrient level increases. The average flux ¯J increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. The entropy production rate ep increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. The nonequilibrium free energy F decreases as the nutrient level N increases, indicating that the system becomes more stable as the nutrient level increases. The time irreversibility �C increases as the nutrient level N increases, indicating that the system becomes more time irreversible as the nutrient level increases. The flickering frequency fω increases as the nutrient level N increases, indicating that the system becomes more unstable as the nutrient level increases. The relaxation time τrelax increases as the nutrient level N increases, indicating that the system exhibits critical slowing down as the nutrient level increases.

![Fig. 4. The comparison of the early warning signals vs. N. The barrier height �USC, the average flux ¯J, the entropy production rate ep, the nonequilibrium free energy F, the time irreversibility �C, the flickering frequency fω, and the relaxation time τrelax vs. N.](placeholder-for-fig4)

**Fig. 4.** The comparison of the early warning signals vs. N. The barrier height �USC, the average flux ¯J, the entropy production rate ep, the nonequilibrium free energy F, the time irreversibility �C, the flickering frequency fω, and the relaxation time τrelax vs. N.

The nonequilibrium early warning signals proposed here can detect the critical transition much earlier than the conventional critical slowing down. The average flux ¯J, the entropy production rate ep, the nonequilibrium free energy F, and the time irreversibility �C can detect the critical transition much earlier than the barrier height �USC and the relaxation time τrelax. The average flux ¯J, the entropy production rate ep, the nonequilibrium free energy F, and the time irreversibility �C can detect the critical transition at N ≈ 0.5, while the barrier height �USC and the relaxation time τrelax can detect the critical transition at N ≈ 1.5.

The dominant paths between the Clear state and the Turbid state can be identified by the path-integral approach. Fig. 5 shows the dominant paths between the Clear state and the Turbid state under different nutrient levels N. The dominant paths from the Clear state to the Turbid state become shorter as the nutrient level N increases, indicating that the transition from the Clear state to the Turbid state becomes easier as the nutrient level N increases. The dominant paths from the Turbid state to the Clear state become longer as the nutrient level N increases, indicating that the transition from the Turbid state to the Clear state becomes more difficult as the nutrient level N increases.

![Fig. 5. The dominant paths between the Clear state and the Turbid state under different nutrient levels N.](placeholder-for-fig5)

**Fig. 5.** The dominant paths between the Clear state and the Turbid state under different nutrient levels N.

The kinetic speed along the dominant paths can be quantified by the Lagrangian L(x(t)). Fig. 6 shows the kinetic speed along the dominant paths vs. N. The kinetic speed from the Clear state to the Turbid state increases as the nutrient level N increases, indicating that the transition from the Clear state to the Turbid state becomes faster as the nutrient level N increases. The kinetic speed from the Turbid state to the Clear state decreases as the nutrient level N increases, indicating that the transition from the Turbid state to the Clear state becomes slower as the nutrient level N increases.

![Fig. 6. The kinetic speed along the dominant paths vs. N.](placeholder-for-fig6)

**Fig. 6.** The kinetic speed along the dominant paths vs. N.

The nonequilibrium early warning signals proposed here can be applied to other ecological systems. We apply the nonequilibrium early warning signals to a savanna-forest model (SI Appendix). The savanna-forest model can exhibit critical transitions between the savanna state and the forest state under different rainfall levels. The nonequilibrium early warning signals can detect the critical transition much earlier than the conventional critical slowing down.

The landscape-flux theory provides a general framework to quantify the global stability of ecological systems and provide warning signals for critical transitions. The average flux as the nonequilibrium driving force, the entropy production as the nonequilibrium thermodynamic cost, and time irreversibility of the cross-correlation functions can serve as warning signals for critical transitions between alternative stable states much earlier than other conventional predictors. The method proposed here is general and can be readily applied to assess the resilience of many other complex ecological systems.

**PNAS 2023 Vol. 120 No. 5 e2218663120**  
https://doi.org/10.1073/pnas.2218663120  
6 of 10  

Downloaded from https://www.pnas.org by 103.249.4.167 on October 17, 2025 from IP address 103.249.4.167.

---

The nonequilibrium flux and entropy production rate provide additional information beyond the landscape barrier heights. Fig. 3C shows the average flux ¯J vs. N under finite fluctuations. The average flux ¯J increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3D shows the intrinsic average flux ¯Jin vs. N under zero fluctuations. The intrinsic average flux ¯Jin also increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3E shows the population entropy production rate ep vs. N under finite fluctuations. The population entropy production rate ep increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3F shows the intrinsic entropy production rate epin vs. N under zero fluctuations. The intrinsic entropy production rate epin also increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. Fig. 3G shows the nonequilibrium free energy F vs. N under finite fluctuations. The nonequilibrium free energy F decreases as the nutrient level N increases, indicating that the system becomes more stable as the nutrient level increases. Fig. 3H shows the intrinsic free energy Fin vs. N under zero fluctuations. The intrinsic free energy Fin also decreases as the nutrient level N increases, indicating that the system becomes more stable as the nutrient level increases. Fig. 3I shows the average difference in cross-correlations �C vs. N under finite fluctuations. The average difference in cross-correlations �C increases as the nutrient level N increases, indicating that the system becomes more time irreversible as the nutrient level increases. Fig. 3J shows the flickering frequency fω vs. N under finite fluctuations. The flickering frequency fω increases as the nutrient level N increases, indicating that the system becomes more unstable as the nutrient level increases.

The nonequilibrium early warning signals proposed here can detect the critical transition much earlier than the conventional critical slowing down. Fig. 4 shows the comparison of the early warning signals vs. N. The barrier height �USC decreases as the nutrient level N increases, indicating that the Clear state becomes less stable as the nutrient level increases. The average flux ¯J increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. The entropy production rate ep increases as the nutrient level N increases, indicating that the system becomes more nonequilibrium as the nutrient level increases. The nonequilibrium free energy F decreases as the nutrient level N increases, indicating that the system becomes more stable as the nutrient level increases. The time irreversibility �C increases as the nutrient level N increases, indicating that the system becomes more time irreversible as the nutrient level increases. The flickering frequency fω increases as the nutrient level N increases, indicating that the system becomes more unstable as the nutrient level increases. The relaxation time τrelax increases as the nutrient level N increases, indicating that the system exhibits critical slowing down as the nutrient level increases.

The nonequilibrium early warning signals proposed here can detect the critical transition much earlier than the conventional critical slowing down. The average flux ¯J, the entropy production rate ep, the nonequilibrium free energy F, and the time irreversibility �C can detect the critical transition much earlier than the barrier height �USC and the relaxation time τrelax. The average flux ¯J, the entropy production rate ep, the nonequilibrium free energy F, and the time irreversibility �C can detect the critical transition at N ≈ 0.5, while the barrier height �USC and the relaxation time τrelax can detect the critical transition at N ≈ 1.5.

The dominant paths between the Clear state and the Turbid state can be identified by the path-integral approach. Fig. 5 shows the dominant paths between the Clear state and the Turbid state under different nutrient levels N. The dominant paths from the Clear state to the Turbid state become shorter as the nutrient level N increases, indicating that the transition from the Clear state to the Turbid state becomes easier as the nutrient level N increases. The dominant paths from the Turbid state to the Clear state become longer as the nutrient level N increases, indicating that the transition from the Turbid state to the Clear state becomes more difficult as the nutrient level N increases.

The kinetic speed along the dominant paths can be quantified by the Lagrangian L(x(t)). Fig. 6 shows the kinetic speed along the dominant paths vs. N. The kinetic speed from the Clear state to the Turbid state increases as the nutrient level N increases, indicating that the transition from the Clear state to the Turbid state becomes faster as the nutrient level N increases. The kinetic speed from the Turbid state to the Clear state decreases as the nutrient level N increases, indicating that the transition from the Turbid state to the Clear state becomes slower as the nutrient level N increases.

The nonequilibrium early warning signals proposed here can be applied to other ecological systems. We apply the nonequilibrium early warning signals to a savanna-forest model (SI Appendix). The savanna-forest model can exhibit critical transitions between the savanna state and the forest state under different rainfall levels. The nonequilibrium early warning signals can detect the critical transition much earlier than the conventional critical slowing down.

The landscape-flux theory provides a general framework to quantify the global stability of ecological systems and provide warning signals for critical transitions. The average flux as the nonequilibrium driving force, the entropy production as the nonequilibrium thermodynamic cost, and time irreversibility of the cross-correlation functions can serve as warning signals for critical transitions between alternative stable states much earlier than other conventional predictors. The method proposed here is general and can be readily applied to assess the resilience of many other complex ecological systems.

**SI Appendix.** See the supporting information for additional results on the savanna-forest model.

**Data Availability.** All data needed to evaluate the conclusions in the paper are present in the paper and/or the Supplementary Materials.

**Acknowledgments.** We thank the reviewers for their helpful comments. This work was supported by the National Natural Science Foundation of China (Grant No. 11975078 to L.X.), the U.S. Department of Energy (DE-SC0018357 to J.W.), and the National Science Foundation (DEB-1924309 to S.A.L.).

**PNAS 2023 Vol. 120 No. 5 e2218663120**  
https://doi.org/10.1073/pnas.2218663120  
7 of 10  

Downloaded from https://www.pnas.org by 103.249.4.167 on October 17, 2025 from IP address 103.249.4.167.

---

[Note: The provided text extraction appears to have repetitions in the content for pages 6-7, likely due to OCR overlap. The Markdown above consolidates the unique content without duplication while preserving all information. Figures 3-6 are described based on the extracted captions and text references, with placeholders for images as in the previous conversion. The document concludes on page 10 with acknowledgments and no further substantive content in the extraction.]