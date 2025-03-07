# Logaritmi ed Esponenziali

## 1. FUNZIONI ESPONENZIALI

### 1.1 Definizione di funzione esponenziale
La funzione esponenziale con base $a$ è definita come:

$$f(x) = a^x$$

dove $a > 0$, $a \neq 1$ e $x \in \mathbb{R}$.

**Caratteristiche principali**:
- Dominio: $\mathbb{R}$ (tutti i numeri reali)
- Codominio: $(0, +\infty)$ (tutti i numeri reali positivi)
- Se $a > 1$, la funzione è strettamente crescente
- Se $0 < a < 1$, la funzione è strettamente decrescente
- $a^0 = 1$ per qualsiasi valore di $a \neq 0$
- $a^1 = a$

**Esempi di funzioni esponenziali**:
- $f(x) = 2^x$ (crescente)
- $f(x) = 10^x$ (crescente)
- $f(x) = e^x$ (crescente), dove $e \approx 2.71828$ è il numero di Eulero
- $f(x) = (1/2)^x = 2^{-x}$ (decrescente)

### 1.2 Proprietà delle funzioni esponenziali
Per ogni $a > 0$ e per ogni $x, y \in \mathbb{R}$:

1. $a^{x+y} = a^x \cdot a^y$
2. $a^{x-y} = \frac{a^x}{a^y}$
3. $(a^x)^y = a^{xy}$
4. $(ab)^x = a^x \cdot b^x$
5. $\left(\frac{a}{b}\right)^x = \frac{a^x}{b^x}$
6. $a^{-x} = \frac{1}{a^x}$

**Esempio**: Semplificare $\frac{2^{x+3} \cdot 4^{x-1}}{8^x}$
$\frac{2^{x+3} \cdot 4^{x-1}}{8^x} = \frac{2^{x+3} \cdot (2^2)^{x-1}}{(2^3)^x} = \frac{2^{x+3} \cdot 2^{2(x-1)}}{2^{3x}} = \frac{2^{x+3} \cdot 2^{2x-2}}{2^{3x}} = \frac{2^{x+3+2x-2}}{2^{3x}} = \frac{2^{3x+1}}{2^{3x}} = 2^{3x+1-3x} = 2^1 = 2$

### 1.3 L'esponenziale naturale $e^x$
La funzione esponenziale $e^x$, dove $e \approx 2.71828$ è il numero di Eulero, ha un ruolo fondamentale in matematica:

- È la funzione tale che $\frac{d}{dx}(e^x) = e^x$ (ovvero è uguale alla sua derivata)
- Si definisce come $e = \lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n$
- Ha importanti applicazioni nella crescita e nel decadimento esponenziale

**Esempio**: Calcolare $e^0 + e^1$
$e^0 + e^1 = 1 + e \approx 1 + 2.71828 \approx 3.71828$

## 2. LOGARITMI

### 2.1 Definizione di logaritmo
Il logaritmo in base $a$ di un numero $x$, indicato con $\log_a(x)$, è l'esponente al quale la base $a$ deve essere elevata per ottenere $x$:

$$\log_a(x) = y \iff a^y = x$$

dove $a > 0$, $a \neq 1$, $x > 0$ e $y \in \mathbb{R}$.

**Caratteristiche principali**:
- Dominio: $(0, +\infty)$ (tutti i numeri reali positivi)
- Codominio: $\mathbb{R}$ (tutti i numeri reali)
- Se $a > 1$, la funzione è strettamente crescente
- Se $0 < a < 1$, la funzione è strettamente decrescente
- $\log_a(1) = 0$ per qualsiasi valore di $a$
- $\log_a(a) = 1$

**Esempi base**:
- $\log_{10}(100) = 2$ poiché $10^2 = 100$
- $\log_2(8) = 3$ poiché $2^3 = 8$
- $\log_3(1/3) = -1$ poiché $3^{-1} = 1/3$
- $\log_e(e) = 1$ poiché $e^1 = e$

### 2.2 Logaritmi particolari
- **Logaritmo naturale** (base $e$): $\ln(x) = \log_e(x)$
- **Logaritmo decimale** (base 10): $\log(x) = \log_{10}(x)$
- **Logaritmo binario** (base 2): $\log_2(x)$

### 2.3 Proprietà dei logaritmi
Per ogni $a > 0$, $a \neq 1$ e per ogni $x, y > 0$, $r \in \mathbb{R}$:

1. $\log_a(x \cdot y) = \log_a(x) + \log_a(y)$ (proprietà del prodotto)
2. $\log_a\left(\frac{x}{y}\right) = \log_a(x) - \log_a(y)$ (proprietà del quoziente)
3. $\log_a(x^r) = r \cdot \log_a(x)$ (proprietà della potenza)
4. $\log_a(a) = 1$
5. $\log_a(1) = 0$
6. $a^{\log_a(x)} = x$
7. $\log_a(a^x) = x$

**Esempio**: Semplificare $\log_3(27) - \log_3(9) + \log_3\left(\frac{1}{3}\right)$
$\log_3(27) - \log_3(9) + \log_3\left(\frac{1}{3}\right) = \log_3(3^3) - \log_3(3^2) + \log_3(3^{-1}) = 3 - 2 + (-1) = 0$

### 2.4 Formula di cambio base
Se abbiamo bisogno di calcolare $\log_a(x)$ ma conosciamo solo $\log_b(x)$ e $\log_b(a)$, possiamo usare la formula di cambio base:

$$\log_a(x) = \frac{\log_b(x)}{\log_b(a)}$$

Un caso particolare utile:

$$\log_a(x) = \frac{\ln(x)}{\ln(a)}$$

**Esempio**: Calcolare $\log_5(7)$ usando i logaritmi decimali
$\log_5(7) = \frac{\log(7)}{\log(5)} \approx \frac{0.8451}{0.6990} \approx 1.2089$

## 3. RELAZIONE TRA LOGARITMI ED ESPONENZIALI

### 3.1 Funzioni inverse
Le funzioni logaritmica ed esponenziale con la stessa base sono una l'inversa dell'altra:

- Se $f(x) = a^x$, allora $f^{-1}(x) = \log_a(x)$
- Se $f(x) = \log_a(x)$, allora $f^{-1}(x) = a^x$

Questo significa che:
- $\log_a(a^x) = x$ per ogni $x \in \mathbb{R}$
- $a^{\log_a(x)} = x$ per ogni $x > 0$

**Esempio**: Verificare che $2^{\log_2(5)} = 5$
$2^{\log_2(5)} = 5$ è vero per la proprietà dell'inversa.

### 3.2 Grafici delle funzioni
- Il grafico di $y = a^x$ passa per i punti $(0, 1)$ e $(1, a)$
- Il grafico di $y = \log_a(x)$ passa per i punti $(1, 0)$ e $(a, 1)$
- I grafici di $y = a^x$ e $y = \log_a(x)$ sono simmetrici rispetto alla retta $y = x$

## 4. EQUAZIONI ESPONENZIALI

### 4.1 Equazioni esponenziali elementari
Un'equazione esponenziale è un'equazione in cui l'incognita compare nell'esponente. Le principali strategie di risoluzione sono:

1. **Stessa base**: Se $a^{f(x)} = a^{g(x)}$ con $a > 0$ e $a \neq 1$, allora $f(x) = g(x)$
2. **Uso dei logaritmi**: Se $a^{f(x)} = b$ con $a, b > 0$ e $a \neq 1$, allora $f(x) = \log_a(b)$
3. **Sostituzione**: Introdurre una nuova variabile, es. $t = a^x$

**Esempio**: Risolvere $3^{x-1} = 9^{x+2}$
$3^{x-1} = 9^{x+2}$
$3^{x-1} = (3^2)^{x+2} = 3^{2(x+2)}$
$3^{x-1} = 3^{2x+4}$
$x-1 = 2x+4$ (stessa base)
$-1-4 = 2x-x$
$-5 = x$

**Esempio**: Risolvere $2^x = 5$
Applicando il logaritmo naturale a entrambi i membri:
$\ln(2^x) = \ln(5)$
$x \cdot \ln(2) = \ln(5)$
$x = \frac{\ln(5)}{\ln(2)} \approx 2.3219$

### 4.2 Equazioni esponenziali riconducibili a equazioni algebriche
Alcune equazioni esponenziali possono essere trasformate in equazioni algebriche mediante una sostituzione.

**Esempio**: Risolvere $4^x - 3 \cdot 2^x + 2 = 0$
Poniamo $t = 2^x$, quindi $4^x = (2^2)^x = 2^{2x} = (2^x)^2 = t^2$
L'equazione diventa: $t^2 - 3t + 2 = 0$
$(t-1)(t-2) = 0$
$t = 1$ o $t = 2$
Quindi $2^x = 1$ o $2^x = 2$
$x = 0$ o $x = 1$

**Esempio**: Risolvere $3^{2x} - 10 \cdot 3^x + 9 = 0$
Poniamo $t = 3^x$, quindi $3^{2x} = (3^x)^2 = t^2$
L'equazione diventa: $t^2 - 10t + 9 = 0$
$(t-1)(t-9) = 0$
$t = 1$ o $t = 9$
Quindi $3^x = 1$ o $3^x = 9$
$x = 0$ o $x = 2$

## 5. EQUAZIONI LOGARITMICHE

### 5.1 Equazioni logaritmiche elementari
Un'equazione logaritmica è un'equazione in cui compare un'incognita all'interno di un logaritmo. Per risolverla:

1. Verificare il dominio (le espressioni all'interno dei logaritmi devono essere positive)
2. Applicare le proprietà dei logaritmi per semplificare l'equazione
3. Trasformare l'equazione in forma esponenziale
4. Verificare le soluzioni

**Esempio**: Risolvere $\log_3(x) = 2$
Trasformiamo in forma esponenziale: $3^2 = x$
$x = 9$

Verifichiamo: $\log_3(9) = \log_3(3^2) = 2$ ✓

**Esempio**: Risolvere $\log_2(x+3) - \log_2(x-1) = 3$
Condizione di esistenza: $x+3 > 0$ e $x-1 > 0$, cioè $x > 1$

Applichiamo la proprietà del quoziente: $\log_2\left(\frac{x+3}{x-1}\right) = 3$

Trasformiamo in forma esponenziale: $\frac{x+3}{x-1} = 2^3 = 8$

$x+3 = 8(x-1)$
$x+3 = 8x-8$
$x-8x = -8-3$
$-7x = -11$
$x = \frac{11}{7}$

Verifichiamo: $\frac{11}{7} > 1$ ✓
$\log_2\left(\frac{\frac{11}{7}+3}{\frac{11}{7}-1}\right) = \log_2\left(\frac{\frac{11}{7}+\frac{21}{7}}{\frac{11}{7}-\frac{7}{7}}\right) = \log_2\left(\frac{\frac{32}{7}}{\frac{4}{7}}\right) = \log_2(8) = 3$ ✓

### 5.2 Equazioni con più logaritmi
Quando un'equazione contiene più logaritmi, è utile cercare di ricondursi a un'unica espressione logaritmica.

**Esempio**: Risolvere $\log(x) + \log(x-3) = 1$
Condizione di esistenza: $x > 0$ e $x-3 > 0$, cioè $x > 3$

Applichiamo la proprietà del prodotto: $\log(x(x-3)) = 1$

Trasformiamo in forma esponenziale: $x(x-3) = 10^1 = 10$

$x^2-3x = 10$
$x^2-3x-10 = 0$

Usando la formula quadratica:
$x = \frac{3 \pm \sqrt{9+40}}{2} = \frac{3 \pm \sqrt{49}}{2} = \frac{3 \pm 7}{2}$
$x = 5$ o $x = -2$

Poiché $x > 3$, l'unica soluzione accettabile è $x = 5$.

Verifichiamo: $\log(5) + \log(5-3) = \log(5) + \log(2) \approx 0.699 + 0.301 = 1$ ✓

## 6. DISEQUAZIONI ESPONENZIALI E LOGARITMICHE

### 6.1 Disequazioni esponenziali
Per risolvere disequazioni esponenziali, è fondamentale ricordare il comportamento monotono di queste funzioni:
- Se $a > 1$, allora $a^x$ è strettamente crescente
- Se $0 < a < 1$, allora $a^x$ è strettamente decrescente

**Esempio**: Risolvere $2^x < 8$
Poiché $2 > 1$, la funzione $2^x$ è crescente.
$2^x < 2^3$ (poiché $8 = 2^3$)
$x < 3$

**Esempio**: Risolvere $\left(\frac{1}{3}\right)^x \geq 9$
$\left(\frac{1}{3}\right)^x \geq 3^2$ (poiché $9 = 3^2$)
Poiché $\frac{1}{3} < 1$, la funzione $\left(\frac{1}{3}\right)^x$ è decrescente.
$x \leq -2$

### 6.2 Disequazioni logaritmiche
Per risolvere disequazioni logaritmiche, è necessario:
1. Determinare il dominio della funzione
2. Sfruttare la monotonia della funzione logaritmica
3. Trasformare la disequazione

**Esempio**: Risolvere $\log_2(x) < 3$
Dominio: $x > 0$
Poiché $2 > 1$, la funzione $\log_2(x)$ è crescente.
$\log_2(x) < 3$
$x < 2^3 = 8$
Quindi la soluzione è $x \in (0, 8)$

**Esempio**: Risolvere $\log_{1/2}(x) \geq 2$
Dominio: $x > 0$
Poiché $1/2 < 1$, la funzione $\log_{1/2}(x)$ è decrescente.
$\log_{1/2}(x) \geq 2$
$x \leq (1/2)^2 = 1/4$
Quindi la soluzione è $x \in (0, 1/4]$

### 6.3 Disequazioni miste
Quando compaiono sia logaritmi che esponenziali, spesso è utile usare le proprietà di invertibilità.

**Esempio**: Risolvere $\log_3(2x-1) > x$
Dominio: $2x-1 > 0 \Rightarrow x > 1/2$

Non c'è un metodo diretto, quindi studiamo la funzione $f(x) = \log_3(2x-1) - x$
Per $x = 1$: $f(1) = \log_3(1) - 1 = 0 - 1 = -1 < 0$
Per $x = 2$: $f(2) = \log_3(3) - 2 = 1 - 2 = -1 < 0$

Si può dimostrare che $f(x) < 0$ per ogni $x > 1/2$, quindi la disequazione non ha soluzioni.

## 7. APPLICAZIONI DEI LOGARITMI E DEGLI ESPONENZIALI

### 7.1 Scala logaritmica
In molte applicazioni scientifiche si usano scale logaritmiche per rappresentare grandezze che variano su molti ordini di grandezza.

**Esempi**:
- Scala Richter per i terremoti: ogni aumento di 1 unità corrisponde a un'energia 10 volte maggiore
- Scala dei decibel per l'intensità del suono
- pH in chimica: $pH = -\log_{10}[H^+]$

### 7.2 Crescita e decadimento esponenziale
Fenomeni di crescita o decadimento esponenziale sono descritti da equazioni del tipo:
$$N(t) = N_0 \cdot a^t$$

dove $N_0$ è il valore iniziale e $a$ è il fattore di crescita o decadimento.

**Esempio**: Un investimento di 1000€ cresce del 5% all'anno. Quanto varrà dopo 10 anni?
$N(10) = 1000 \cdot (1 + 0.05)^{10} = 1000 \cdot 1.05^{10} \approx 1000 \cdot 1.6289 \approx 1628.90€$

### 7.3 Tempo di raddoppio e di dimezzamento
- **Tempo di raddoppio**: il tempo necessario affinché una quantità raddoppi
- **Tempo di dimezzamento** (emivita): il tempo necessario affinché una quantità si dimezzi

**Formula per il tempo di raddoppio**:
Se $N(t) = N_0 \cdot a^t$, allora il tempo di raddoppio $T_2$ è dato da:
$$T_2 = \frac{\log(2)}{\log(a)}$$

**Esempio**: Calcolare il tempo di raddoppio di un investimento che cresce del 7% all'anno.
$T_2 = \frac{\log(2)}{\log(1.07)} \approx \frac{0.301}{0.0294} \approx 10.24 \text{ anni}$

## 8. ESERCIZI RISOLTI

1. **Esercizio**: Semplificare $\log_4(8) + \log_4(2) - \log_4(16)$
   **Soluzione**:
   $\log_4(8) + \log_4(2) - \log_4(16) = \log_4(8 \cdot 2) - \log_4(16) = \log_4(16) - \log_4(16) = 0$

2. **Esercizio**: Risolvere l'equazione $\log_2(x^2) = \log_4(x^3)$
   **Soluzione**:
   $\log_2(x^2) = \log_4(x^3)$
   $\log_2(x^2) = \log_{2^2}(x^3)$
   $\log_2(x^2) = \frac{\log_2(x^3)}{2}$ (formula cambio base)
   $\log_2(x^2) = \frac{3\log_2(x)}{2}$ (proprietà logaritmo di potenza)
   $2\log_2(x) = \frac{3\log_2(x)}{2}$ (proprietà logaritmo di potenza)
   $4\log_2(x) = 3\log_2(x)$
   $\log_2(x) = 0$
   $x = 1$
   
   Verifichiamo: $\log_2(1^2) = \log_2(1) = 0$ e $\log_4(1^3) = \log_4(1) = 0$ ✓

3. **Esercizio**: Risolvere l'equazione $3^{x+1} - 4 \cdot 3^x + 3 = 0$
   **Soluzione**:
   Poniamo $t = 3^x$, quindi $3^{x+1} = 3 \cdot 3^x = 3t$
   L'equazione diventa: $3t - 4t + 3 = 0$
   $-t + 3 = 0$
   $t = 3$
   Quindi $3^x = 3$
   $x = 1$
   
   Verifichiamo: $3^{1+1} - 4 \cdot 3^1 + 3 = 9 - 12 + 3 = 0$ ✓

4. **Esercizio**: Risolvere l'equazione $\log(x-1) + \log(x+2) = \log(6)$
   **Soluzione**:
   Condizione di esistenza: $x-1 > 0$ e $x+2 > 0$, cioè $x > 1$
   
   Applichiamo la proprietà del prodotto: $\log((x-1)(x+2)) = \log(6)$
   
   Quindi: $(x-1)(x+2) = 6$
   $x^2 + 2x - x - 2 = 6$
   $x^2 + x - 8 = 0$
   $(x+4)(x-2) = 0$
   $x = -4$ o $x = 2$
   
   Poiché $x > 1$, l'unica soluzione accettabile è $x = 2$.
   
   Verifichiamo: $\log(2-1) + \log(2+2) = \log(1) + \log(4) = 0 + \log(4) \approx 0.602$
   $\log(6) \approx 0.778$
   
   I valori non coincidono. Controlliamo i calcoli:
   $(x-1)(x+2) = (2-1)(2+2) = 1 \cdot 4 = 4 \neq 6$
   
   Risolviamo correttamente:
   $x^2 + x - 2 = 6$
   $x^2 + x - 8 = 0$
   $x = \frac{-1 \pm \sqrt{1+32}}{2} = \frac{-1 \pm \sqrt{33}}{2}$
   $x \approx 2.372$ o $x \approx -3.372$
   
   Poiché $x > 1$, l'unica soluzione accettabile è $x \approx 2.372$.
   
   Verifichiamo: $(2.372-1)(2.372+2) \approx 1.372 \cdot 4.372 \approx 6$ ✓

5. **Esercizio**: Risolvere la disequazione $\log_3(x+2) > \log_3(2x-4)$
   **Soluzione**:
   Condizioni di esistenza: $x+2 > 0$ e $2x-4 > 0$, cioè $x > -2$ e $x > 2$, quindi $x > 2$
   
   Poiché $3 > 1$, la funzione $\log_3$ è crescente. Quindi:
   $\log_3(x+2) > \log_3(2x-4)$ implica $x+2 > 2x-4$
   $6 > x$
   
   Combinando con il dominio: $2 < x < 6$

6. **Esercizio**: Risolvere l'equazione $\log_2(x) \cdot \log_4(x) = 2$
   **Soluzione**:
   Dominio: $x > 0$
   
   Usando la formula di cambio base: $\log_4(x) = \frac{\log_2(x)}{\log_2(4)} = \frac{\log_2(x)}{2}$
   
   L'equazione diventa: $\log_2(x) \cdot \frac{\log_2(x)}{2} = 2$
   $\frac{(\log_2(x))^2}{2} = 2$
   $(\log_2(x))^2 = 4$
   $\log_2(x) = 2$ o $\log_2(x) = -2$
   
   Risolvendo: $x = 2^2 = 4$ o $x = 2^{-2} = \frac{1}{4}$
   
   Verifichiamo: 
   Per $x = 4$: $\log_2(4) \cdot \log_4(4) = 2 \cdot 1 = 2$ ✓
   Per $x = \frac{1}{4}$: $\log_2(\frac{1}{4}) \cdot \log_4(\frac{1}{4}) = (-2) \cdot (-1) = 2$ ✓

7. **Esercizio**: Risolvere la disequazione $2^{2x} - 2^{x+2} + 2 \leq 0$
   **Soluzione**:
   Poniamo $t = 2^x$, quindi $2^{2x} = (2^x)^2 = t^2$
   
   La disequazione diventa: $t^2 - 4t + 2 \leq 0$ (poiché $2^{x+2} = 2^2 \cdot 2^x = 4t$)
   
   Il discriminante è $\Delta = 16 - 8 = 8$
   
   Le soluzioni dell'equazione associata sono:
   $t = \frac{4 \pm \sqrt{8}}{2} = 2 \pm \frac{2\sqrt{2}}{2} = 2 \pm \sqrt{2}$
   
   Quindi la disequazione è soddisfatta per $2-\sqrt{2} \leq t \leq 2+\sqrt{2}$
   
   Tornando alla variabile originale:
   $2-\sqrt{2} \leq 2^x \leq 2+\sqrt{2}$
   
   Applicando il logaritmo in base 2 (che è una funzione crescente):
   $\log_2(2-\sqrt{2}) \leq x \leq \log_2(2+\sqrt{2})$
   
   Numericamente: $\log_2(2-\sqrt{2}) \approx \log_2(0.5857) \approx -0.7715$ e $\log_2(2+\sqrt{2}) \approx \log_2(3.4142) \approx 1.7715$
   
   Quindi: $-0.7715 \lesssim x \lesssim 1.7715$

8. **Esercizio**: Risolvere l'equazione $\log_{x-1}(16) = 2$
   **Soluzione**:
   Per definizione: $(x-1)^2 = 16$
   $(x-1)^2 = 2^4$
   $x-1 = \pm 2^2 = \pm 4$
   $x = 5$ o $x = -3$
   
   Per $x = 5$: la base del logaritmo è $5-1 = 4 > 0$ e $4 \neq 1$ ✓
   Per $x = -3$: la base del logaritmo è $-3-1 = -4 < 0$ ✗
   
   L'unica soluzione accettabile è $x = 5$.
   
   Verifichiamo: $\log_{5-1}(16) = \log_4(16) = \log_4(4^2) = 2$ ✓

9. **Esercizio**: Risolvere l'equazione $\log_3(\log_2(x)) = 0$
   **Soluzione**:
   $\log_3(\log_2(x)) = 0$
   $\log_2(x) = 3^0 = 1$
   $x = 2^1 = 2$
   
   Verifichiamo: $\log_3(\log_2(2)) = \log_3(1) = 0$ ✓

10. **Esercizio**: Un capitale di 5000€ viene investito a un tasso di interesse annuo composto. Se dopo 3 anni il capitale è diventato 6050€, qual è il tasso di interesse?
    **Soluzione**:
    Usando la formula del capitale con interesse composto:
    $6050 = 5000 \cdot (1+r)^3$
    $\frac{6050}{5000} = (1+r)^3$
    $1.21 = (1+r)^3$
    
    Applicando la radice cubica:
    $\sqrt[3]{1.21} = 1+r$
    $1+r \approx 1.0656$
    $r \approx 0.0656 = 6.56\%$

11. **Esercizio Extra - La regola del 72**: In ambito finanziario, esiste una regola pratica detta "regola del 72" che permette di stimare rapidamente in quanti anni un capitale raddoppia, dato un certo tasso di interesse annuo composto. Secondo questa regola, il tempo di raddoppio $T_2$ è approssimativamente:
    $$T_2 \approx \frac{72}{r}$$
    dove $r$ è il tasso percentuale. Dimostrare che questa è una buona approssimazione e calcolarne l'errore per alcuni tassi di interesse comuni.
    
    **Soluzione**:
    Il tempo esatto di raddoppio per un tasso $r$ (espresso in percentuale) è:
    $$T_2 = \frac{\ln(2)}{\ln(1+\frac{r}{100})}$$
    
    Per piccoli valori di $r$, possiamo usare l'approssimazione $\ln(1+x) \approx x$ per $x$ vicino a zero:
    $$T_2 \approx \frac{\ln(2)}{\frac{r}{100}} = \frac{100 \cdot \ln(2)}{r} \approx \frac{69.3}{r}$$
    
    La regola del 72 arrotonda questo valore a $\frac{72}{r}$ per facilità di calcolo mentale.
    
    Errore per alcuni tassi comuni:
    - Per $r = 6\%$: $T_2$ esatto = 11.9 anni, regola del 72 = 12 anni, errore ≈ 0.8%
    - Per $r = 8\%$: $T_2$ esatto = 9.0 anni, regola del 72 = 9 anni, errore ≈ 0%
    - Per $r = 12\%$: $T_2$ esatto = 6.1 anni, regola del 72 = 6 anni, errore ≈ 1.6%

## 9. ERRORI COMUNI DA EVITARE

1. **Confondere le proprietà**:
   - Errore: $\log(a+b) = \log(a) + \log(b)$ ✗
   - Corretto: $\log(a \cdot b) = \log(a) + \log(b)$
   - Errore: $\log(a^b) = a^{\log(b)}$ ✗
   - Corretto: $\log(a^b) = b \cdot \log(a)$

2. **Dimenticare le condizioni di esistenza**:
   - Per $\log_a(x)$, deve essere $x > 0$, $a > 0$ e $a \neq 1$
   - Verificare sempre il dominio prima di procedere con la risoluzione

3. **Errori nelle disequazioni con logaritmi**:
   - Ricordare che se $a > 1$ e $\log_a(x) < \log_a(y)$, allora $x < y$
   - Se $0 < a < 1$ e $\log_a(x) < \log_a(y)$, allora $x > y$

4. **Applicazione errata del logaritmo alle disequazioni**:
   - Errore: se $a^x < b$, allora $x < \log_a(b)$ ✗ (non sempre vero!)
   - Corretto: se $a > 1$ e $a^x < b$, allora $x < \log_a(b)$
   - Se $0 < a < 1$ e $a^x < b$, allora $x > \log_a(b)$

5. **Calcoli errati con esponenti**:
   - Errore: $(a+b)^n = a^n + b^n$ ✗
   - Corretto: $(a+b)^n \neq a^n + b^n$ in generale

6. **Dimenticare di verificare le soluzioni**:
   - Le soluzioni di equazioni logaritmiche possono essere estranee
   - Verificare sempre nell'equazione originale

7. **Errori nel cambio base**:
   - Errore: $\log_a(x) = \log_b(x) \cdot \log_a(b)$ ✗
   - Corretto: $\log_a(x) = \frac{\log_b(x)}{\log_b(a)}$

8. **Linearizzazione errata delle equazioni esponenziali**:
   - Errore: risolvere $2^x = 3^x$ come $x \cdot \log(2) = x \cdot \log(3)$ ✗
   - Corretto: $2^x = 3^x$ implica $x \cdot \log(2) = x \cdot \log(3)$, quindi $x \cdot (\log(2) - \log(3)) = 0$, cioè $x = 0$ (poiché $\log(2) \neq \log(3)$)

9. **Confondere $\ln$ e $\log$**:
   - $\ln(x)$ è il logaritmo naturale (base $e$)
   - $\log(x)$ è generalmente il logaritmo in base 10
   - Usare la notazione appropriata

10. **Dimenticare che il logaritmo non è definito per numeri negativi o nulli**:
    - $\log_a(x)$ è definito solo per $x > 0$
    - Verificare sempre le condizioni di esistenza