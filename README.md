
# The Noble Model

The Noble Model was developed based on the Hodgkin-Huxley's mathematical model for ion channels. The experimental work was carried out using the current clamp technique with two microelectrodes impaled into Purkinje fibres from sheep and dog hearts. The purpose of one microelectrode was to pass current while the other was to measure changes in the membrane potential. 

Two types of potassium currents were identified, the inward rectifier (iK1) and the delayed rectifier (iK). The inward rectifier carries a large inward current at negative potentials, but the current decreases towards zero during depolarization. On the other hand, the delayed rectifier current activates slowly, inducing repolarization of the action potential.

The equations for iK used modified versions of the Hodgkin-Huxley K+ current equations to reflect the difference in the time required for the process in nerves and hearts. The equations for iK1 were empirical descriptions of the current's dependence on voltage and potassium concentration, assuming that this component was not explicitly dependent on time. The sodium current equations used the Hodgkin-Huxley equations since the sodium inactivation process was found to be similar in the heart according to Weidmann (1956). An anion (chloride) current was also included as it was detected in the experimental data.





The Noble model (1962) was the first mathematical model of cardiac action potentials V dynamics. It was a development from the Hodgkin-Huxley model

$$
\begin{aligned}
\frac{dV}{dt} &= -\left(i_{K} + i_{Na} + i_{An}\right)/C_{m} \\
i_{K} &= \left(1.2 n^{4} + 1.2 e^{[-V - 90]/50} + 0.015 e^{[V+90]/60}\right)(V + 100) \\
i_{Na} &= 120 \left(400 m^{3}h + 0.14\right)(V - 40) \\
i_{An} &= 0 (V + 60) \\
\frac{dy}{dt} &= \alpha_{y} - (\alpha_{y} + \beta_{y}) y = \left(\bar{y} - y\right)/\tau_{y}, \\
\tau_{y} &= \frac{1}{\alpha_{y} + \beta_{y}}, \\
\bar{y} &= \frac{\alpha_{y}}{\alpha_{y} + \beta_{y}}
\end{aligned}
$$

where y is m, h or n gate, $i_{An}$ is anions (chloride) current, $C_{m} = 12\ \mu F/cm^{2}$.

$$
\begin{aligned}
\alpha_{n} &= 0.0001 (-V - 50) / \left(e^{[-V - 50]/10} - 1\right) \\
\beta_{n} &= 0.002 e^{[-V - 90]/80} \\
\alpha_{m} &= 0.1 (-V - 48) / \left(e^{[-V - 48]/15} - 1\right) \\
\beta_{m} &= 0.12 (V + 8) / \left(e^{[V + 8]/5} - 1\right) \\
\alpha_{h} &= 0.17 e^{[-V - 90]/20} \\
\beta_{h} &= 1 / \left(e^{[-V - 42]/10} + 1\right)
\end{aligned}
$$


