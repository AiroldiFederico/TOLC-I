# Valore Assoluto

## 1. DEFINIZIONE E CONCETTI DI BASE

### 1.1 Definizione matematica
Il valore assoluto di un numero reale $x$, indicato con $|x|$, è definito come:

$$|x| = \begin{cases}
x & \text{se } x \geq 0 \\
-x & \text{se } x < 0
\end{cases}$$

In altre parole, il valore assoluto di un numero positivo o zero è il numero stesso, mentre il valore assoluto di un numero negativo è l'opposto del numero (cioè, il numero senza il segno meno).

**Esempi**:
- $|5| = 5$ (poiché $5 > 0$)
- $|0| = 0$ (poiché $0 = 0$)
- $|-7| = -(-7) = 7$ (poiché $-7 < 0$)
- $|-\pi| = \pi$ (poiché $-\pi < 0$)

### 1.2 Interpretazione geometrica
Il valore assoluto di un numero rappresenta la sua distanza dall'origine sulla retta numerica, indipendentemente dalla direzione.

**Esempio**: Sia $|x| = 3$
Geometricamente, questo rappresenta tutti i punti che si trovano a una distanza di 3 unità dall'origine, cioè i punti $x = 3$ e $x = -3$.

### 1.3 Forme alternative di definizione
- $|x| = \sqrt{x^2}$ per ogni $x \in \mathbb{R}$
- $|x| = \max\{x, -x\}$ per ogni $x \in \mathbb{R}$

## 2. PROPRIETÀ DEL VALORE ASSOLUTO

### 2.1 Proprietà fondamentali
Per ogni $a, b \in \mathbb{R}$ e $n \in \mathbb{Z}$:

1. $|a| \geq 0$, e $|a| = 0$ se e solo se $a = 0$
2. $|-a| = |a|$
3. $|a \cdot b| = |a| \cdot |b|$
4. $\left|\frac{a}{b}\right| = \frac{|a|}{|b|}$ (per $b \neq 0$)
5. $|a^n| = |a|^n$
6. $\sqrt{a^2} = |a|$

**Esempio**: Verificare la proprietà 3 con $a = -3$ e $b = 4$
$|a \cdot b| = |(-3) \cdot 4| = |-12| = 12$
$|a| \cdot |b| = |-3| \cdot |4| = 3 \cdot 4 = 12$
La proprietà è verificata.

### 2.2 Disuguaglianze triangolari
Per ogni $a, b \in \mathbb{R}$:

1. $|a + b| \leq |a| + |b|$ (disuguaglianza triangolare)
2. $|a - b| \leq |a| + |b|$
3. $|a + b| \geq \big| |a| - |b| \big|$ (disuguaglianza triangolare inversa)
4. $|a - b| \geq \big| |a| - |b| \big|$

**Dimostrazione della disuguaglianza triangolare**:
$-|a| \leq a \leq |a|$ e $-|b| \leq b \leq |b|$
Sommando: $-|a| - |b| \leq a + b \leq |a| + |b|$
Quindi: $-(|a| + |b|) \leq a + b \leq |a| + |b|$
Ciò significa che $|a + b| \leq |a| + |b|$

**Esempio**: Verificare la disuguaglianza triangolare con $a = -3$ e $b = 5$
$|a + b| = |(-3) + 5| = |2| = 2$
$|a| + |b| = |-3| + |5| = 3 + 5 = 8$
$2 \leq 8$, quindi la disuguaglianza è verificata.

### 2.3 Casi di uguaglianza nella disuguaglianza triangolare
$|a + b| = |a| + |b|$ se e solo se $ab \geq 0$ (cioè, $a$ e $b$ hanno lo stesso segno o almeno uno di essi è zero)

**Esempio**: Con $a = 3$ e $b = 4$ (stesso segno)
$|a + b| = |3 + 4| = |7| = 7$
$|a| + |b| = |3| + |4| = 3 + 4 = 7$
L'uguaglianza è verificata.

**Esempio**: Con $a = -3$ e $b = 4$ (segni diversi)
$|a + b| = |-3 + 4| = |1| = 1$
$|a| + |b| = |-3| + |4| = 3 + 4 = 7$
$1 < 7$, quindi non c'è uguaglianza.

## 3. EQUAZIONI CON VALORE ASSOLUTO

### 3.1 Equazioni del tipo $|f(x)| = k$
- Se $k > 0$, allora l'equazione è equivalente a: $f(x) = k$ oppure $f(x) = -k$
- Se $k = 0$, allora l'equazione è equivalente a: $f(x) = 0$
- Se $k < 0$, allora l'equazione non ha soluzioni (poiché il valore assoluto è sempre non negativo)

**Esempio**: Risolvere $|2x - 3| = 5$
Soluzione: Poiché $5 > 0$, l'equazione equivale a:
$2x - 3 = 5$ oppure $2x - 3 = -5$
$2x = 8$ oppure $2x = -2$
$x = 4$ oppure $x = -1$
L'insieme delle soluzioni è $\{-1, 4\}$.

**Esempio**: Risolvere $|3x + 1| = 0$
Soluzione: $3x + 1 = 0$
$3x = -1$
$x = -\frac{1}{3}$
L'insieme delle soluzioni è $\{-\frac{1}{3}\}$.

**Esempio**: Risolvere $|x - 2| = -3$
Soluzione: Poiché $-3 < 0$ e il valore assoluto è sempre non negativo, l'equazione non ha soluzioni.

### 3.2 Equazioni del tipo $|f(x)| = |g(x)|$
Questa equazione è equivalente a: $f(x) = g(x)$ oppure $f(x) = -g(x)$

**Esempio**: Risolvere $|x - 1| = |2x + 3|$
Soluzione: L'equazione equivale a:
$x - 1 = 2x + 3$ oppure $x - 1 = -(2x + 3)$
$x - 1 = 2x + 3$ oppure $x - 1 = -2x - 3$
$-x = 4$ oppure $3x = -2$
$x = -4$ oppure $x = -\frac{2}{3}$
L'insieme delle soluzioni è $\{-4, -\frac{2}{3}\}$.

### 3.3 Equazioni con più valori assoluti
Per equazioni con più valori assoluti, è necessario analizzare i diversi casi possibili in base al segno delle espressioni interne ai valori assoluti.

**Esempio**: Risolvere $|x - 2| + |x + 1| = 5$
Soluzione: Dobbiamo considerare tre casi:
1. $x \leq -1$: entrambe le espressioni sono non positive
   $|x - 2| + |x + 1| = -(x - 2) + -(x + 1) = -x + 2 - x - 1 = -2x + 1 = 5$
   $-2x = 4$
   $x = -2$
   Verifichiamo: $-2 \leq -1$ ✓

2. $-1 < x < 2$: prima espressione negativa, seconda positiva
   $|x - 2| + |x + 1| = -(x - 2) + (x + 1) = -x + 2 + x + 1 = 3 = 5$
   $3 = 5$, che è falso, quindi non ci sono soluzioni in questo intervallo.

3. $x \geq 2$: entrambe le espressioni sono non negative
   $|x - 2| + |x + 1| = (x - 2) + (x + 1) = 2x - 1 = 5$
   $2x = 6$
   $x = 3$
   Verifichiamo: $3 \geq 2$ ✓

L'insieme delle soluzioni è $\{-2, 3\}$.

## 4. DISEQUAZIONI CON VALORE ASSOLUTO

### 4.1 Disequazioni del tipo $|f(x)| < k$
- Se $k > 0$, allora la disequazione è equivalente a: $-k < f(x) < k$
- Se $k = 0$, allora la disequazione non ha soluzioni (a meno che $f(x)$ non sia identicamente zero)
- Se $k < 0$, allora la disequazione non ha soluzioni

**Esempio**: Risolvere $|3x - 2| < 4$
Soluzione: Poiché $4 > 0$, la disequazione equivale a:
$-4 < 3x - 2 < 4$
$-2 < 3x < 6$
$-\frac{2}{3} < x < 2$
L'insieme delle soluzioni è $(-\frac{2}{3}, 2)$.

### 4.2 Disequazioni del tipo $|f(x)| > k$
- Se $k \geq 0$, allora la disequazione è equivalente a: $f(x) < -k$ oppure $f(x) > k$
- Se $k < 0$, allora la disequazione è sempre verificata (poiché il valore assoluto è sempre non negativo)

**Esempio**: Risolvere $|2x + 5| > 3$
Soluzione: Poiché $3 > 0$, la disequazione equivale a:
$2x + 5 < -3$ oppure $2x + 5 > 3$
$2x < -8$ oppure $2x > -2$
$x < -4$ oppure $x > -1$
L'insieme delle soluzioni è $(-\infty, -4) \cup (-1, +\infty)$.

### 4.3 Disequazioni del tipo $|f(x)| \leq k$ e $|f(x)| \geq k$
Queste disequazioni si risolvono in modo analogo ai casi precedenti, includendo anche i punti di frontiera.

**Esempio**: Risolvere $|x - 3| \leq 2$
Soluzione: Poiché $2 > 0$, la disequazione equivale a:
$-2 \leq x - 3 \leq 2$
$1 \leq x \leq 5$
L'insieme delle soluzioni è $[1, 5]$.

**Esempio**: Risolvere $|4x - 1| \geq 7$
Soluzione: Poiché $7 > 0$, la disequazione equivale a:
$4x - 1 \leq -7$ oppure $4x - 1 \geq 7$
$4x \leq -6$ oppure $4x \geq 8$
$x \leq -\frac{3}{2}$ oppure $x \geq 2$
L'insieme delle soluzioni è $(-\infty, -\frac{3}{2}] \cup [2, +\infty)$.

### 4.4 Disequazioni fratte con valore assoluto
Per risolvere disequazioni fratte con valore assoluto, è necessario tener conto anche delle condizioni di esistenza.

**Esempio**: Risolvere $\left|\frac{x-1}{x+2}\right| < 3$
Soluzione: 
Condizione di esistenza: $x \neq -2$

La disequazione equivale a:
$-3 < \frac{x-1}{x+2} < 3$

Analizziamo separatamente:
$\frac{x-1}{x+2} < 3$
$x-1 < 3(x+2)$ se $x+2 > 0$, cioè se $x > -2$
$x-1 < 3x+6$
$-2x < 7$
$x > -\frac{7}{2}$

$\frac{x-1}{x+2} > -3$
$x-1 > -3(x+2)$ se $x+2 > 0$, cioè se $x > -2$
$x-1 > -3x-6$
$4x > -5$
$x > -\frac{5}{4}$

$x-1 < -3(x+2)$ se $x+2 < 0$, cioè se $x < -2$
$x-1 < -3x-6$
$4x < -5$
$x < -\frac{5}{4}$

$x-1 > 3(x+2)$ se $x+2 < 0$, cioè se $x < -2$
$x-1 > 3x+6$
$-2x > 7$
$x < -\frac{7}{2}$

Combinando i risultati e considerando la condizione di esistenza:
$x \in (-\infty, -\frac{7}{2}) \cup (-2, +\infty)$

## 5. APPLICAZIONI DEL VALORE ASSOLUTO

### 5.1 Distanza tra due punti sulla retta reale
La distanza tra due punti $a$ e $b$ sulla retta reale è data da $|a - b|$.

**Esempio**: Calcolare la distanza tra $-3$ e $5$ sulla retta reale.
Soluzione: $|(-3) - 5| = |-8| = 8$

### 5.2 Intorni di un punto
Un intorno di raggio $r > 0$ del punto $a \in \mathbb{R}$ è l'insieme dei punti $x \in \mathbb{R}$ tali che $|x - a| < r$.

**Esempio**: Descrivere l'intorno di raggio $2$ del punto $3$.
Soluzione: $|x - 3| < 2$
$-2 < x - 3 < 2$
$1 < x < 5$
L'intorno è l'intervallo $(1, 5)$.

### 5.3 In problemi di ottimizzazione
Il valore assoluto è utile per descrivere problemi di minimizzazione della distanza o dell'errore.

**Esempio**: Trovare il punto $x$ che minimizza la somma delle distanze dai punti $-1$, $2$ e $5$.
Soluzione: Vogliamo minimizzare la funzione $f(x) = |x - (-1)| + |x - 2| + |x - 5| = |x + 1| + |x - 2| + |x - 5|$.

I punti critici della funzione sono $x = -1$, $x = 2$ e $x = 5$. Calcoliamo i valori della funzione in questi punti:
$f(-1) = |-1 + 1| + |-1 - 2| + |-1 - 5| = 0 + 3 + 6 = 9$
$f(2) = |2 + 1| + |2 - 2| + |2 - 5| = 3 + 0 + 3 = 6$
$f(5) = |5 + 1| + |5 - 2| + |5 - 5| = 6 + 3 + 0 = 9$

Il minimo è raggiunto in $x = 2$ con valore $f(2) = 6$.

## 6. ESERCIZI RISOLTI

1. **Esercizio**: Calcolare il valore di $|3-7|+|-2|+|0|-|-4|$
   **Soluzione**:
   $|3-7|+|-2|+|0|-|-4| = |{-4}|+|{-2}|+|0|-|{-4}| = 4+2+0-4 = 2$

2. **Esercizio**: Risolvere l'equazione $|2x-5|=|3x+1|$
   **Soluzione**:
   L'equazione equivale a:
   $2x-5 = 3x+1$ oppure $2x-5 = -(3x+1)$
   $2x-5 = 3x+1$ oppure $2x-5 = -3x-1$
   $-x = 6$ oppure $5x = -6$
   $x = -6$ oppure $x = -\frac{6}{5}$
   L'insieme delle soluzioni è $\{-6, -\frac{6}{5}\}$.

3. **Esercizio**: Risolvere la disequazione $|x^2-4| \leq 3$
   **Soluzione**:
   $-3 \leq x^2-4 \leq 3$
   $1 \leq x^2 \leq 7$
   $1 \leq x^2$ implica $x \leq -1$ o $x \geq 1$
   $x^2 \leq 7$ implica $-\sqrt{7} \leq x \leq \sqrt{7}$
   Combinando: $-\sqrt{7} \leq x \leq -1$ o $1 \leq x \leq \sqrt{7}$
   L'insieme delle soluzioni è $[-\sqrt{7}, -1] \cup [1, \sqrt{7}]$.

4. **Esercizio**: Risolvere la disequazione $\frac{|x-2|}{|x+1|} < 1$
   **Soluzione**:
   Condizione di esistenza: $x \neq -1$
   
   $\frac{|x-2|}{|x+1|} < 1$ equivale a $|x-2| < |x+1|$
   
   Caso 1: $x \leq -1$
   $|x-2| < |x+1|$
   $-(x-2) < -(x+1)$ (entrambi i termini sono negativi)
   $-x+2 < -x-1$
   $2 < -1$, che è falso. Quindi non ci sono soluzioni in questo intervallo.
   
   Caso 2: $-1 < x < 2$
   $|x-2| < |x+1|$
   $-(x-2) < x+1$ (primo termine negativo, secondo positivo)
   $-x+2 < x+1$
   $-2x < -1$
   $x > \frac{1}{2}$
   
   Caso 3: $x \geq 2$
   $|x-2| < |x+1|$
   $x-2 < x+1$ (entrambi i termini sono positivi)
   $-2 < 1$, che è vero. Quindi l'intervallo $[2, +\infty)$ è parte della soluzione.
   
   Combinando i risultati e considerando la condizione di esistenza:
   $x \in (\frac{1}{2}, -1) \cup (-1, +\infty) = (\frac{1}{2}, +\infty) \setminus \{-1\}$

5. **Esercizio**: Risolvere l'equazione $|x^2-5x+6|=1$
   **Soluzione**:
   $x^2-5x+6 = 1$ oppure $x^2-5x+6 = -1$
   $x^2-5x+5 = 0$ oppure $x^2-5x+7 = 0$
   
   Prima equazione:
   $\Delta = 25-20 = 5$
   $x = \frac{5 \pm \sqrt{5}}{2}$
   $x_1 = \frac{5 + \sqrt{5}}{2} \approx 3.618$
   $x_2 = \frac{5 - \sqrt{5}}{2} \approx 1.382$
   
   Seconda equazione:
   $\Delta = 25-28 = -3$
   Non ci sono soluzioni reali.
   
   L'insieme delle soluzioni è $\{\frac{5 + \sqrt{5}}{2}, \frac{5 - \sqrt{5}}{2}\}$.

6. **Esercizio**: Per quali valori di $k$ l'equazione $|x-3|+|x+1|=k$ ha esattamente tre soluzioni?
   **Soluzione**:
   Consideriamo i tre casi possibili:
   
   Caso 1: $x \leq -1$
   $|x-3|+|x+1| = -(x-3)-(x+1) = -2x+2$
   
   Caso 2: $-1 < x < 3$
   $|x-3|+|x+1| = -(x-3)+(x+1) = 4$
   
   Caso 3: $x \geq 3$
   $|x-3|+|x+1| = (x-3)+(x+1) = 2x-2$
   
   La funzione $f(x) = |x-3|+|x+1|$ è:
   $f(x) = -2x+2$ per $x \leq -1$
   $f(x) = 4$ per $-1 < x < 3$
   $f(x) = 2x-2$ per $x \geq 3$
   
   Per avere esattamente tre soluzioni, $k$ deve essere tale che l'equazione $f(x) = k$ intersechi il grafico di $f$ in esattamente tre punti.
   
   Ciò accade quando $k = 4$, poiché l'equazione diventa:
   $-2x+2 = 4$ per $x \leq -1$, che dà $x = -1$
   $4 = 4$ per $-1 < x < 3$, che è soddisfatta per ogni $x$ nell'intervallo
   $2x-2 = 4$ per $x \geq 3$, che dà $x = 3$
   
   Quindi le tre soluzioni sono $x = -1$ (il punto di confine nel caso 1), qualsiasi $x$ nell'intervallo $(-1, 3)$, e $x = 3$ (il punto di confine nel caso 3).
   
   La risposta è $k = 4$.

7. **Esercizio**: Risolvere il sistema
   $\begin{cases}
   |x+y| = 1 \\
   |x-y| = 3
   \end{cases}$
   
   **Soluzione**:
   Dal primo vincolo: $x+y = 1$ o $x+y = -1$
   Dal secondo vincolo: $x-y = 3$ o $x-y = -3$
   
   Analizziamo tutte le possibili combinazioni:
   
   Caso 1: $x+y = 1$ e $x-y = 3$
   Risolvendo: $x = 2, y = -1$
   
   Caso 2: $x+y = 1$ e $x-y = -3$
   Risolvendo: $x = -1, y = 2$
   
   Caso 3: $x+y = -1$ e $x-y = 3$
   Risolvendo: $x = 1, y = -2$
   
   Caso 4: $x+y = -1$ e $x-y = -3$
   Risolvendo: $x = -2, y = 1$
   
   L'insieme delle soluzioni è $\{(2, -1), (-1, 2), (1, -2), (-2, 1)\}$.

## 7. ERRORI COMUNI DA EVITARE

1. **Confondere $|x^2|$ con $|x|^2$**:
   - $|x^2| = x^2$ per qualsiasi $x$ (poiché $x^2 \geq 0$ per ogni $x \in \mathbb{R}$)
   - $|x|^2 = x^2$ per qualsiasi $x$ (ma la notazione è ridondante)

2. **Linearizzare erroneamente il valore assoluto**:
   - Errore: $|a + b| = |a| + |b|$ ✗ (non sempre vero!)
   - Corretto: $|a + b| \leq |a| + |b|$ (disuguaglianza triangolare)

3. **Eliminare erroneamente il valore assoluto in equazioni**:
   - Errore: $|x| = 5$ implica $x = 5$ ✗ (incompleto!)
   - Corretto: $|x| = 5$ implica $x = 5$ o $x = -5$

4. **Risolvere disequazioni con valore assoluto senza considerare i casi**:
   - Errore: $|x| < 3$ implica $x < 3$ ✗ (incompleto!)
   - Corretto: $|x| < 3$ implica $-3 < x < 3$

5. **Non verificare le soluzioni**:
   - È importante verificare che le soluzioni trovate soddisfino l'equazione o la disequazione originale, specialmente quando si risolvono equazioni con più valori assoluti.

6. **Trattare $\sqrt{x^2}$ come $x$**:
   - Errore: $\sqrt{x^2} = x$ ✗ (non sempre vero!)
   - Corretto: $\sqrt{x^2} = |x|$ (per qualsiasi $x \in \mathbb{R}$)

7. **Errori nella determinazione degli intervalli di definizione**:
   - Quando si risolvono disequazioni con valore assoluto, è fondamentale determinare correttamente gli intervalli in cui le espressioni all'interno del valore assoluto sono positive o negative.

8. **Confondere $|f(x)| = 0$ con $f(x) = 0$**:
   - L'equazione $|f(x)| = 0$ è equivalente a $f(x) = 0$ (questo è corretto)
   - Ma l'equazione $|f(x)| \neq 0$ non è equivalente a $f(x) \neq 0$ (sebbene siano logicamente equivalenti, la forma non è la stessa)