# Potenze e Radici

## 1. POTENZE: DEFINIZIONI E CONCETTI BASE

### 1.1 Definizione di potenza
La potenza $a^n$ di base $a$ ed esponente intero positivo $n$ è definita come il prodotto della base $a$ ripetuta $n$ volte:

$$a^n = \underbrace{a \times a \times \cdots \times a}_{n \text{ volte}}$$

**Esempi**:
- $2^3 = 2 \times 2 \times 2 = 8$
- $5^2 = 5 \times 5 = 25$
- $10^4 = 10 \times 10 \times 10 \times 10 = 10000$

### 1.2 Estensione agli esponenti interi
- **Esponente 0**: Per $a \neq 0$, si definisce $a^0 = 1$
- **Esponenti negativi**: Per $a \neq 0$ e $n > 0$, si definisce $a^{-n} = \frac{1}{a^n}$

**Esempi**:
- $7^0 = 1$
- $2^{-3} = \frac{1}{2^3} = \frac{1}{8} = 0.125$
- $10^{-2} = \frac{1}{10^2} = \frac{1}{100} = 0.01$

### 1.3 Estensione agli esponenti razionali
Se $n$ è un intero positivo e $a > 0$, si definisce:
- $a^{1/n} = \sqrt[n]{a}$ (radice $n$-esima di $a$)
- $a^{m/n} = (a^{1/n})^m = (a^m)^{1/n} = \sqrt[n]{a^m} = (\sqrt[n]{a})^m$

**Esempi**:
- $4^{1/2} = \sqrt{4} = 2$
- $8^{2/3} = (8^{1/3})^2 = (\sqrt[3]{8})^2 = 2^2 = 4$
- $27^{-1/3} = \frac{1}{27^{1/3}} = \frac{1}{\sqrt[3]{27}} = \frac{1}{3}$

### 1.4 Estensione agli esponenti reali
L'estensione della definizione di potenza a esponenti reali richiede concetti di analisi matematica e si basa sul limite di successioni. Per il TOLC-I, è sufficiente comprendere e utilizzare potenze con esponenti razionali.

## 2. PROPRIETÀ DELLE POTENZE

### 2.1 Proprietà fondamentali
Per $a, b \neq 0$ e $m, n$ numeri reali:

1. $a^m \cdot a^n = a^{m+n}$ (prodotto di potenze con la stessa base)
2. $\frac{a^m}{a^n} = a^{m-n}$ (quoziente di potenze con la stessa base)
3. $(a^m)^n = a^{m \cdot n}$ (potenza di una potenza)
4. $(a \cdot b)^n = a^n \cdot b^n$ (potenza di un prodotto)
5. $\left(\frac{a}{b}\right)^n = \frac{a^n}{b^n}$ (potenza di un quoziente)
6. $a^{-n} = \frac{1}{a^n}$ (potenza con esponente negativo)
7. $a^0 = 1$ per $a \neq 0$ (potenza con esponente zero)

**Esempio**: Semplificare $\frac{x^5 \cdot x^3}{x^2}$
$\frac{x^5 \cdot x^3}{x^2} = \frac{x^{5+3}}{x^2} = \frac{x^8}{x^2} = x^{8-2} = x^6$

**Esempio**: Semplificare $(3^4)^2 \cdot 3^{-3}$
$(3^4)^2 \cdot 3^{-3} = 3^{4 \cdot 2} \cdot 3^{-3} = 3^8 \cdot 3^{-3} = 3^{8-3} = 3^5 = 243$

### 2.2 Notazione scientifica
Un numero in notazione scientifica è espresso come $a \times 10^n$ dove $1 \leq a < 10$ e $n$ è un numero intero.

**Esempi**:
- $3500 = 3.5 \times 10^3$
- $0.0042 = 4.2 \times 10^{-3}$
- $6.022 \times 10^{23}$ (numero di Avogadro)

**Operazioni in notazione scientifica**:
- $(3 \times 10^4) \times (2 \times 10^{-2}) = (3 \times 2) \times 10^{4 + (-2)} = 6 \times 10^2 = 600$
- $\frac{8 \times 10^5}{4 \times 10^3} = \frac{8}{4} \times 10^{5-3} = 2 \times 10^2 = 200$

## 3. RADICI: DEFINIZIONI E CONCETTI BASE

### 3.1 Definizione di radice
La radice $n$-esima di un numero $a$ è il numero $b$ tale che $b^n = a$.
Si indica con:
$$\sqrt[n]{a} = a^{1/n}$$

Per $n$ pari:
- Se $a > 0$, $\sqrt[n]{a}$ è l'unico numero positivo $b$ tale che $b^n = a$
- Se $a < 0$, $\sqrt[n]{a}$ non è definita in $\mathbb{R}$ (non esiste in campo reale)
- Se $a = 0$, $\sqrt[n]{a} = 0$

Per $n$ dispari:
- $\sqrt[n]{a}$ è l'unico numero reale $b$ tale che $b^n = a$

**Esempi**:
- $\sqrt{25} = 5$ perché $5^2 = 25$
- $\sqrt[3]{-8} = -2$ perché $(-2)^3 = -8$
- $\sqrt{-9}$ non è definita in $\mathbb{R}$ (è un numero complesso)

### 3.2 Proprietà delle radici
Per $a, b > 0$ e $n$ intero positivo:

1. $\sqrt[n]{a \cdot b} = \sqrt[n]{a} \cdot \sqrt[n]{b}$ (radice di un prodotto)
2. $\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{\sqrt[n]{b}}$ (radice di un quoziente)
3. $\sqrt[n]{a^m} = a^{m/n} = (\sqrt[n]{a})^m$ (radice di una potenza)
4. $\sqrt[m]{\sqrt[n]{a}} = \sqrt[m \cdot n]{a} = a^{1/(m \cdot n)}$ (radice di una radice)

**Esempio**: Semplificare $\sqrt[3]{8 \cdot 27}$
$\sqrt[3]{8 \cdot 27} = \sqrt[3]{8} \cdot \sqrt[3]{27} = 2 \cdot 3 = 6$

**Esempio**: Semplificare $\sqrt[4]{16} \cdot \sqrt{16}$
$\sqrt[4]{16} \cdot \sqrt{16} = 16^{1/4} \cdot 16^{1/2} = 16^{1/4 + 1/2} = 16^{3/4} = (2^4)^{3/4} = 2^{4 \cdot 3/4} = 2^3 = 8$

### 3.3 Razionalizzazione del denominatore
La razionalizzazione consiste nell'eliminare radici dal denominatore di una frazione, moltiplicando numeratore e denominatore per un'opportuna espressione.

**Per denominatori del tipo $\sqrt{a}$**:
$$\frac{b}{\sqrt{a}} = \frac{b \cdot \sqrt{a}}{a} = \frac{b \cdot \sqrt{a}}{a}$$

**Per denominatori del tipo $\sqrt{a} + \sqrt{b}$**:
$$\frac{c}{\sqrt{a} + \sqrt{b}} = \frac{c \cdot (\sqrt{a} - \sqrt{b})}{(\sqrt{a} + \sqrt{b})(\sqrt{a} - \sqrt{b})} = \frac{c \cdot (\sqrt{a} - \sqrt{b})}{a - b}$$

**Esempi**:
- $\frac{3}{\sqrt{5}} = \frac{3 \cdot \sqrt{5}}{5} = \frac{3\sqrt{5}}{5}$
- $\frac{2}{\sqrt{3} + \sqrt{2}} = \frac{2 \cdot (\sqrt{3} - \sqrt{2})}{(\sqrt{3} + \sqrt{2})(\sqrt{3} - \sqrt{2})} = \frac{2 \cdot (\sqrt{3} - \sqrt{2})}{3 - 2} = \frac{2\sqrt{3} - 2\sqrt{2}}{1} = 2\sqrt{3} - 2\sqrt{2}$

## 4. POTENZE CON ESPONENTI RAZIONALI

### 4.1 Relazione tra potenze ed esponenti razionali
Per $a > 0$ e $m, n$ interi con $n > 0$:
$$a^{m/n} = \sqrt[n]{a^m} = (\sqrt[n]{a})^m$$

**Esempi**:
- $4^{3/2} = \sqrt{4^3} = \sqrt{64} = 8$
- $8^{2/3} = (\sqrt[3]{8})^2 = 2^2 = 4$
- $16^{-1/4} = \frac{1}{16^{1/4}} = \frac{1}{\sqrt[4]{16}} = \frac{1}{2} = 0.5$

### 4.2 Semplificazione di espressioni con esponenti razionali
La chiave per semplificare espressioni con esponenti razionali è applicare le proprietà delle potenze.

**Esempio**: Semplificare $(27^{1/3} \cdot 9^{1/2})^2$
$(27^{1/3} \cdot 9^{1/2})^2 = (3 \cdot 3)^2 = 9^2 = 81$

**Esempio**: Semplificare $\frac{(x^{2/3} \cdot y^{1/2})^3}{x \cdot y^{3/4}}$
$\frac{(x^{2/3} \cdot y^{1/2})^3}{x \cdot y^{3/4}} = \frac{x^{2/3 \cdot 3} \cdot y^{1/2 \cdot 3}}{x \cdot y^{3/4}} = \frac{x^2 \cdot y^{3/2}}{x \cdot y^{3/4}} = \frac{x^{2-1} \cdot y^{3/2-3/4}}{1} = x \cdot y^{3/4} = x \cdot y^{0.75}$

## 5. EQUAZIONI E DISEQUAZIONI ESPONENZIALI

### 5.1 Equazioni esponenziali
Un'equazione esponenziale è un'equazione in cui l'incognita compare all'esponente. Le principali strategie di risoluzione sono:

1. **Stessa base**: se $a^f(x) = a^g(x)$ con $a > 0$ e $a \neq 1$, allora $f(x) = g(x)$
2. **Uso dei logaritmi**: se $a^{f(x)} = b$ con $a, b > 0$ e $a \neq 1$, allora $f(x) = \log_a b$
3. **Sostituzione**: introdurre una nuova variabile, es. $t = a^x$

**Esempio**: Risolvere $2^{x+1} = 8$
$2^{x+1} = 2^3$ (poiché $8 = 2^3$)
$x+1 = 3$ (stessa base)
$x = 2$

**Esempio**: Risolvere $3^x = 5$
Applicando il logaritmo in base 10 a entrambi i membri:
$\log(3^x) = \log(5)$
$x \cdot \log(3) = \log(5)$
$x = \frac{\log(5)}{\log(3)} \approx 1.465$

**Esempio**: Risolvere $4^x + 2 \cdot 2^x - 3 = 0$
Poniamo $t = 2^x$, allora $4^x = (2^2)^x = 2^{2x} = (2^x)^2 = t^2$
L'equazione diventa: $t^2 + 2t - 3 = 0$
$(t+3)(t-1) = 0$
$t = -3$ o $t = 1$
Poiché $t = 2^x > 0$ per ogni $x$ reale, $t = -3$ non è accettabile.
Quindi $t = 1$, cioè $2^x = 1$, da cui $x = 0$

### 5.2 Disequazioni esponenziali
La risoluzione di disequazioni esponenziali sfrutta la monotonia delle funzioni esponenziali:
- Se $a > 1$, la funzione $f(x) = a^x$ è strettamente crescente
- Se $0 < a < 1$, la funzione $f(x) = a^x$ è strettamente decrescente

**Esempio**: Risolvere $2^x > 8$
$2^x > 2^3$ (poiché $8 = 2^3$)
Poiché $2 > 1$, la funzione $2^x$ è crescente, quindi: $x > 3$

**Esempio**: Risolvere $\left(\frac{1}{3}\right)^x \leq 9$
$\left(\frac{1}{3}\right)^x \leq 3^2$ (poiché $9 = 3^2$)
Poiché $\frac{1}{3} < 1$, la funzione $\left(\frac{1}{3}\right)^x$ è decrescente, quindi: $x \geq -2$

## 6. RADICI ED EQUAZIONI IRRAZIONALI

### 6.1 Equazioni irrazionali
Un'equazione irrazionale è un'equazione in cui l'incognita appare sotto il segno di radice. Per risolverla:

1. Isolare la radice
2. Elevare entrambi i membri all'esponente appropriato
3. Verificare le soluzioni (potenziali soluzioni spurie)

**Esempio**: Risolvere $\sqrt{x+3} = x-1$
Eleviamo al quadrato entrambi i membri: $(x+3) = (x-1)^2$
$x+3 = x^2-2x+1$
$0 = x^2-3x-2$
$(x-2)(x+1) = 0$
$x = 2$ o $x = -1$

Verifichiamo:
- Per $x = 2$: $\sqrt{2+3} = 2-1$ ⟹ $\sqrt{5} = 1$ (falso)
- Per $x = -1$: $\sqrt{-1+3} = -1-1$ ⟹ $\sqrt{2} = -2$ (falso)

Non ci sono soluzioni valide.

**Esempio**: Risolvere $\sqrt{2x+1} - \sqrt{x-2} = 3$
Isoliamo una radice: $\sqrt{2x+1} = 3 + \sqrt{x-2}$
Eleviamo al quadrato: $2x+1 = 9 + 6\sqrt{x-2} + (x-2)$
$2x+1 = 9 + 6\sqrt{x-2} + x-2$
$x+1 = 7 + 6\sqrt{x-2}$
$x-6 = 6\sqrt{x-2}$
Eleviamo nuovamente al quadrato: $(x-6)^2 = 36(x-2)$
$x^2-12x+36 = 36x-72$
$x^2-48x+108 = 0$
$x^2-48x+108 = 0$
$x = \frac{48 \pm \sqrt{48^2-4 \cdot 1 \cdot 108}}{2 \cdot 1} = \frac{48 \pm \sqrt{2304-432}}{2} = \frac{48 \pm \sqrt{1872}}{2}$
$x = \frac{48 \pm 2\sqrt{468}}{2} = 24 \pm \sqrt{468} \approx 24 \pm 21.63$
$x \approx 45.63$ o $x \approx 2.37$

Verifichiamo le soluzioni (calcolo omesso per brevità). Solo $x \approx 45.63$ soddisfa l'equazione originale.

### 6.2 Condizioni di esistenza
Quando si opera con radici, è fondamentale verificare le condizioni di esistenza:
- Per radici di indice pari: il radicando deve essere non negativo
- Per radici in generale: se il radicando è una frazione, il denominatore non può essere zero

**Esempio**: Determinare il dominio di $f(x) = \sqrt{x^2-9}$
Condizione: $x^2-9 \geq 0$
$x^2 \geq 9$
$x \leq -3$ o $x \geq 3$
Dominio: $(-\infty, -3] \cup [3, +\infty)$

## 7. ESERCIZI RISOLTI

1. **Esercizio**: Semplificare $\frac{6^{2/3} \cdot 9^{1/2}}{3^{5/3}}$
   **Soluzione**:
   $\frac{6^{2/3} \cdot 9^{1/2}}{3^{5/3}} = \frac{(2 \cdot 3)^{2/3} \cdot (3^2)^{1/2}}{3^{5/3}} = \frac{2^{2/3} \cdot 3^{2/3} \cdot 3}{3^{5/3}} = \frac{2^{2/3} \cdot 3^{2/3} \cdot 3}{3^{5/3}} = \frac{2^{2/3} \cdot 3^{2/3 + 1}}{3^{5/3}} = \frac{2^{2/3} \cdot 3^{5/3}}{3^{5/3}} = 2^{2/3} = \sqrt[3]{2^2} = \sqrt[3]{4} \approx 1.587$

2. **Esercizio**: Calcolare il valore di $\sqrt[3]{-27} \cdot \sqrt[6]{729}$
   **Soluzione**:
   $\sqrt[3]{-27} \cdot \sqrt[6]{729} = -3 \cdot \sqrt[6]{3^6} = -3 \cdot 3 = -9$

3. **Esercizio**: Razionalizzare il denominatore di $\frac{4}{\sqrt{5} - 2}$
   **Soluzione**:
   $\frac{4}{\sqrt{5} - 2} = \frac{4 \cdot (\sqrt{5} + 2)}{(\sqrt{5} - 2)(\sqrt{5} + 2)} = \frac{4 \cdot (\sqrt{5} + 2)}{5 - 4} = \frac{4 \cdot (\sqrt{5} + 2)}{1} = 4\sqrt{5} + 8$

4. **Esercizio**: Risolvere l'equazione $\sqrt{x+5} + \sqrt{x-3} = 4$
   **Soluzione**:
   Eleviamo al quadrato entrambi i membri dopo aver isolato una radice:
   $\sqrt{x+5} = 4 - \sqrt{x-3}$
   $(\sqrt{x+5})^2 = (4 - \sqrt{x-3})^2$
   $x+5 = 16 - 8\sqrt{x-3} + (x-3)$
   $x+5 = 16 + x - 3 - 8\sqrt{x-3}$
   $5 = 13 - 8\sqrt{x-3}$
   $-8 = -8\sqrt{x-3}$
   $1 = \sqrt{x-3}$
   $1^2 = (\sqrt{x-3})^2$
   $1 = x-3$
   $x = 4$
   
   Verifichiamo:
   Per $x = 4$: $\sqrt{4+5} + \sqrt{4-3} = \sqrt{9} + \sqrt{1} = 3 + 1 = 4$ ✓
   
   L'unica soluzione è $x = 4$.

5. **Esercizio**: Risolvere la disequazione $3^{2x} - 2 \cdot 3^x + 1 > 0$
   **Soluzione**:
   Poniamo $t = 3^x$, la disequazione diventa:
   $t^2 - 2t + 1 > 0$
   $(t-1)^2 > 0$
   
   Poiché un quadrato è sempre non negativo e $(t-1)^2 = 0$ solo per $t = 1$, abbiamo:
   $(t-1)^2 > 0$ per ogni $t \neq 1$
   
   Quindi $3^x \neq 1$, cioè $x \neq 0$ (poiché $3^0 = 1$)
   
   La soluzione è $x \in (-\infty, 0) \cup (0, +\infty)$, cioè $x \neq 0$.

6. **Esercizio**: Risolvere l'equazione $2^{x+1} + 2^{x-1} = 5$
   **Soluzione**:
   $2^{x+1} + 2^{x-1} = 5$
   $2 \cdot 2^x + \frac{1}{2} \cdot 2^x = 5$
   $2^x \cdot (2 + \frac{1}{2}) = 5$
   $2^x \cdot \frac{5}{2} = 5$
   $2^x = 2$
   $x = 1$
   
   Verifichiamo:
   Per $x = 1$: $2^{1+1} + 2^{1-1} = 2^2 + 2^0 = 4 + 1 = 5$ ✓
   
   L'unica soluzione è $x = 1$.

7. **Esercizio**: Risolvere l'equazione $\sqrt[3]{x^2} = \sqrt{x}$
   **Soluzione**:
   $x^{2/3} = x^{1/2}$
   
   Per $x > 0$ (condizione necessaria per l'esistenza della radice quadrata):
   $2/3 = 1/2$, che è falso.
   
   Per $x = 0$:
   $\sqrt[3]{0^2} = \sqrt{0}$
   $0 = 0$, che è vero.
   
   Per $x < 0$:
   $\sqrt[3]{x^2} = \sqrt{x}$ non ha senso poiché $\sqrt{x}$ non è definita per $x < 0$.
   
   L'unica soluzione è $x = 0$.

8. **Esercizio**: Trovare il valore di $x$ che soddisfa $\log_3(x^2 - 7x + 12) = 0$
   **Soluzione**:
   $\log_3(x^2 - 7x + 12) = 0$
   $x^2 - 7x + 12 = 3^0 = 1$
   $x^2 - 7x + 11 = 0$
   
   Usando la formula risolutiva:
   $x = \frac{7 \pm \sqrt{49-44}}{2} = \frac{7 \pm \sqrt{5}}{2}$
   
   Verifichiamo che il logaritmo sia definito, cioè che $x^2 - 7x + 12 > 0$:
   Per $x = \frac{7 + \sqrt{5}}{2} \approx 4.618$:
   $(4.618)^2 - 7(4.618) + 12 \approx 21.33 - 32.33 + 12 = 1$ ✓
   
   Per $x = \frac{7 - \sqrt{5}}{2} \approx 2.382$:
   $(2.382)^2 - 7(2.382) + 12 \approx 5.67 - 16.67 + 12 = 1$ ✓
   
   Entrambi i valori sono accettabili: $x = \frac{7 + \sqrt{5}}{2}$ o $x = \frac{7 - \sqrt{5}}{2}$

9. **Esercizio**: Calcolare il valore dell'espressione $\sqrt{12 + 2\sqrt{35}} + \sqrt{12 - 2\sqrt{35}}$
   **Soluzione**:
   Osserviamo che:
   $(\sqrt{12 + 2\sqrt{35}} + \sqrt{12 - 2\sqrt{35}})^2 = (12 + 2\sqrt{35}) + (12 - 2\sqrt{35}) + 2\sqrt{(12 + 2\sqrt{35})(12 - 2\sqrt{35})}$
   $= 24 + 2\sqrt{144 - 4 \cdot 35}$
   $= 24 + 2\sqrt{144 - 140}$
   $= 24 + 2\sqrt{4}$
   $= 24 + 2 \cdot 2$
   $= 24 + 4$
   $= 28$
   
   Quindi $\sqrt{12 + 2\sqrt{35}} + \sqrt{12 - 2\sqrt{35}} = \sqrt{28} = 2\sqrt{7}$

10. **Esercizio**: Risolvere la disequazione $\frac{\sqrt{x+1}}{x-3} \leq 0$
    **Soluzione**:
    Affinché il rapporto sia non positivo, è necessario che:
    - numeratore $\geq 0$ e denominatore $< 0$, oppure
    - numeratore $\leq 0$ e denominatore $> 0$
    
    Poiché $\sqrt{x+1} \geq 0$ per ogni $x \geq -1$ (e non è definita per $x < -1$), l'unica possibilità è:
    - numeratore $> 0$ e denominatore $< 0$
    
    Quindi:
    $\sqrt{x+1} > 0$ implica $x > -1$
    $x-3 < 0$ implica $x < 3$
    
    Inoltre, il denominatore non può essere nullo, quindi $x \neq 3$.
    
    Combinando le condizioni: $-1 < x < 3$
    
    La soluzione è $x \in (-1, 3)$.

## 8. ERRORI COMUNI DA EVITARE

1. **Confondere le regole di potenze e radici**:
   - Errore: $(a + b)^n = a^n + b^n$ ✗ (non è vero in generale!)
   - Corretto: solo $(a \cdot b)^n = a^n \cdot b^n$ e $(a/b)^n = a^n/b^n$

2. **Distribuzione errata della potenza su somme e differenze**:
   - Errore: $(a + b)^2 = a^2 + b^2$ ✗
   - Corretto: $(a + b)^2 = a^2 + 2ab + b^2$
   - Errore: $(a - b)^2 = a^2 - b^2$ ✗
   - Corretto: $(a - b)^2 = a^2 - 2ab + b^2$

3. **Trattare radici negative con indice pari**:
   - Errore: $\sqrt{-4} = -2$ ✗
   - Corretto: $\sqrt{-4}$ non è definita in $\mathbb{R}$

4. **Linearizzare erroneamente le radici**:
   - Errore: $\sqrt{a + b} = \sqrt{a} + \sqrt{b}$ ✗
   - Corretto: in generale, $\sqrt{a + b} \neq \sqrt{a} + \sqrt{b}$

5. **Applicare scorrettamente le proprietà esponenziali**:
   - Errore: $(a^m)^n = a^{m+n}$ ✗
   - Corretto: $(a^m)^n = a^{m \cdot n}$

6. **Dimenticare le condizioni di esistenza**:
   - Per $\sqrt[n]{x}$ con $n$ pari, deve essere $x \geq 0$
   - Per $\log_a(x)$, deve essere $x > 0$ e $a > 0$, $a \neq 1$

7. **Non verificare le soluzioni di equazioni irrazionali**:
   - Elevare al quadrato può introdurre soluzioni estranee che non soddisfano l'equazione originale
   - Le soluzioni devono sempre essere verificate nell'equazione originale

8. **Confondere le proprietà di monotonia nelle disequazioni esponenziali**:
   - Se $a > 1$ e $a^x < a^y$, allora $x < y$ (funzione crescente)
   - Se $0 < a < 1$ e $a^x < a^y$, allora $x > y$ (funzione decrescente)

9. **Errori nei calcoli con esponenti negativi e frazionari**:
   - Errore: $3^{-2} = -9$ ✗
   - Corretto: $3^{-2} = \frac{1}{3^2} = \frac{1}{9}$

10. **Dimenticare che $0^0$ è indeterminato**:
    - $0^0$ è generalmente considerato indeterminato nella teoria, ma in molti contesti pratici si adotta la convenzione $0^0 = 1$