## Summen
$S_n = \sum_{k=1}^n a_k = a_1 + a_2 + ... + a_n$
### Konstante Reihe
Alle Glieder sind konstant: $a_k = c$ $\sum_{k=1}^n c = n \cdot c$ | $\sum_{k=1}^{\infty} c = \infty$
### Arithmetische Reihe
Differenz zweier Glieder ist konstant: $a_{k+1} - a_k = d$ $a_k = a_1 + (k-1)d$ $\sum_{k=1}^n a_k = a_1 + (a_1+d) + ... + (a_1+(n-1)d) = \frac{a_1+a_n}{2} \cdot n$ $\sum_{k=1}^n (a_1+(k-1)d) = \frac{n}{2}(2a_1 + (n-1)d)$
Spezialfall: $\sum_{k=1}^n k = \frac{n(n+1)}{2}$
### Geometrische Reihe
Quotient zweier Folgeglieder ist konstant: $\frac{a_{k+1}}{a_k} = q$ $a_k = a_1 \cdot q^{k-1}$ $\sum_{k=1}^n a_k = S = a_1 \cdot (1 + q + q^2 + q^3 + ... + q^{n-1})$ $S \cdot q = a_1 \cdot (q + q^2 + q^3 + ... + q^n)$ $S(q-1) = a_1 \cdot (q^n - 1)$ $S(q-1) = a_1 \cdot (q^n-1)$ $S = a_1 \cdot \frac{q^n-1}{q-1}$

$\huge \sum_{k=1}^n a_1 \cdot q^{k-1} = a_1 \cdot \frac{q^n-1}{q-1}$, $q \neq 1$
## Definition: Erfinder des Schachspiels verlangte vom König Sheram
1. Feld: 1 Korn
2. Feld: 2 Körner
3. Feld: 4 Körner
4. Feld: $2^{63}$ Körner
$1 + 2 + ... + 2^63 = \sum{K=1}^64 1*2^{k-1} \approx 1,8...*10^{19}$
$18$ Reiskörner $\approx 1 g \Rightarrow 10^{18g} \approx 10^{12} t$  
## Unendliche Reihen
### Konvergente Reihe
$S = \lim_{n \to \infty} S_n$ existiert endlich
### Divergente Reihe
$\lim_{n \to \infty} S_n$ existiert nicht (oder ist $\infty$)
### Konvergente geometrische Reihe
$S_n = a_1 + a_1q + ... + a_1q^{n-1} = a_1 \frac{1-q^n}{1-q}$, $(|q|<1)$ $S = \lim_{n \to \infty} a_1 \frac{1-q^n}{1-q} = \frac{a_1}{1-q}$
### Beispiele
1. $1 + \frac{1}{2} + \frac{1}{4} + \frac{1}{8} + ... = 2$
2. $3, 3 - \frac{1}{3}, 3 - \frac{1}{3} + \frac{1}{9}, ... = \frac{10}{3}$
### Teleskop-Reihe (Mengoli)
$\sum_{k=1}^{\infty} \frac{1}{k(k+1)} = \sum_{k=1}^{\infty} (\frac{1}{k} - \frac{1}{k+1}) = 2[\frac{1}{1} + (\frac{1}{2} - \frac{1}{2}) + (\frac{1}{3} - \frac{1}{3}) + ...] = 1$
### Baseler Problem (Euler) 1738
$\sum_{k=1}^{\infty} \frac{1}{k^2} = 1 + \frac{1}{4} + \frac{1}{9} + ... = \frac{\pi^2}{6}$
### Divergente Reihen (Beispiele)
1. $\sum_{k=1}^{\infty} 1 = 1 + 1 + 1 + ...$ hat keinen Grenzwert
2. $\sum_{k=1}^{\infty} \frac{1}{k} = 1 + \frac{1}{2} + \frac{1}{3} + ... = 1 + (\frac{1}{2} + \frac{1}{3}) + (\frac{1}{4} + \frac{1}{5} + \frac{1}{6} + \frac{1}{7}) + ... > 1 + \frac{1}{2} + \frac{1}{2} + \frac{1}{2} + ...$
3. $\sum_{k=1}^{\infty} \frac{1}{k}$ ist divergent
4. $\sum_{k=1}^{\infty} \frac{1}{k^2}$ ist konvergent
## Arithmetisch-geometrische Reihe
$\sum_{k=1}^n k \cdot q^k = \frac{q}{(1-q)^2} \cdot (n \cdot q^{n+1} - (n+1) \cdot q^n + 1)$, $q \neq 0,1$