
# Teorema lui Gauss

$$
\Psi_{\Sigma}=\oint_{\Sigma}\vec{E_{v}}\vec{dA}=\frac{q_{\Sigma}}{\epsilon_{0}}
$$
---
## Problema 1

O suprafata sferica conductoare de raza $a$ este incarcata cu sarcina electrica distribuita uniform pe suprafata acestuia cu densitatea superficiala de sarcina $\rho_{s}$. Sa se determine intensitatea campului electric in punctele interioare si exterioare ale sferei (situate la distanta notata generic cu $r$) stiind ca sfera este plasata in vid.

---

![[Seminar 2 - Calculul intensitatii campului electric in vid 2024-10-14 08.26.15.excalidraw|700]]
 $$
\begin{gathered}
\Psi_{\Sigma}=\int_{\Sigma}\vec{E_{v}}\vec{dA}=\frac{q\Sigma}{\epsilon_{0}}\\
a)E_{i}=?,r<a\\
1.sim,\epsilon_{0}\\
2.\Sigma_{i}\\
3.\vec{E_{i}}||\vec{dA}\implies \cos(0^o)=1\\
4.\Psi_{\Sigma_{i}}=\int_{\Sigma_{i}}\vec{E_{i}}\vec{dA}=\int_{\Sigma_{i}}E_{i}dA\cos(0)=E_{i}\int_{\Sigma_{i}}dA=E_{i}4\pi r^2\\
5.q_{\Sigma_{i}}=0\\
6.E_{i}=0\\
b)E_{e}=?,r>a\\
1.sim,\epsilon_{0}\\
2.\Sigma_{e}\\
3.\vec{E_{e}}||\vec{dA}\implies \cos(0)\\
4.\Psi_{\epsilon_{i}}=\int_{\epsilon_{e}}\vec{E_{i}}\vec{dA}=E_{i}\int_{\epsilon_{e}}dA\\
\Psi_{\epsilon_{e}}=E_{i}*4\pi r^2\\
q_{\epsilon_{e}}=\rho_{S}*A_{sfera}=\rho_{S}4\pi a^2\\
6.E_{i}4\pi r^2=\rho_{S}4\pi a^2\\
E_{e}=\frac{\rho_{S}a^2}{r^2 * \epsilon_{0}},\left[ \frac{V}{m} \right]

\end{gathered}
$$
---
Fluxul campului electric pentru puncte interioare si puncte exterioare in cazul acestei probleme este aceeasi

--
## Problema 2 

Se da un cilindru drept de raza $a$, infinit lung, incarcat cu sarcina electrica libera uniform distribuita cu densitatea superficiala de sarcina $\rho_{S}$. Sa se determine intensitatea campului electric in punctele exterioare si interioare ale cilindrului ( situate la o distanta notata generic cu $r$ fata de axul acestuia), stiind ca acesta este plasat in vid.

---

![[Seminar 2 - Calculul intensitatii campului electric in vid 2024-10-14 08.48.09.excalidraw]]
$$
\begin{gathered}
\Psi_{\Sigma}=\oint_{\Sigma}\vec{E_{v}}\vec{dA}=\frac{q_{\Sigma}}{\epsilon_{0}}\\
a.P_{i},E_{i}=?,r<a\\
1.sim.cilindrica,\epsilon_{0}\\
2.\Sigma_{i}\\
3.Al:\vec{E_{i}}\vec{dA}\implies \cos(0)=1\\
Ab:\vec{E_{i}}\perp \vec {dA}\implies \cos(90)=0\\
\dots\dots\\
b)P_{e},E_{e}=?,r>a\\
1)sim. cilindrica, \epsilon_{0}\\
2)\Sigma_{e}\\
3)Al:\vec{E_{e}}||\vec{dA}\implies \cos(0)=1\\
Ab:\vec{E_{e}}\perp\vec{dA}\implies \cos(90)=0\\
4.\Psi_{\Sigma_{i}}=\int_{\vec\Sigma_{i}\vec{dA}}+2\int_{A_{b}}\vec{E_{i}}\vec{dA}=\int_{A_{b}}\vec{E_{i}}\vec{dA}\cos(0)=E_{e}2\pi rhe\\
5.q_{\Sigma_{e}}=\varphi_{S} \text{Al cilindu}=\varphi_{S}2\pi arhe\\
6.E_{e}2\pi rhe=\frac{\varphi_{2}\pi arhe}{\epsilon_{0}}\\
E_{e}=\frac{\varphi_{S}a}{r\epsilon_{0}}\left[ \frac{V}{M} \right]\\
\boxed{\text{OBS }r=a\implies E_{e}=\frac{\varphi_{S}}{e_{0}}}
\end{gathered}
$$
---
![[Seminar 2 - Calculul intensitatii campului electric in vid 2024-10-15 14.14.14.excalidraw]]