# Proprietà e operazioni sui numeri (interi, razionali, reali)

## 1. INSIEMI NUMERICI

### 1.1 Numeri Naturali ($\mathbb{N}$)
- **Definizione**: $\mathbb{N} = \{0, 1, 2, 3, ...\}$ (includo lo zero come è convenzione in matematica moderna)
- **Operazioni possibili**: addizione, moltiplicazione
- **Proprietà dell'addizione**:
  - Commutativa: $a + b = b + a$
  - Associativa: $(a + b) + c = a + (b + c)$
  - Elemento neutro: $a + 0 = a$
- **Proprietà della moltiplicazione**:
  - Commutativa: $a \times b = b \times a$
  - Associativa: $(a \times b) \times c = a \times (b \times c)$
  - Elemento neutro: $a \times 1 = a$
  - Distributiva rispetto all'addizione: $a \times (b + c) = a \times b + a \times c$
- **Limitazioni**: non sempre è possibile la sottrazione (es. $3-5$) o la divisione

**Esempio**: Verificare la proprietà distributiva con $a=2$, $b=3$, $c=4$
$2 \times (3 + 4) = 2 \times 7 = 14$
$2 \times 3 + 2 \times 4 = 6 + 8 = 14$

### 1.2 Numeri Interi ($\mathbb{Z}$)
- **Definizione**: $\mathbb{Z} = \{..., -3, -2, -1, 0, 1, 2, 3, ...\}$
- **Operazioni possibili**: addizione, sottrazione, moltiplicazione
- **Proprietà aggiuntive**:
  - Opposto: Per ogni $a$ esiste $-a$ tale che $a + (-a) = 0$
  - Valore assoluto: $|a| = a$ se $a \geq 0$, $|a| = -a$ se $a < 0$
- **Regole dei segni**:
  - $(+a) + (+b) = +(a + b)$
  - $(+a) + (-b) = +(a - b)$ se $a > b$
  - $(+a) + (-b) = -(b - a)$ se $a < b$
  - $(-a) + (-b) = -(a + b)$
  - $(+a) \times (+b) = +(a \times b)$
  - $(+a) \times (-b) = -(a \times b)$
  - $(-a) \times (+b) = -(a \times b)$
  - $(-a) \times (-b) = +(a \times b)$
- **Limitazioni**: non sempre è possibile la divisione (es. $5 \div 2$)

**Esempio**: Calcolare $(-5) \times (-3) + (-4) \times (2)$
$(-5) \times (-3) + (-4) \times (2) = 15 + (-8) = 7$

### 1.3 Numeri Razionali ($\mathbb{Q}$)
- **Definizione**: $\mathbb{Q} = \{\frac{a}{b} | a, b \in \mathbb{Z}, b \neq 0\}$
- **Rappresentazione**: frazione $\frac{a}{b}$ o decimale (finito o periodico)
- **Operazioni possibili**: addizione, sottrazione, moltiplicazione, divisione (tranne per 0)
- **Operazioni con frazioni**:
  - Addizione: $\frac{a}{b} + \frac{c}{d} = \frac{a \times d + b \times c}{b \times d}$
  - Sottrazione: $\frac{a}{b} - \frac{c}{d} = \frac{a \times d - b \times c}{b \times d}$
  - Moltiplicazione: $\frac{a}{b} \times \frac{c}{d} = \frac{a \times c}{b \times d}$
  - Divisione: $\frac{a}{b} \div \frac{c}{d} = \frac{a \times d}{b \times c}$, con $c \neq 0$
- **Proprietà di densità**: tra due numeri razionali esiste sempre un altro numero razionale (ad esempio, la loro media aritmetica)

**Esempio**: Calcolare $\frac{2}{3} + \frac{5}{4}$
$\frac{2}{3} + \frac{5}{4} = \frac{2 \times 4 + 3 \times 5}{3 \times 4} = \frac{8 + 15}{12} = \frac{23}{12}$

**Esempio**: Trovare un numero razionale tra $\frac{3}{5}$ e $\frac{2}{3}$
La media aritmetica: $\frac{\frac{3}{5} + \frac{2}{3}}{2} = \frac{\frac{9}{15} + \frac{10}{15}}{2} = \frac{\frac{19}{15}}{2} = \frac{19}{30}$

### 1.4 Numeri Irrazionali
- **Definizione**: numeri decimali illimitati non periodici
- **Esempi**: $\sqrt{2}$, $\pi$, $e$
- **Caratteristiche**: non esprimibili come rapporto di numeri interi
- **Approssimazioni**:
  - $\sqrt{2} \approx 1.414213562...$
  - $\pi \approx 3.141592653...$
  - $e \approx 2.718281828...$

**Esempio**: Dimostrare che $\sqrt{2}$ è irrazionale
Dimostrazione per assurdo: Supponiamo che $\sqrt{2} = \frac{p}{q}$ dove $p$ e $q$ sono interi primi tra loro.
Allora $2 = \frac{p^2}{q^2}$, quindi $p^2 = 2q^2$.
Quindi $p^2$ è pari, il che implica che $p$ è pari.
Se $p$ è pari, allora $p = 2k$ per qualche intero $k$.
Sostituendo: $4k^2 = 2q^2$, quindi $q^2 = 2k^2$.
Quindi $q^2$ è pari, il che implica che $q$ è pari.
Ma se sia $p$ che $q$ sono pari, non sono primi tra loro.
Questa è una contraddizione, quindi $\sqrt{2}$ non può essere razionale.

### 1.5 Numeri Reali ($\mathbb{R}$)
- **Definizione**: unione di numeri razionali e irrazionali: $\mathbb{R} = \mathbb{Q} \cup \mathbb{I}$
- **Proprietà di completezza**: ogni punto sulla retta corrisponde a un numero reale
- **Intervalli**:
  - Chiuso: $[a, b] = \{x \in \mathbb{R} | a \leq x \leq b\}$
  - Aperto: $(a, b) = \{x \in \mathbb{R} | a < x < b\}$
  - Semiaperti: $[a, b) = \{x \in \mathbb{R} | a \leq x < b\}$ o $(a, b] = \{x \in \mathbb{R} | a < x \leq b\}$
  - Illimitati: $[a, +\infty) = \{x \in \mathbb{R} | x \geq a\}$ o $(-\infty, b] = \{x \in \mathbb{R} | x \leq b\}$

**Esempio**: Rappresentare in forma di intervallo l'insieme $\{x \in \mathbb{R} | -1 < x \leq 4\}$
La risposta è: $(-1, 4]$

## 2. PROPRIETÀ FONDAMENTALI

### 2.1 Divisibilità (numeri interi)
- **Definizione**: $a$ è divisibile per $b$ se esiste $k \in \mathbb{Z}$ tale che $a = b \times k$
- **Notazione**: $b|a$ (si legge "$b$ divide $a$")
- **Divisori e multipli**: se $a$ divide $b$, allora $a$ è un divisore di $b$ e $b$ è un multiplo di $a$
- **Criteri di divisibilità**:
  - Per 2: l'ultima cifra è pari (0, 2, 4, 6, 8)
  - Per 3: la somma delle cifre è divisibile per 3
  - Per 4: le ultime due cifre formano un numero divisibile per 4
  - Per 5: l'ultima cifra è 0 o 5
  - Per 6: il numero è divisibile sia per 2 che per 3
  - Per 8: le ultime tre cifre formano un numero divisibile per 8
  - Per 9: la somma delle cifre è divisibile per 9
  - Per 10: l'ultima cifra è 0
  - Per 11: la differenza tra la somma delle cifre in posizione pari e la somma delle cifre in posizione dispari è divisibile per 11 (o uguale a 0)

**Esempio**: Verificare se 2346 è divisibile per 9
Somma delle cifre: $2 + 3 + 4 + 6 = 15$
$15$ è divisibile per 3 ma non per 9, quindi 2346 non è divisibile per 9.

**Esempio**: Verificare se 2541 è divisibile per 3
Somma delle cifre: $2 + 5 + 4 + 1 = 12$
$12$ è divisibile per 3, quindi 2541 è divisibile per 3.

### 2.2 Numeri primi
- **Definizione**: numeri naturali $> 1$ divisibili solo per 1 e per sé stessi
- **Primi 10 numeri primi**: 2, 3, 5, 7, 11, 13, 17, 19, 23, 29
- **Teorema fondamentale dell'aritmetica**: ogni numero naturale $> 1$ può essere scritto come prodotto di numeri primi in modo unico (a meno dell'ordine dei fattori)

**Esempio**: Scomporre in fattori primi il numero 84
$84 = 2 \times 42 = 2 \times 2 \times 21 = 2^2 \times 3 \times 7$

**Esempio**: Scomporre in fattori primi il numero 495
$495 = 5 \times 99 = 5 \times 3 \times 33 = 5 \times 3 \times 3 \times 11 = 5 \times 3^2 \times 11$

### 2.3 MCD e mcm
- **Massimo Comun Divisore (MCD)**: il più grande divisore comune tra due o più numeri
  - Metodo: scomposizione in fattori primi, prodotto dei fattori comuni con il minimo esponente
- **minimo comune multiplo (mcm)**: il più piccolo multiplo comune tra due o più numeri
  - Metodo: scomposizione in fattori primi, prodotto dei fattori comuni e non comuni con il massimo esponente
- **Relazione**: $\text{MCD}(a,b) \times \text{mcm}(a,b) = a \times b$

**Esempio**: Calcolare MCD e mcm di 36 e 48
Scomposizione in fattori primi:
$36 = 2^2 \times 3^2$
$48 = 2^4 \times 3$

MCD: prodotto dei fattori comuni con il minimo esponente: $2^2 \times 3^1 = 4 \times 3 = 12$
mcm: prodotto dei fattori comuni e non comuni con il massimo esponente: $2^4 \times 3^2 = 16 \times 9 = 144$

Verifica: $\text{MCD} \times \text{mcm} = 12 \times 144 = 1728 = 36 \times 48$

**Esempio**: Calcolare MCD e mcm di 45, 60 e 75
Scomposizione in fattori primi:
$45 = 3^2 \times 5$
$60 = 2^2 \times 3 \times 5$
$75 = 3 \times 5^2$

MCD: $3^1 \times 5^1 = 15$
mcm: $2^2 \times 3^2 \times 5^2 = 4 \times 9 \times 25 = 900$

### 2.4 Frazioni e numeri decimali
- **Frazione propria**: $|\frac{a}{b}| < 1$
- **Frazione impropria**: $|\frac{a}{b}| \geq 1$
- **Frazione apparente**: equivalente a un numero intero (es. $\frac{4}{2} = 2$)
- **Frazioni equivalenti**: $\frac{a}{b} = \frac{c}{d}$ se $a \times d = b \times c$
- **Conversione in decimale**: dividere numeratore per denominatore
- **Tipi di numeri decimali**:
  - Limitato: termina dopo un numero finito di cifre (es. $\frac{3}{8} = 0.375$)
  - Illimitato periodico: cifre che si ripetono all'infinito (es. $\frac{1}{3} = 0.333...$)
  - Illimitato non periodico: cifre che non seguono uno schema ripetitivo (es. $\sqrt{2} = 1.414213562...$)

**Esempio**: Convertire $\frac{5}{6}$ in numero decimale
$\frac{5}{6} = 0.8333... = 0.\overline{83}$

**Esempio**: Convertire $2.35\overline{7}$ in frazione
$2.35\overline{7} = 2 + 0.35\overline{7}$
$10 \times 0.35\overline{7} = 3.5\overline{7}$
$100 \times 0.35\overline{7} = 35.\overline{7}$
$35.\overline{7} - 3.5\overline{7} = 32.2$
$99 \times 0.35\overline{7} = 32.2$
$0.35\overline{7} = \frac{32.2}{99} = \frac{322}{990} = \frac{161}{495}$
$2.35\overline{7} = 2 + \frac{161}{495} = \frac{990}{495} + \frac{161}{495} = \frac{1151}{495}$

## 3. OPERAZIONI E PROPRIETÀ AVANZATE

### 3.1 Potenze
- **Definizione**: $a^n = \underbrace{a \times a \times ... \times a}_{n \text{ volte}}$
- **Proprietà**:
  - $a^m \times a^n = a^{m+n}$
  - $a^m \div a^n = a^{m-n}$
  - $(a^m)^n = a^{m \times n}$
  - $(a \times b)^n = a^n \times b^n$
  - $(a \div b)^n = a^n \div b^n$
  - $a^0 = 1$ (per $a \neq 0$)
  - $a^{-n} = \frac{1}{a^n}$
- **Potenze con base 10**: $10^n$ = 1 seguito da $n$ zeri

**Esempio**: Semplificare $\frac{2^5 \times 3^2}{2^3 \times 3^4}$
$\frac{2^5 \times 3^2}{2^3 \times 3^4} = \frac{2^{5-3} \times 3^{2-4}}{1} = 2^2 \times 3^{-2} = 4 \times \frac{1}{9} = \frac{4}{9}$

**Esempio**: Calcolare $(2^3)^2 \times \frac{3^4}{3^2}$
$(2^3)^2 \times \frac{3^4}{3^2} = 2^{3 \times 2} \times 3^{4-2} = 2^6 \times 3^2 = 64 \times 9 = 576$

### 3.2 Radici
- **Definizione**: $\sqrt[n]{a} = a^{1/n}$
- **Proprietà**:
  - $\sqrt[n]{a \times b} = \sqrt[n]{a} \times \sqrt[n]{b}$
  - $\sqrt[n]{\frac{a}{b}} = \frac{\sqrt[n]{a}}{\sqrt[n]{b}}$
  - $\sqrt[n]{a^m} = a^{m/n}$
  - $(\sqrt[n]{a})^m = a^{m/n}$
  - $\sqrt[m]{\sqrt[n]{a}} = \sqrt[m \times n]{a}$
- **Razionalizzazione del denominatore**: $\frac{a}{\sqrt{b}} = \frac{a \times \sqrt{b}}{b}$

**Esempio**: Semplificare $\sqrt{8} \times \sqrt{2}$
$\sqrt{8} \times \sqrt{2} = \sqrt{8 \times 2} = \sqrt{16} = 4$

**Esempio**: Razionalizzare $\frac{3}{\sqrt{5}}$
$\frac{3}{\sqrt{5}} = \frac{3 \times \sqrt{5}}{5} = \frac{3\sqrt{5}}{5}$

### 3.3 Proporzioni e percentuali
- **Proporzione**: $a : b = c : d$ (o $\frac{a}{b} = \frac{c}{d}$)
- **Proprietà fondamentale**: $a \times d = b \times c$
- **Altre proprietà**:
  - $a : b = c : d \Rightarrow a : c = b : d$ (invertendo i medi)
  - $a : b = c : d \Rightarrow (a+b) : b = (c+d) : d$ (componendo)
  - $a : b = c : d \Rightarrow (a-b) : b = (c-d) : d$ (dividendo)
- **Percentuale**: $x\% = \frac{x}{100}$
- **Calcolo della percentuale**: $(x\% \text{ di } y) = \frac{x \times y}{100}$
- **Variazione percentuale**: $\left[\frac{\text{valore finale} - \text{valore iniziale}}{\text{valore iniziale}}\right] \times 100$

**Esempio**: Se $a : b = 3 : 4$ e $b : c = 2 : 3$, trovare $a : c$
$a : b = 3 : 4 \Rightarrow \frac{a}{b} = \frac{3}{4}$
$b : c = 2 : 3 \Rightarrow \frac{b}{c} = \frac{2}{3}$
$\frac{a}{c} = \frac{a}{b} \times \frac{b}{c} = \frac{3}{4} \times \frac{2}{3} = \frac{6}{12} = \frac{1}{2}$
Quindi $a : c = 1 : 2$

**Esempio**: Un prodotto costa 120€ e viene scontato del 15%. Viene poi applicato un ulteriore sconto del 10% sul prezzo scontato. Qual è il prezzo finale?
Primo sconto: $120 - 15\% \text{ di } 120 = 120 - 18 = 102€$
Secondo sconto: $102 - 10\% \text{ di } 102 = 102 - 10.2 = 91.8€$

### 3.4 Ordine dei numeri reali
- **Relazioni d'ordine**: $<$, $>$, $\leq$, $\geq$
- **Proprietà di compatibilità con le operazioni**:
  - Se $a < b$, allora $a + c < b + c$
  - Se $a < b$ e $c > 0$, allora $a \times c < b \times c$
  - Se $a < b$ e $c < 0$, allora $a \times c > b \times c$

**Esempio**: Dati $a = -3$ e $b = 2$, verificare che $a < b$ ma $a \times (-5) > b \times (-5)$
$a < b$ poiché $-3 < 2$
$a \times (-5) = (-3) \times (-5) = 15$
$b \times (-5) = 2 \times (-5) = -10$
$15 > -10$, quindi $a \times (-5) > b \times (-5)$

## 4. ESERCIZI RISOLTI

1. **Esercizio**: Calcolare il valore dell'espressione $\frac{3^2 \times 2^4}{6^2 \div 2^2}$
   **Soluzione**:
   $\frac{3^2 \times 2^4}{6^2 \div 2^2} = \frac{9 \times 16}{36 \div 4} = \frac{144}{9} = 16$

2. **Esercizio**: Semplificare $\frac{\sqrt{50} + \sqrt{8}}{\sqrt{18}}$
   **Soluzione**:
   $\frac{\sqrt{50} + \sqrt{8}}{\sqrt{18}} = \frac{\sqrt{25 \times 2} + \sqrt{4 \times 2}}{\sqrt{9 \times 2}} = \frac{5\sqrt{2} + 2\sqrt{2}}{3\sqrt{2}} = \frac{7\sqrt{2}}{3\sqrt{2}} = \frac{7}{3}$

3. **Esercizio**: Trovare il minimo comune multiplo di 36, 48 e 60
   **Soluzione**:
   $36 = 2^2 \times 3^2$
   $48 = 2^4 \times 3$
   $60 = 2^2 \times 3 \times 5$
   mcm = $2^4 \times 3^2 \times 5 = 16 \times 9 \times 5 = 720$

4. **Esercizio**: Ordinare dal più piccolo al più grande: $\frac{3}{7}$, $\frac{5}{11}$, $\frac{7}{15}$
   **Soluzione**:
   Portiamo tutto allo stesso denominatore:
   $\frac{3}{7} = \frac{3 \times 11 \times 15}{7 \times 11 \times 15} = \frac{495}{1155}$
   $\frac{5}{11} = \frac{5 \times 7 \times 15}{11 \times 7 \times 15} = \frac{525}{1155}$
   $\frac{7}{15} = \frac{7 \times 7 \times 11}{15 \times 7 \times 11} = \frac{539}{1155}$
   Quindi: $\frac{3}{7} < \frac{5}{11} < \frac{7}{15}$

5. **Esercizio**: Se $x$ aumenta del 20% e poi diminuisce del 25%, qual è la variazione percentuale totale rispetto al valore iniziale?
   **Soluzione**:
   Aumento del 20%: $x \rightarrow 1.2x$
   Diminuzione del 25%: $1.2x \rightarrow 1.2x \times 0.75 = 0.9x$
   Variazione percentuale totale: $\frac{0.9x - x}{x} \times 100 = \frac{-0.1x}{x} \times 100 = -10\%$

6. **Esercizio**: Calcolare il risultato di $(0.125)^{-2} \times (0.2)^3$
   **Soluzione**:
   $(0.125)^{-2} \times (0.2)^3 = (1/0.125)^2 \times (0.2)^3 = 8^2 \times (0.2)^3 = 64 \times 0.008 = 0.512$

7. **Esercizio**: Semplificare $\frac{\sqrt{12} - \sqrt{3}}{\sqrt{3}}$
   **Soluzione**:
   $\frac{\sqrt{12} - \sqrt{3}}{\sqrt{3}} = \frac{\sqrt{4 \times 3} - \sqrt{3}}{\sqrt{3}} = \frac{2\sqrt{3} - \sqrt{3}}{\sqrt{3}} = \frac{\sqrt{3}}{\sqrt{3}} = 1$

8. **Esercizio**: Un capitale di 1000€ viene investito per 2 anni a un tasso di interesse composto del 5% annuo. Quanto vale alla fine dei 2 anni?
   **Soluzione**:
   Capitale finale = $1000 \times (1 + 0.05)^2 = 1000 \times 1.1025 = 1102.50€$

9. **Esercizio**: Se $a : b = 3 : 5$ e $b : c = 10 : 7$, trovare $a : c$
   **Soluzione**:
   $\frac{a}{b} = \frac{3}{5}$
   $\frac{b}{c} = \frac{10}{7}$
   $\frac{a}{c} = \frac{a}{b} \times \frac{b}{c} = \frac{3}{5} \times \frac{10}{7} = \frac{30}{35} = \frac{6}{7}$
   Quindi $a : c = 6 : 7$

10. **Esercizio**: Determinare per quali valori di $x$ è verificata la seguente disuguaglianza: $\frac{2x-1}{3} > \frac{x+2}{2}$
    **Soluzione**:
    $\frac{2x-1}{3} > \frac{x+2}{2}$
    $\frac{2(2x-1)}{6} > \frac{3(x+2)}{6}$
    $\frac{4x-2}{6} > \frac{3x+6}{6}$
    $4x-2 > 3x+6$
    $4x-3x > 6+2$
    $x > 8$

## 5. ERRORI COMUNI DA EVITARE

1. **Confondere le proprietà delle potenze**:
   - Errore: $(2 \times 3)^2 = 2^2 \times 3^2 = 4 \times 9 = 36$ ✓ (corretto)
   - Errore: $2^2 + 3^2 = (2 + 3)^2$ ✗ (sbagliato!), infatti $4 + 9 = 13 \neq 25 = 5^2$

2. **Sbagliare i segni nelle operazioni con numeri negativi**:
   - Errore: $(-3) \times (-5) = -15$ ✗ (sbagliato!), in realtà $(-3) \times (-5) = 15$
   - Errore: $-3^2 = -9$ ✓ (corretto, perché $-3^2 = -(3^2) = -9$)
   - Errore: $(-3)^2 = -9$ ✗ (sbagliato!), in realtà $(-3)^2 = 9$

3. **Dimenticare di ridurre le frazioni ai minimi termini**:
   - Errore: $\frac{36}{48} = \frac{36}{48}$ ✗ (non ridotta), dovrebbe essere $\frac{3}{4}$

4. **Errori nelle operazioni con frazioni**:
   - Errore: $\frac{1}{2} + \frac{1}{3} = \frac{1+1}{2+3} = \frac{2}{5}$ ✗ (sbagliato!)
   - Corretto: $\frac{1}{2} + \frac{1}{3} = \frac{3}{6} + \frac{2}{6} = \frac{5}{6}$

5. **Confondere la divisione con le frazioni inverse**:
   - Errore: $\frac{a}{b} \div \frac{c}{d} = \frac{a}{b} \times \frac{d}{c}$ ✓ (corretto)
   - Errore: $\frac{a}{b} \div \frac{c}{d} = \frac{a \div c}{b \div d}$ ✗ (sbagliato!)

6. **Errori con lo zero e l'infinito**:
   - Errore: $\frac{a}{0} = 0$ ✗ (sbagliato!), la divisione per zero non è definita
   - Errore: $0^0 = 0$ ✗ (sbagliato!), per convenzione $0^0 = 1$

7. **Confondere le regole di precedenza nelle espressioni**:
   - Errore: $2 + 3 \times 4 = 5 \times 4 = 20$ ✗ (sbagliato!)
   - Corretto: $2 + 3 \times 4 = 2 + 12 = 14$

8. **Errori nella semplificazione di espressioni con radici**:
   - Errore: $\sqrt{a^2} = a$ ✓ (corretto solo se $a \geq 0$)
   - Corretto: $\sqrt{a^2} = |a|$ (per qualsiasi valore di $a$)
   - Errore: $\sqrt{a + b} = \sqrt{a} + \sqrt{b}$ ✗ (sbagliato!)

9. **Errori nei calcoli percentuali**:
   - Errore: Un aumento del 10% seguito da un ulteriore aumento del 10% equivale a un aumento del 20% ✗ (sbagliato!)
   - Corretto: Un aumento del 10% seguito da un ulteriore aumento del 10% equivale a un aumento del 21% (perché $1.1 \times 1.1 = 1.21$)