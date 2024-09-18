#Aufschrieb #Mathe-Vorkurs 
## Definitionen
$|x| = \begin{cases} x & \text{für } x \geq 0 \ \newline -x & \text{für } x < 0 \end{cases}$
$|a| = 3 \Leftrightarrow a = 3 \text{ oder } a = -3$ 
$|0| = 0$
$|f(x)| = \begin{cases} f(x) & \text{für } x \geq 0 \ \newline f(-x) & \text{für } x < 0 \end{cases}$
![[Funtionsgraphen f_sin und g_abs(sin).png]]
## Betragsgleichungen auflösen durch Fallunterscheidung (!)
Beispiel: $|x+1| + |x-2| < 5$
### Fallunterscheidung:
I: $x < -1$ : $-(x+1) - (x-2) < 5$ 
II: $-1 \leq x \leq 2$ : $(x+1) - (x-2) < 5$ 
III: $x \geq 2$ : $(x+1) + (x-2) < 5$

I: $x < -1$ : 
	$-x-1 - x+2 < 5$ 
	$-2x + 1 < 5$
	$-2x < 4$
	$x \geq -2$ $\qquad \large L_I = [-2, -1[$
II: $-1 \leq x \leq 2$ : 
	$x+1 - x+2 < 5$
	$3 < 5$
	$0 < 2$ $\qquad \large L_{II} = [-1, 2[$
III: $x \geq 2$ : 
	$x+1 + x-2 < 5$
	$2x - 1 < 5$
	$2x < 6$ 
	$x < 3$ $\qquad \large L_{III} = [2, 3]$

$\large L = L_I \cup L_{II} \cup L_{III} = [-2, 3]$