# Quadratische Gleichung

Eine quadratische Gleichung ist eine Gleichung, bei der die Unbekannte quadriert wird. Das Lösen einer quadratischen
Gleichung ist identisch mit dem Bestimmen der Nullstellen einer quadratischen Funktion.

::: info Quadratische Gleichung  
Eine quadratische Gleichung hat die allgemeine Form

$[ax^2+bx+c=0]$

wobei $(a \neq 0)$ sein muss.
:::

Beispiele für quadratische Gleichungen:
  - $(2x^2-8x+4=0)$
  - $(7x^2=9x)$
  - $((x+2)^2=-1 \Leftrightarrow x^2+4x+5=0)$

## Bezeichungen
Liegt eine Gleichung in allgemeiner Form $(ax^2+bx+c=0)$ vor, bezeichnet man
  - $(ax^2)$ als quadratisches Glied
  - $(bx)$ als lineares Glied
  - und $(c)$ als absolutes Glied.
  
Eine Gleichung mit $(b=0)$, also ohne lineares Glied, heißt auch **reinquadratische Gleichung**.  
Beispiele für reinquadratische Gleichungen:
  - $(x^2=8)$
  - $(6x^2=6)$

### Normalform
Eine quadratische Gleichung ist in Normalform, wenn $(a=1)$ ist.

Eine Gleichung in allgemeiner Form lässt sich einfach in Normalform umschreiben, indem man
die Gleichung durch den Koeffizienten $(a)$ teilt.

$[
\begin{aligned}  
  ax^2+bx+c &= 0 \\  
  \frac{a}{a}x^2+\frac{b}{a}x+\frac{c}{a} &= \frac{0}{a} \\  
  x^2+px+q &= 0  
\end{aligned}  
]$

## Bestimmen der Lösungen (in R)

::: info Anzahl der Lösungen  
Eine quadratische Gleichung kann in $(\R)$ **keine**, **eine** oder **zwei** Lösungen haben.  
:::

Je nach der vorliegenden Form sollte man andere Lösungsansätze wählen, um möglichst schnell zum Ergebnis zu kommen.

### 1. Reinquadratische Gleichungen
Liegt die Form $(ax^2+c=0)$ vor (also $(b=0)$), lassen sich die Lösungen durch einfaches Umformen bestimmen.

#### Beispiel 1
  
Bestimme die Lösungen von $(2x^2-8=0)$.  

Die Gleichung hat kein lineares Glied, sie ist also reinquadratisch. Man muss nun versuchen, mit Äquivalenzumformungen 
das $(x^2)$ alleine auf eine Seite zu bringen.

$[
\begin{aligned}  
  2x^2-8 &= 0    & &| +8 \\  
  2x^2   &= 8    & &| :2 \\  
  x^2    &= 4    &  
\end{aligned}  
]$

Jetzt kann man die Wurzel ziehen, dann ergeben sich die **zwei** Lösungen:

$[
\begin{aligned}  
  x_1 &= \sqrt{4} = 2 \\  
  x_2 &= -\sqrt{4} = -2  
\end{aligned}  
]$

::: warning Beachte: Wurzel ziehen  
Das Ziehen der Wurzel ergibt zwei Lösungen.
$(x^2=y \Longrightarrow x = \pm \sqrt{y})$
:::

#### Beispiel 2
Bestimme die Lösungen von $(3x^2+6=0)$.

Es liegt wieder eine reinquadratische Gleichung vor, da $(b=0)$ ist. Wir formen also wieder um:

$[
\begin{aligned}  
  3x^2+6 &= 0   & &| -6 \\  
  3x^2   &= -6  & &| :3 \\  
  x^2    &= -2  
\end{aligned}  
]$

Hier müsste man $(\sqrt{-2})$ berechnen, die Wurzel aus negativen Zahlen ist aber **nicht definiert**!  
Diese Gleichung hat also **keine Lösung**.

::: danger Beachte: Wurzel ziehen  
Man darf keine Wurzeln aus negativen Zahlen ziehen.
:::

### 2. Gleichungen ohne absolutes Glied
Hat die Gleichung die Form $(ax^2+bx=0)$, also wenn $(c=0)$ ist,
kann man die Lösung durch Ausklammern von $(x)$ bestimmen.

#### Beispiel
Bestimme die Lösungen von $(2x^2+4x=0)$.

$[
\begin{aligned}  
  2x^2+4x        &= 0  & | \: x \text{ ausklammern} \\  
  x \cdot (2x+4) &= 0  
\end{aligned}  
]$

Nach dem Satz vom Nullprodukt ist ein Produkt null, wenn eines seiner Faktoren null ist. Damit ist die erste 
Lösung $(x_1=0)$ schon gefunden.  
Für die zweite Lösung muss man noch $(2x+4=0)$ ausrechnen.

$[
\begin{aligned}  
  2x+4    &= 0   & &| -4 \\  
  2x      &= -4  & &| :2 \\  
  x       &= -2  
\end{aligned}  
]$

Die beiden Lösungen der Gleichung sind also $(x_1=0)$ und $(x_2=-2)$.

### 3. Allgemeine Gleichungen
Liegt weder Form (1) noch Form (2) vor, dann kann man die Lösungen nicht durch einfaches Umformen
bestimmen.  
Um Gleichungen in allgemeiner Form zu lösen, benötigt man die 
[Mitternachtsformel](../mitternachtsformel). Setzt man die Koeffizienten $(a)$, $(b)$ und $(c)$ in die 
Formel ein, ergeben sich die Lösungen $(x_1)$ und $(x_2)$.

$[\boxed{x_{1/2}=\frac{-b \pm \sqrt{b^2-4ac}}{2a}}]$

Die Mitternachtsformel wird auf der nächsten Seite im Detail betrachtet.
