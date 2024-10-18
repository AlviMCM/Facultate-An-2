# Problema 1

![[Curs 3 2024-10-17 08.22.45.excalidraw]]
$$
\begin{gathered}
TKI:[A]*[\underline{I}]=[0]\\
TKII:[B]*[\underline{U}]=[0]\\
L{0}[\underline{U}]+[\underline{E}]=[Z]*[\underline{I}]\\
\end{gathered}

$$

$$
A= 
\overbrace{
\begin{gathered}
\Sigma_{1}\\
\Sigma_{2}\\
\Sigma_{3}
\end{gathered}
\begin{cases}
\begin{bmatrix}
0 & 0 & 0 & -1 & 1\\
1 & -1 & 0 & -1 & 0 \\
0 & 1 & 1 & 0 & 0
\end{bmatrix}
\end{cases}}

$$

$$
B=
\begin{bmatrix}
1 & 0 & 0 & 1 & 1 & 0 \\
1 & 1 & -1 & 0 & 0 & 0 \\
0 & 0 & -1 & 0
\end{bmatrix}
$$
$$
Z=\begin{bmatrix}
R_{1} & - & - & - & - & -j\omega L_{25} \\
- & j\omega l_{2} & - & - & - & - \\
- & - & \frac{1}{j\omega C_{3}} & - & - & - \\
- & - & - & R_{4}+j\omega L_{4} & j\omega L_{45} & - \\
- & j\omega{L_{25}} & - & j\omega L_{45} & j\omega L_{5}-j\omega L_{56} & - \\
- & - & - & - & - & -j\omega L_{56}R_{6}+j\omega L_{6}
\end{bmatrix}
$$
$$
\begin{gathered}
[B]|[\underline{U}]+[\underline{E}]=[\underline{Z}]*[\underline{I}]\implies[B]*[\underline{U}]+[\underline{B}]*[\underline{E}]=[\underline{B}]*[\underline{Z}]*[\underline{I}]\\
\implies[\underline{B}]*[\underline{Z}]*[\underline{I}]=[\underline{B}]*[\underline{E}]
\end{gathered}
$$
# Problema 2

$$
\begin{gathered}
P_{2}:[\underline{I}]=[B]^{tr}[\underline{I_{c}}]
\end{gathered}

$$
# Problema 3

$$
P_{3}:[\underline{U}]=[A]^{tr}*[\underline{V_{n}}]
$$
```c
int main(){
return -1;
}
```