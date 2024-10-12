## ungiul solid

![[Curs 2 - Electrostatica 2024-10-08 12.19.43.excalidraw]]
$$
\begin{gathered}
d\beta=\frac{ds}{r}\to\beta=\frac{2\pi r}{r}=2\pi
\end{gathered}
$$
---
![[Curs 2 - Electrostatica 2024-10-08 12.22.50.excalidraw]]
$$
\begin{gathered}
\ohm=\frac{4\pi r^2}{r^2}=4\pi \\
d\ohm=\frac{dA}{r^2}
\end{gathered}
$$
---
![[Curs 2 - Electrostatica 2024-10-08 12.26.27.excalidraw]]
$$
\begin{gathered}
d\beta=\frac{ds}{r}*cos(\alpha)\\
cos(\alpha)=\vec{n}*\frac{\vec  r}{r}\\
=>d\beta=\frac{dS}{r}*\vec{n}*\frac{\vec r}{r}\\
d\ohm=\frac{dA}{r^2}*\frac{\vec r}{r}*\vec n=>d\ohm=\frac{\vec dA*\vec r}{r^3}\\
\Psi=\int_S\vec E_v*\vec dA\to\text{q este sarcina punctiforma}
\end{gathered}
$$
---
![[Curs 2 - Electrostatica 2024-10-08 12.33.13.excalidraw]]
$$
\begin{gathered}
\Psi=\int_S{\vec E_v*dS}\to\text{q. sarcina punctiforma}\\
\vec E_v=\frac{1}{4\pi\epsilon_0}*\frac{q}{\vec r^2}*\frac{\vec r}{r}\\



\phi_\Sigma=\oint_\Sigma\vec E_v \vec dA=\frac{q_\Sigma}{\epsilon_0}\\
\oint_\Sigma\vec{E_v}\vec{dA}=\frac{q_\Sigma}{\epsilon_0}\text{Teorma lui Gauss ; Probleme cu simetrii;}
\end{gathered}
$$

Sa se determine expresia campului electric $\vec E_v$ produsa in vecinatatea unui plan infinit extins incarcat cu sarcina electrica cu densitatea $\rho_S=const.$
![[Curs 2 - Electrostatica 2024-10-08 12.44.45.excalidraw]]
$$
\begin{gathered}
\phi=\oint_\Sigma\vec E_v *dA=\frac{q_\Sigma}{\epsilon_0}\\
A_b:\vec E_v||dA=1\\
A_{l}:\vec{E_{v}}\perp vec{dA}=0\\
\oint_\Sigma\vec{dA}=\int_{S_1}E_v*dAcos(0^o)+\int_{S_2}E_v*dAcos(0^o)+E_v\int_{S_1}dA+E_v\int_{S_2}dA\\
\rho=E_v*A+E_v*A=2E_v A\\
q_\Sigma=\rho_SA\\
2E_vA=\frac{\rho_SA\\}{\epsilon_0}=>E_v=\frac{\rho_s}{2\epsilon_0}\\

\end{gathered}
$$
![[Curs 2 - Electrostatica 2024-10-08 13.15.45.excalidraw]]
$$
\vec{E_{v}}=\frac{\rho_{s}}{E_{v}}
$$

# Tensiunea electrica si potentialul electric.

![[Curs 2 - Electrostatica 2024-10-08 13.22.58.excalidraw]]
$$
\begin{gathered}
dL=\vec{F}dS\\
L_{AB}=\int_{A}^{B}\vec{F}dS=\int_{A}^Bq_{0}\vec{E_{V}}dS;\\
\vec{F}=q_{0}\vec{E_{v}}\\
L_{AB}=q_{0}\int_{A}^{B}\vec{E_{v}}dS\implies \color{red}{U_{AB}=def=\frac{L_{AB}}{q_{0}}}\\
U_{AB}=\int_{A}^{B}\vec{E_{v}}\vec{dS}[V]\implies E_{v}SI;=\frac{V}{m}\\
\text{Observatie:}\\
1)U_{BA}=\int_{B}^{A}\vec{E_{v}}\vec{dS}=-U_{AB}\\
2)U_{AA}=\int_{A}^{A}\vec{E_{v}}\vec{dS}\equiv 0\\
U_{BA}=-U_{AB}\\
\end{gathered}

$$
![[Curs 2 - Electrostatica 2024-10-08 13.34.44.excalidraw]]
$$
\begin{gathered}
U_{AA}=U_{AmB}+U_{BnA}=0\\
U_{AmB}=U_{AnB}\\
\color{red}{\text{Nu depinde de drumul de integrare}}
\end{gathered}

$$
![[Curs 2 - Electrostatica 2024-10-08 13.38.24.excalidraw]]

$$
U_{AA}=0\implies \oint_{\beta}\vec{E_{v}}\vec{dS}=0;\text{Teorema fundamentala a electrostaticii.}
$$
$\vec{E_{v}}$-Camp potential irotational.
$$
rot(E_{v})=0
$$
## Potentialul electric

Reprezinta tensiunea electrica calculata in raport cu un punct de referinta $t_{0}$.
![[Curs 2 - Electrostatica 2024-10-08 13.47.52.excalidraw]]
$$
U_{AP_{0}}=V_{A}=\int_{A}^{r_{0}}\vec{E_{v}}\vec{dS}\\
U_{AB}=U_{AP_{0}}+U_{AP_{0}}\\
$$
### Observatie

1. Sarcina electrica in care zona este finita in spatiu:$P_{0}\to \infty$
		1. Sarcina electrica - zona $\infty$ in spatiu $P_{0}$ arbitrara.
2. Suprafete echipotentiale$$\int_{p}^{p_{0}}\vec{E_{v}}\vec{dS}\implies V=const.$$
