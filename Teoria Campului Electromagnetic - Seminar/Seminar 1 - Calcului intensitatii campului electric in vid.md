# Calcului intensitatii campului electric in vid
## Metoda directa

+ Ne ajuta sa determinam intensitatea curentului electric in vid.
+ Se poate aplica in orice problema.
$$
E_v=\frac{q}{4*\pi*\epsilon_0*r^2}*\frac{r}{r}
$$
$E_v$ - Intensitatea curentului electric in vid.
$q$ - Sarcina electrica.
$\epsilon_0$ - Permitivitatea electrica in vid. $\epsilon_0=\frac{1}{4*\pi*9*10^9}$ $[\frac{F}{m}]$.
$r$ - distanta de la corpul incarcat cu sarcina electrica la punctul de calcul.


### Sarcina electrica
+ Sarcina electrica punctiforma:
$$
\sum_{k=1}^{n}q_n,[C]
$$
+ Sarcina distribuita in volumul unui corp:
    + In acest caz se defineste densitatea volumica de sarcina:
    $\rho_v=\lim\limits_{\delta V \to 0}\frac{\delta q}{\delta V}=\frac{dq}{dV},[\frac{c}{m^3}]$
	$q=\int_V \rho_v * dv$
+ Sarcina repartizata pe suprafata unui conductor:
	+ In acest caz se defineste densitatea superficiala de sarcina:
	$\rho_s=\lim\limits_{\Delta A \to 0}{\frac{\Delta Q}{\Delta A}}$
#### Observatie:
 + $\rho_s$ prezinta importanta, in special,  pentru materialele conductoare.
	 + in acesta caz se defineste densitatea lineica de sarcina:
	 $\rho_l=\lim\limits_{\Delta l \to 0}\frac{\Delta Q}{\Delta L}$
	 $dq=p_l*d_l$
	 $q=\int_l \rho_l*d_l$
### Problema 1

Se considera o spira de la raza $a$ incarcata cu densitatea lineica de sarcina, $\rho_l$=const., sa se determine expresia intensitatii campului electric in punctul $P$ situat la distanta $z_0$ fata de centrul spirei, pe axa de simetrie a acestuia folosind metoda directa.
![[Seminar 1 2024-10-07 08.39.09.excalidraw]]
$$
d\vec{E_v}=\frac{dq}{4\pi\epsilon_0*r^2}*\frac{\vec{r}}{r}
$$
$dE_v$ Merge pe aceeasi directie cu $r$, iar daca sarcina ar fi negativa ar merge in jos.
$$
dE_v=\frac{\rho l*dl}{4\pi\epsilon_0*r^2}
$$
$$
dE_z=cos(\alpha)=\frac{\rho*dl}{4\pi\epsilon_0*r^2}
$$
$$
dE_z=\frac{\rho l*dl}{4\pi\epsilon_0*r^2}*\frac{r}{z_0}
$$
$$
dE_z=\frac{\rho_l*dl*z_0}{4\pi\epsilon_0*(z_0^2+a^2)^\frac{3}{2}};r=\sqrt{z_0^2+a^2}
$$

$$
E_z=\int_{l}\frac{\rho l * z_0 *dl}{4\pi\epsilon_0*(z_0^2+a^2)^\frac{3}{2}}\int_l dl
$$
$$
E_z = \frac{\rho_l z_0}{4\pi\epsilon_0*(z_0^2+a^2)^\frac{3}{2}}*2\pi a
$$
$$
E_z=\frac{\rho l z_0 a}{2\epsilon_0(z_0^2+a^2)^\frac{3}{2}}\big[\frac{V}{m}\big]
$$
$$
\vec{E}_z=\frac{\rho l z_0 a}{2\epsilon_0(z_0^2+a^2)^\frac{3}{2}}*\frac{\vec{r}}{r}
$$

## Teorema lui Gauss pentru calculul intensitatii electrice in vid

+ Ne ajuta sa determinam intensitatea curenctului electric in vid;
+ Se poate aplica doar in probleme in care exista simetrie;
### Enunt

Fluxul intensitatii campului electrostatic in vid, $\psi_\sum$, prin orice suprafata inchisa $\Sigma$, este egal cu raportul dintre sarcina electrica cuprinsa in interiorul suprafetei $\Sigma$,$\rho_\Sigma$ si permitivitatea absoluta a vidului $\epsilon_0$.
$$
\psi_\Sigma=\oint_\Sigma\vec{E_v}*\vec{dA}=\frac{q_\Sigma}{\epsilon_0}
$$
### Etape de calcul:
1. Se verifica daca se poate aplica teorema lui Gauss(mediul este vidul si campul prezinta simetrie);
2. Se alege o suprafata de integrare $\Sigma$ astfel incat punctul de calcul sa se afle pe aceasta suprafata;
3. Se figureaza vectorul intensitatii campului electric $E_v$ si respectiv vectorul elementului de arie $\vec{dA}$;
4. Se calculeaza fluxul vectorului intensitatii campului electric $\vec{E_v}$:$$\Psi_\Sigma=\oint_\Sigma*\vec{E_v}*\vec{dA}(2)$$
5. Se determina sarcina din interiorul suprafetei $\Sigma$    $q_\Sigma=..$
6. Se introduce (2)si(3) in (1) si se determina intensitatea campului electric in vid: $E_v=..$


### Problema 2

Se considera un fir conductor rectiliniu infinit lung, plasat in vid si incarcat cu sarcina uniform distribuita lineic cu densitatea $\rho_l$.Sa se calculeze intensitatea campului electric in vid, $E_v$, intr-un punct $P$,generic situat la distanta $R$ fatade conductor, utilizand teorema lui Gauss.

![[Seminar 1 2024-10-07 09.20.00.excalidraw]]
$$
\Psi_\Sigma=\oint_\Sigma\vec{E_v}*\vec{dA}=\frac{q_\Sigma}{\epsilon_0}
$$
1. Simetrie radiala, $\epsilon_0$
2. $\Sigma$
3. $Al: \vec{E_v}||d\vec{A}=>cos(0)=1$
4. $\Psi_\Sigma=\oint_\Sigma{\vec{E_v}*d\vec{A}}=\int_Al{E_v*dA*cos(0)}+\int_{A_{l1}}E_v*dA*cos(90)+\int_{a_{l2}}E_v*dA*cos(90)$
	$\Psi=E_v2\pi R l$
	
	 **Cilindru**:
	+ $Al=2\pi r h$
	+ $A_b=\pi*\frac\pi r^2$
		
	**Sfera**:
	+ $A=4*\pi r^2$
	+ $V=\frac{4 \pi r^3}{3}$
		
	**Cerc**:
	+ $l=2 \pi r$
	+ $A=\pi r^2$

5. $q_\Sigma=\rho_l*l$
6. $E_v*2\pi R l=\frac{\rho l*l}{\epsilon_0}$
	$\vec{E_v}=\frac{\rho l}{2\pi R \epsilon_0}$

#### Observatie:
Pentru verificare->Daca avem simetrie Cilintrica sau axiala, tot timpul rezultatul va fi sub forma
Observatie: Toate punctele aflate pe suprafata Al se afla la aceeasi distanta fata de fie  $\implies\frac{k}{r}$
