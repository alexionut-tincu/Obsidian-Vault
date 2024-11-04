## I. Probabilități
### Spațiul de probabilități
#### Definiție
Numim:
a) **Experiment**: Orice rezultat posibil obținut în urma unui fenomen aleator. Notație: $\omega$
b) **Spațiul total**: Mulțimea tuturor experimentelor/rezultatelor posibile. Notație: $\Omega$
#### Exemple:
a) Arunc cu zarul (variabile discrete)
$\Omega=\{\omega_1=1,\omega_2=2,...,\omega_6=6\}$ (finit)
b) Numărul de vizitatori pe un site (variabile discrete)
$\Omega=\{0,1,2,...\}=\mathbb{N}$ (inifint numărabil)
c) Durata de rulare a unui cod (variabile continue)
$\Omega=(0,+\infty)$ (inifinite nenumărabil)

#### Definiție
Numim **eveniment** orice mulțime de experimente și o reprezentăm, de regulă, sub forma:
$A=\{\omega\in\Omega:\omega\text{ satisface o propozitie data}\}\subseteq\Omega$
#### Exemplu
Evenimentul de a da cu zarul cu un număr par:
$A=\{2,4,6\}\in\Omega=\{1,2,3,4,5,6\}$

#### Operații logice cu evenimente
a) $A$ sau $B$: $A\cup B$
b) $A$ și $B$: $A\cap B$
c) $A$ și nu $B$: $A\setminus B$
d) nu $A$: $A^C=A\cap B^C$
e) $A$ și $B$ formează o partiție în $\Omega$
$\begin{cases}A\cap B=\varnothing\\ A\cup B=\Omega\end{cases}$

#### Legile lui De Morgan
a) $(A\cup B)^C=A^C\cap B^C$ și $(A\cap B)^C=A^C\cup B^C$
b) $(\bigcup_n A_n)^C=\bigcap_n A_n^C$ și $(\bigcap_n A_n)^C=\bigcup_n A_n^C$

#### Definiție
O familie de evenimente $\varnothing\neq\mathcal{F}\subseteq\mathcal{P}(\Omega)$ se numește $\sigma\text{-algebra}$ dacă:
a) $A\in\mathcal{F}\Rightarrow A^C\in\mathcal{F}$
b) $(A_n)_n\subseteq\mathcal{F}\Rightarrow\bigcup_n A_n\in\mathcal{F}$
Notație: $(\Omega,\mathcal{F})$ spațiu măsurabil

#### Proprietate
$(A_n)_n\subseteq\mathcal{F}\Rightarrow\bigcap_n A_n\in\mathcal{F}$

#### Demonstrație
$(A_n)_n\subseteq\mathcal{F}\Rightarrow(A_n^C)_n\subseteq\mathcal{F}\Rightarrow\bigcup_n A_n^C\in\mathcal{F}\Rightarrow(\bigcup_n A_n^C)^C=\bigcap_n A_n\in\mathcal{F}$
#### Exemple
a) D