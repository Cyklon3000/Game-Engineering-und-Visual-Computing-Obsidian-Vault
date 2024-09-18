#Aufschrieb #Mathe-Vorkurs 
### f(x) = 0 : Gleichung von Grad $n \geq 5$
Gleichungen mit transzendenten Stellen und Polynomen.

### 1) Praktisches Einsetzen
z. B. $f(x) = x^3 - x - 1$

| $x$  | $f(x)$  |
| ------ | --------- |
| $1$  | $4,25$  |
| $2$  | $9,42$  |
| $3$  | $19,41$ |
| $-1$ | $-0,5$  |
Durch Einsetzen von Werten $f(x) \rightarrow 0$ bringen.

### 2) Sekantenverfahren (Regula Falsi)
#### Sekantengleichung
$y_s = \frac{f(x_1) - f(x_2)}{x_1 - x_2} \cdot (x - x_2) + f(x_2)$
Setze $y_s = 0$:
$x = x_2 - \frac{f(x_2)}{\frac{f(x_1) - f(x_2)}{x_1 - x_2}}$
- Beispiel: $f(x) = x^3 - x - 1$
- Es gilt $f(x_2) \cdot f(x_1) < 0$

| $x_1$ | $x_2$ | $f(x_1)$ | $f(x_2)$ | $x$    |
| ----- | ----- | -------- | -------- | ------ |
| $1$   | $2$   | $-0,5$   | $4,25$   | $1,5$  |
| $1,5$ | $2$   | $2,6$    | $4,25$   | $1,75$ |
| ...   | ...   | ...      | ...      | ...    |
<iframe style="overflow: hidden;"src="https://cyklon3000.github.io/Function-Solver-Visualization/Sekanten%20Verfahren" width="100%" height="550px"></iframe>

### 3) Newtonverfahren
#### Tangentengleichung
$y_t = f'(x_1) \cdot (x - x_1) + f(x_1) = 0$
Lösung:
$x = x_1 - \frac{f(x_1)}{f'(x_1)}$
- Beispiel: $f(x) = x^3 - x - 1$
$f'(x) = 3x^2 - 1$
- Start: $x_1 = 1$

| $x_1$ | $f(x_1)$ | $f'(x_1)$ | $x$   |
| ------- | ---------- | ----------- | ------- |
| $1$   | $4,25$   | $2$       | $1,5$ |
| $1,5$ | $0,875$  | $5,75$    | $1,2$ |
| ...     | ...        | ...         | ...     |
