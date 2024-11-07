## Exercițiul 1
Un hard disk are o probabilitate de $5\%$ să se defecteze. Pentru a proteja informația, s-au realizat două backupuri independente, fiecare având o probabilitate de $1\%$ să se defecteze. Se consideră că hard disk-ul și cele două backupuri sunt evenimente independente. Informația stocată se pierde doar dacă toate cele trei dispozitive se defectează simultan. Care este probabilitatea ca informația să nu se piardă?

$\mathbb{P}(D_h)=0.05$
$\mathbb{P}(D_{b_i})=0.01,\forall i\in\{1,2\}$
$D_h\perp\!\!\!\perp D_{b_i},\forall i\in\{1,2\}$
$\mathbb{P}(I)=1-\mathbb{P}(D_h\cap D_{b_1}\cap D_{b_2})$
---
$\mathbb{P}(I)=?$
---
$\mathbb{P}(I)=1-\mathbb{P}(D_h\cap D_{b_1}\cap D_{b_2})$
$\mathbb{P}(I)=1-\mathbb{P}(D_h)\cdot\mathbb{P}(D_{b_1})\cdot\mathbb{P}(D_{b_2})$
$\mathbb{P}(I)=1-0.05\cdot0.01\cdot0.01$
$\mathbb{P}(I)=0.999995$

## Exercițiul 2
Un nou virus ne poate infesta calculatorul fie prin intermediul unui e-mail spam sau prin intermediul unui site nesecurizat. Sunt $32\%$ șanse să îl primim prin intermediul e-mailului și $46\%$ șanse să îl primim prin intermediul unui site. De asemenea, sunt șanse de $29\%$ ca virusul să fie primit atăt prin intermediul e-mailului cât și prin intermediul unui site. Care e probabilitatea ca virusul să nu ne infesteze deloc calculatorul?

$\mathbb{P}(E)=0.32$
$\mathbb{P}(M)=0.46$
$\mathbb{P}(E\cap M)=0.29$
$\mathbb{P}(S)=1-\mathbb{P}(E\cup M)$
---
$\mathbb{P}(S)=?$
---
$\mathbb{P}(S)=1-\mathbb{P}(E\cup M)$
$\mathbb{P}(S)=1-(\mathbb{P}(E)+\mathbb{P}(M)-\mathbb{P}(E\cap M))$
$\mathbb{P}(S)=1-(0.32+0.46-0.29)$
$\mathbb{P}(S)=0.51$

## Exercițiul 3
Pariem o sumă de $s$ lei pe o aruncare cu banul. Dacă pică cap, primim $100\cdot a\%$ din sumă, iar dacă pică pajură, pierdem $100\cdot b\%$ din sumă, unde $[a,b]\in[0,1]$ astfel încât $a>b$. Prin urmare, a juca o singură dată acest joc este avantajos pentru noi. Pentru ce valori alre lui $a$ și $b$ jucarea de mai multe ori a acestui joc este dezavantajoasă pentru noi? (Exemplu: Valorile $a=0.5$ și $b=0.4$ discutate în cursul 1).

