# Mitternachtsformel

Mithilfe der Mitternachtsformel (auch abc-Formel genannt) kann man quadratische Gleichungen lösen bzw.
die Nullstellen einer quadratischen Funktion bestimmen.

::: info Mitternachtsformel  
Gegeben ist eine Gleichung der Form $(ax^2+bx+c=0)$ (allgemeine Form).  
Dann lauten die Lösungen $(x_1)$ und $(x_2)$ dieser Gleichung:

$[
\begin{aligned}  
  x_{1} &= \frac{-b + \sqrt{b^2-4ac}}{2a} \\[1.5em]  
  x_{2} &= \frac{-b - \sqrt{b^2-4ac}}{2a}  
\end{aligned}  
]$

Oder in Kurzschreibweise zusammengefasst:

$[\boxed{x_{1/2}=\frac{-b \pm \sqrt{b^2-4ac}}{2a}}]$

Wobei $(\boxed{b^2-4ac})$ auch als Diskriminante $(D)$ bezeichnet wird.
:::

## Anwendung Schritt für Schritt
Mit diesen fünf Schritten kann das Bestimmen der Lösungen nicht schiefgehen.

**Beispielaufgabe:**  
Bestimme die Lösungen der Gleichung: $(20x + 2x^2 + 4 = 4x -20)$.

### Schritt 1: In allgemeine Form bringen
Zu Beginn sollte man die Gleichung in allgemeine Form $(ax^2+bx+c=0)$ bringen. Dieser Schritt erhöht die 
Übersichtlichkeit erheblich und verringert damit Fehler.  
Verwende zur Umformung dir bekannte Rechenregeln (z.B. Ausmultiplizieren, Zusammenfassen oder "auf die andere Seite bringen").

**In unserem Beispiel:**

$[
\begin{aligned}  
  20x + 2x^2 + 4   &= 4x -20   & | +20 \\  
  20x + 2x^2 + 24  &= 4x       & | -4x \\  
  16x + 2x^2 + 24  &= 0        & | \text{ sortieren} \\  
  2x^2 +16x +24    &= 0        &  
\end{aligned}  
]$

### Schritt 2: Überprüfung
Die Mitternachtsformel kann nur bei **quadratischen** Gleichungen angewendet werden. Wenn es ein $(x)$ mit höheren
Exponenten als 2 gibt (z.B. $(x^3)$ oder $(x^4)$), lässt sich die Formel _nicht_ anwenden.

Ist die Gleichung reinquadratisch oder hat sie kein absolutes Glied, _sollte_ man die
Mitternachtsformel nicht anwenden, weil man die Lösungen schneller durch Umformen bestimmen kann.

### Schritt 3: Koeffizienten ablesen
Für die Formel benötigt man die Koeffizienten $(a)$, $(b)$ und $(c)$, die sich aus der Gleichung ablesen lassen.  
Dabei ist
  - $(a)$ die Konstante vor dem $(x^2)$
  - $(b)$ die Konstante vor dem $(x)$
  - $(c)$ die alleinstehende Konstante (ohne $(x)$)

Hier ein paar Beispiele:
| Term                              | $(a)$      | $(b)$      | $(c)$      | Anmerkungen                                                 |
| :-------------------------------- | :-----------------------: | :-----------------------: | :-----------------------: | :---------------------------------------------------------- |
| $(4x^2+7x+2=0)$    | $(4)$      | $(7)$      | $(2)$      | Gleichung in allgemeiner Form                               |
| $(-8x^2+x-5=0)$    | $(-8)$     | $(1)$      | $(-5)$     | Vorsicht mit negativen Zahlen!                              |
| $(6x^2+1=0)$       | $(6)$      | $(0)$      | $(1)$      | Manche Terme können fehlen! ($(=0)$)         |
| $(7x^3+2x^2-8=0)$  | $(\times)$ | $(\times)$ | $(\times)$ | Keine quadratische Gleichung! ($(x^3)$)      |
| $(x+11=0)$         | $(\times)$ | $(\times)$ | $(\times)$ | Keine quadratische Gleichung! (kein $(x^2)$) |

**In unserem Beispiel:**  
Aus der Gleichung $(2x^2 +16x +24)$ können wir ablesen: $(a=2,\; b=16,\; c=24)$.

### Schritt 4: Diskriminante ausrechnen
Haben wir die Koeffizienten ermittelt, sollten wir danach die Diskriminante $(D)$ ausrechnen, um zu überprüfen, ob
die Gleichung überhaupt lösbar ist.

::: info Diskriminante einer quadratischen Gleichung  
Die Diskriminante $(D)$ bestimmt, wie viele Lösungen die Gleichung besitzt.

$[D = b^2-4ac]$

Dabei gilt:
  - $(D > 0)$: Die Gleichung hat zwei Lösungen
  - $(D = 0)$: Die hat eine gemeinsame Lösung ($(x_1)$ und $(x_2)$ sind identisch)
  - $(D < 0)$: Die Gleichung hat keine Lösung
:::

**In unserem Beispiel:**  
Wir rechnen die Diskriminante aus:

$[
D = \underbrace{16^2}_{b}-4\cdot \underbrace{2}_{a} \cdot \underbrace{24}_{c} = 256 - 192 = 64 > 0
]$

Da $(D > 0)$ ist, hat die Beispielgleichung zwei Lösungen.

### Schritt 5: In die Formel einsetzen  
Ist $(D \geq 0)$, dann können wir die Koeffizienten in die Formel einsetzen und die Lösungen bestimmen.  
Zur Erinnerung: Eine quadratische Gleichung kann zwei Lösungen haben:

$[
\begin{aligned}  
  x_1 &= \frac{-b + \sqrt{D}}{2a} = \frac{-b + \sqrt{b^2-4ac}}{2a} \\[1.5em]  
  x_2 &= \frac{-b - \sqrt{D}}{2a} = \frac{-b - \sqrt{b^2-4ac}}{2a}  
\end{aligned}  
]$

**In unserem Beispiel:**  
Wir setzen die Koeffizienten und $(D)$ in die Mitternachtsformel ein:

$[
\begin{aligned}  
  x_{1/2} &= \frac{-16 \pm \sqrt{64}}{2\cdot2} = \frac{-16 \pm 8}{4} \\[1.5em]  
  x_1     &= \frac{-16 + 8}{4} = \frac{-8}{4} = -2 \\[1em]  
  x_2     &= \frac{-16 - 8}{4} = \frac{-24}{4} = -6  
\end{aligned}  
]$

Fertig! Die Lösungen der Gleichung sind $(x_1 = -2)$ und $(x_2 = -6)$.
