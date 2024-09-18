#Aufschrieb #Mathe-Vorkurs 
## Definition
Eine Folge ist eine eindeutige Zuordnung $n \in \mathbb{N} \to a_n = f(n)$, wobei $a_n \in \mathbb{R}$
## Beispiele
(Kapital bei Zinssatz, Population, Abschreibungen,...)

| $a_n = 1, 3, 5, 7$                                                      | $a_k=k$                                                   |
| ----------------------------------------------------------------------- | --------------------------------------------------------- |
| $b_n = 1, 2, 4, 8, 16$                                                  | $b_k=2^{k-1}$                                             |
| $c_n = \frac{1}{2}, \frac{1}{3}, \frac{1}{4}, \frac{1}{5}$              | $\lim_{k \rightarrow \infty}{c_k=0\quad c_k=\frac{1}{k}}$ |
| $d_n = 1, 1, 2, 3, 5, 8, 13, 21, 34$                                    | Fibonacci: $d_1=1, d_2=2$<br>$d_{k+1} = d_{k-1} + d_k$    |
| $e_n = -1, 1, -1, 1, -1, 1$                                             | $e_n=(-1)^4$                                              |
| $f_n = \frac{1}{2}, \frac{2}{3}, \frac{3}{4}, \frac{4}{5}, \frac{5}{6}$ | $\frac{1}{2^{k-1}}=2^{-k-1}$                              |
## Darstellungsformen
1. Explizit: $a_n = f(n)$, z.B. $b_n = 2^{n-1}$
2. Rekursiv: $a_{n+1} = f(a_n)$, z.B. $a_{n+2} = a_{n+1} + a_n$
## Wichtige Begriffe
### Arithmetische Folge
$a_{n+1} = a_n + d$
### Geometrische Folge
$\frac{a_{n+1}}{a_n} = q$, $a_n = a_1 \cdot q^{n-1}$
### Konvergente Folge
Strebt einem Grenzwert zu: $\lim_{n \to \infty} a_n = a \in \mathbb{R}$
### Divergente Folge
Hat keinen Grenzwert
## Spezielle Folgen
$a_n = k$ (konstant) $b_n = 2^{n-1}$ $c_n = \frac{1}{n}$ $d_n = \frac{1}{n^2}$
### Fibonacci-Folge
$a_1 = 1$ 
$a_2 = 1$
$a_{n+2} = a_{n+1} + a_n$ 
$a_n = \frac{1}{\sqrt{5}}[(\frac{1+\sqrt{5}}{2})^n - (\frac{1-\sqrt{5}}{2})^n]$
$e_n = (-1)^n$
$f_n = \frac{n}{n+1} = 2 - \frac{1}{n+1}$