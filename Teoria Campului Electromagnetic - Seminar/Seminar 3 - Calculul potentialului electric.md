# Calculul potentialului electric

+ potentialul in punctul A:
$$
\boxed{V_{A}=\int_{A(l)}^{P}\vec{E}*\vec{dl}}
$$
+ se alege arbitrar un punct P de referinta(origine de potential)
	+ pentru dimensiuni finite $P \to \infty,r_{p} \to \infty$
	+ pentru dimensiuni infinite $P \text{ este fix},r_{p}=1$
+ traiectoria de integrare (I) poate fi arbitrar aleasa, insa pentru ca valoarea potentialului electric nu depinde de drum ea se alege cat mai convenabil, pentru a putea efectua cat mai usor produsul scalar $\vec{E}*\vec{dr}$.
	+ daca o alegem ca fiind chiar o linie de camp $\vec{E}\implies \vec{E} || \vec{dr}$.

## Problema 1

O sfera de raza a si permitivitate $\epsilon_{0}$ este incarcata cu sarcina electrica distribuitiva uniform in volumul acesteia cu densitatea volumica de sarcina $\rho_{v}$. Sfera este plasata in vid. Sa se determine:
1. intensitatea campului electric in puncte interioare si exterioare ale sferei.
2. potentialele electrice alea acelorasi puncte.

![[Seminar 3 - Calculul potentialului electric 2024-10-21 08.20.31.excalidraw]]
1. $E_{i}=?,E_{e}=?$
1. $E_{i}=?,r<a$
+ simetrie sferica
+ $\Sigma_{i}$
+ $E_{i}||dA\implies \cos(0)=1$
+ $\Psi_{\Sigma_{i}}=\int_{\Sigma_{i}}\vec{E_{i}}*\vec{dA}=\int_{\Sigma_{i}}\vec{E_{i}}*dA\cos(0)=E_{i}\int_{\Sigma_{i}}dA=E_{i}4\pi r^2$
+ $q_{\Sigma_{i}}=\rho_{v}*V_{\Sigma_{i}}=\rho_{v}*\left( \frac{4}{3} \right)\pi*r^3$
+ $E_{i}4\pi r^2=\frac{\frac{4}{3}\rho_{v}\pi r^3}{\epsilon_{0}}$
	+ $E_{i}=\frac{\rho_{v}r}{\epsilon_{0}} \left[ \frac{V}{m} \right]$ 
2. $E_{i}=?,r>a$
+ simetrie simetrica $\epsilon_{0}$
+ $\Sigma_{e}$
+ $E_{e}||dA=\cos()..$

![[Seminar 3 - Calculul potentialului electric 2024-10-21 08.34.49.excalidraw]]
B. $V_{Pi}=?,V_{Pe}=?$
$$
\begin{gathered}
V_{Pi}=\int_{Pi}^{P}\vec{E_{i}}\vec{dl}=\int_{Pi}^{A}\vec{E_{i}}\vec{dr}+\int_{A}^{P}\vec{E_{e}}\vec{dr}=\int_{Pi}^{A}\frac{\rho_{v}*r}{3\epsilon_{0}}dr+\int_{A}^{P}\frac{\rho_{v}*a^3}{3\epsilon_{0}r^2}dr=\frac{\rho_{v}}{3\epsilon_{0}}\\=\int_{P_{i}}^{A}rdr+\frac{\rho va^3}{3\epsilon_{0}}*\int_{A}^{P}\frac{dr}{r^2}=\frac{\rho_{v}}{3\epsilon_{0}}*\frac{r^2}{2}+\frac{\rho_{v}a^3}{3\epsilon_{0}}*\left( -\frac{1}{r} \right)\\
=\frac{\rho_{v}}{3\epsilon_{0}}*\left( \frac{a^2}{2} - \frac{r_{Pi}}{2}\right)+\frac{\rho_{v}a^3}{3\epsilon_{0}}*\left( \frac{-1}{r_{p}} + \frac{1}{a}\right)\\
..=\frac{\rho_{v}(3a^2-r_{Pi}^2)}{6\epsilon_{0}}
\end{gathered}
$$
Punctul de calcul $P_{i}$ trece prin 2 domenii pana la punctul de referinta P:
+ Zonei interioare care are expresia $E_{i}=\frac{\rho_{v}*r}{3\pi\epsilon_{0}}$
+ Zona exerioara in care $E_{i}=\frac{\rho_{v}a^3}{3\epsilon_{0}r^2}$
$$
V_{Pe}=\int_{P_{e}}^{P}\vec{E_{e}}\vec{de}=\int_{P_{e}}^{P}\frac{\rho a^3}{3\epsilon_{0}r^2}dr=\frac{\rho a^3}{3\epsilon_{0}}\int_{P_{e}}^{P}\left( \frac{1}{r^2} \right)dr=\frac{\rho a^3}{3\epsilon_{0}}-\left( \frac{1}{r} \right)=\frac{\rho a^3}{3\epsilon_{0}r^2}\left( -\frac{1}{r_{p}} +\frac{1}{r_{pe}} \right)=-\frac{1}{3\epsilon_{0}rP_{e}}[V]
$$

## Problema 2

Se considera un tub dielectric cilindric cu raza interna a si cea externa b, de lungime infinita. Aceasta este incarcat cu sarcina unform distribuita in volum cu densitatea volumica de sarcina $\rho_{v}$. Sa se determine:
1. expresia intensitatii campului electric in cele 3 domenii.
2. expresia potentialului electric in cele 3 domenii.

![[Seminar 3 - Calculul potentialului electric 2024-10-21 09.01.24.excalidraw]]
## A. E1
1. Simetrie cilindrica $\epsilon_{0}$
2. $\Sigma_{1}$
3. $$Al:\vec{E_{1}}||\vec{dA}\implies \cos(0)=1 $$
$$Ab:\vec{E_{1}}\perp\vec{dA}\implies \cos(90)=0 $$
4. $$\Psi_{\Sigma_{1}}=\int_{\Sigma_{1}}\vec{E_{1}}*\vec{dA}=E_{1}\int_{\Sigma_{1}}\vec{dA}$$
5. $q_{\Sigma_{1}}=0$
6. $E_{1}=0$
### A2. E2
1. simetrie cilindrica, $\epsilon_{0}$
2. $\Sigma_{2}$
3. $$Al:\vec{E_{1}}||\vec{dA}\implies \cos(0)=1 $$
$$Ab:\vec{E_{1}}\perp\vec{dA}\implies \cos(90)=0 $$
4. $\Psi_{\Sigma_{2}}=\int_{\Sigma_{2}}E_{2}dA=E_{2}\int_{\Sigma_{2}}dA=E_{2}*2\pi r_{2}$
5. $q_{\Sigma_{2}}=\rho_{V}*(V_{cr_{2}}-V_{ca})$
$q_{\Sigma_{2}}=\rho_{4}\pi h_{2}(r_{1}^2-a^2)$
6. $E_{2}*2\pi r_{2}*h_{2}=\frac{\rho_{v}\pi h_{2}(r_{2}^2-a^2)}{\epsilon_{0}}=E_{2}=\frac{\rho_{v}(r_{2}^2-a^2)}{2\epsilon_{0}r_{2}}\left[ \frac{V}{m} \right]$
### A3. E3
1. simetrie cilindrica $\epsilon_{0}$
2. $\Sigma_{3}$
3. ...
4. $\Psi_{\Sigma_{3}}=\int_{\Sigma_{3}}E_{3}*dA=E_{3}2\pi r_{3}h_{3}$
5. $q_{\Sigma_{3}}=\rho_{v}(V_{cb}-V_{ca})=\rho_{v(\pi b^2h_{3-\pi a^2 h^3})}$
6. $E_{3}=\frac{\rho_{v}(b^2-a^2)}{2\epsilon_{0}r^3}\left[ \frac{V}{m} \right]$
### B1.
$$
\begin{gathered}
V_{P_{1}}=\int_{P_{1}}^{P}\vec{E}\vec{dl}=\int_{P_{1}}\\
..=V_{P_{1}}=\frac{\rho_{v}}{4\epsilon_{0}}(b^2-a^2)+\frac{\rho_{v}a^2}{2\epsilon_{0}}\ln(a)-\frac{\rho_{v}b^2}{2\epsilon_{0}}\ln(b)
\end{gathered}

$$
