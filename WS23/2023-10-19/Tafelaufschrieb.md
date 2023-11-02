## 1.1 Einleitung
### 1.1.1 Mathematik und Informatik

Die Informatik verwendet 
- die mathematische Notation und Begriffsbildung
- die mathematische Denkweise
- mathematische Ergebnisse

Mathematische Methodologie:
1. Definition - *definiere Begriffe formal*
2. Satz - *formuliert whare Aussagen*
3. Beweis - *beweise diese Aussagen*

Beispiel: natürliche Zahlen $0,1,2,3,...$, Addition, Multiplikation, die Ordnung und deren Eigenschaften seien bereits definiert beziehungsweise bewiesen.

> z.B gilt $(a \cdot b) \cdot c = a \cdot (b \cdot c)$ (Assoziativgesetz)

**Definition:** Es seien $t$ und $n$ natürliche Zahlen, $t$ sei ungleich $0$. Dann teilt $t$ die Zahle $n$, falls es ein $k$ gibt mit $n = k \cdot t$. Die Null teilt keine Zahl, auch nicht die Null.

$t$ ist __Teiler__ von $n$
$n$ ist __Vielfaches__ von $t$ 
(ganze Zahlen $..., -2, -1, 0, 1, 2, ...$ $2,3,-2,-3$ teilen $6, -6$)

Für $n$ ungleich $0$ heißen $1$ und $n$ __triviale Teiler__ von $n$.
Eine Primzahl ist eine natürliche Zahl ungleich $0$ und $1$, die nur triviale Teiler hat. ($2,3,5,7,11,13,...$)

__5 Lemma:__ Sei $n$ ungleich $1$ eine natürliche Zahl. Dann wird $n$ von einer Primzahl geteilt.

__Beweis:__ Für $n=0$ oder $n$ prim ist die Aussage klar. Wir können also annehmen: $n \neq 0,1$ $n$ nicht prim. Nach Definition der Primzahl hat $n$ einen _nicht trivialen_ Teiler.

Sei $t$ der kleinste nicht triviale Teiler von $n$ 
Wir zeigen, dass $t$ prim ist.

Falls $t$ nicht prim wäre, hat $t$ einen nicht trivialen Teiler $t'$ es folgt $1 < t' < t < n$. Weiter ist $t'$ Teiler von $n$ da gilt: $n = k \cdot t$ und $t = k' \cdot t'$ dann folgt $n=k\cdot t = k \cdot (k' \cdot t') = (k \cdot k') \cdot t'$

WIDERSPRUCH!!!

__Satz von Euklid__ Es gibt unendlich viele Primzahlen

__Beweis:__ Wir nehmen an, es gäbe nur endlich viele Primzahlen $p_1, ..., p_t$. Sei $n = p_1, ..., p_t$. Dann wird $n$ von alle $p_i, 1 = i\leq t$, geteilt, zum Beispiel gilt $n = (p_i,...,p_t) \cdot p_1$

Somit wird $n + 1$ durch kein $p_i$ geteilt, dafür müsste gelten, dass $p_i$ die Zahl $(n + 1) - n = 1$ teilt.

WIDERSPRUCH: __Lemma 5__: $n+1$ hat keinen Teiler, der prim ist.

### 1.1.2 Mengenlehre

Menge $\widehat{=}$ Zusammenfassung von Objekten, den Elementen der Menge.
Schreibweisen für Mengen: 
$\mathbb{N} = \{0,1,2,...\}$ $U = \{1,2,3,...\}$ 
$A = \{2,3,5,7,11\}$ $B = \{e,...,m\}$

$1 \in \mathbb{N}, 1 \in U, 1 \notin A$

##### Gleichheit von Mengen (Extensionalitätsprinzip)
__Definition:__ Mengen $A$ und $B$ sind _gleich_, falls beide Mengen dieselben Elemente enthalten.
$A$ ist Teilmenge von $B$, falls jedes Element von $A$ auch Element von $B$ ist, Kurz: $A \subseteq B$
Es gibt eine _leere Menge_, geschrieben als $\{\}$ oder $\emptyset$ die keine Elemente enthalten. Für alle Mengen $A$ gilt $\emptyset \leq A$.  

##### Aussonderung
$P = \{n \in \mathbb{N} : n\ prim\} = \{2,3,5,7,11,...\}$
$U = \{n\in\mathbb{N} : n\ gerade\} = \{0,2,4,...\}$

$\mathbb{N}\ x\ \mathbb{N} (a,b)$
 
