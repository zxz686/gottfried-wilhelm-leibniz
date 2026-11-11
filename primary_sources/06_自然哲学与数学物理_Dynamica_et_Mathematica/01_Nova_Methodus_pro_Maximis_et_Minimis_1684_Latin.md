# Nova Methodus pro Maximis et Minimis (1684)
## Itemque tangentibus, quae nec fractas nec irrationales quantitates moratur, et singulare pro illis calculi genus
### Textus Latinus Primigenius Gotofredi Guilielmi Leibnitii
### [Ex *Actis Eruditorum Lipsiensibus*, Octobris 1684 / C.I. Gerhardt, Mathematische Schriften, Tomus V, pp. 220-226]

---

### Prooemium et Regulae Calculi Differentialis

Sit axis $AX$, et curva $YY$. Sit abscissa $x$, ordinata $y$.
Differentiam quantitatis $x$ appello $dx$, quae est elementum seu augmentum infinite parvum ipsius $x$ ; et differentiam ipsius $y$ appello $dy$.

Hinc regulae fundamenti calculi differentialis sic habent :

1. **De Constantibus** :
   Si $a$ sit quantitas constans, tunc :
   $$da = 0$$

2. **De Additione et Subtractione** :
   $$d(x + y - z) = dx + dy - dz$$

3. **De Multiplicatione** :
   $$d(xy) = x \, dy + y \, dx$$
   Nam $(x + dx)(y + dy) - xy = x \, dy + y \, dx + dx \, dy$. Cum vero $dx \, dy$ sit infinite parvum secundi ordinis respectu priorum, tuto negligitur ; unde manet $x \, dy + y \, dx$.

4. **De Divisione** :
   $$d\left(\frac{x}{y}\right) = \frac{y \, dx - x \, dy}{y^2}$$

5. **De Potestatibus et Radicibus** :
   $$d(x^n) = n \, x^{n-1} \, dx$$
   Sive $n$ sit integer, sive fractus, sive affirmativus, sive negativus.

---

### Determinatio Tangentium, Maximorum et Minimorum

* **Ad Tangentes ducendas** :
  Tangens curvae in quovis puncto determinatur per rationem differentiarum ordinatae ad abscissam :
  $$\frac{dy}{dx}$$
  Subtangens vero invenitur facillime sine ullo calculo prolixo aut extractione radicum.

* **Ad Maxima et Minima invenienda** :
  Quando quantitas crescit, $dy$ est positiva ; quando decrescit, $dy$ est negativa.
  Ergo in ipso puncto maximi vel minimi, ubi quantitas neque crescit neque decrescit, differentia evanescit :
  $$dy = 0$$
  Vel, si quantitas vertatur in contrarium per infinitum, $dy = \infty$.

* **De Punctis Flexus Contrarii** :
  Quando differentia prima $dy$ est ipsa maxima vel minima, differentia secunda $d(dy)$ seu $d^2y$ fit aequalis nihilo :
  $$d^2y = 0$$

Haec est methodus generalissima, quae omnes veterum Geometrarum difficultates et ambages uno ictu superat, et omnia curvarum problemata ad purum calculum mechanicum ac certum redigit.
