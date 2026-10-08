# Lezione 1 — Logaritmi

## Obiettivi
Comprendere il significato del logaritmo, calcolare logaritmi semplici e usare le proprietà in equazioni e disequazioni.

## Definizione
Per **a > 0**, **a ≠ 1**, **b > 0**:

```text
log_a(b) = c  se e solo se  a^c = b
```

Il logaritmo chiede: «a quale esponente devo elevare la base a per ottenere b?».

Esempi:
- log₂(8) = 3 perché 2³ = 8
- log₃(81) = 4 perché 3⁴ = 81
- log₂(1/8) = −3 perché 2⁻³ = 1/8
- log₉(3) = 1/2 perché 9^(1/2) = 3

Un esponente negativo non implica un risultato negativo: 2⁻³ = 1/8, non −8.

## Proprietà fondamentali
Per argomenti positivi e una base ammissibile:
1. **Prodotto**: logₐ(bc) = logₐ(b) + logₐ(c)
2. **Quoziente**: logₐ(b/c) = logₐ(b) − logₐ(c)
3. **Potenza**: logₐ(bⁿ) = n·logₐ(b)

**Errore da evitare**: logₐ(b)+logₐ(c) NON è logₐ(b+c).

## Equazioni logaritmiche
Esempio: log₃(x+2) = 2.

1. Condizione di esistenza: x+2 > 0, cioè x > −2.
2. Trasformazione: x+2 = 3² = 9.
3. Soluzione: x = 7.
4. Verifica: 7 > −2, quindi è ammissibile.

Esempio con due logaritmi:
log₂(x)+log₂(x−2)=3.
- Dominio: x > 2.
- Proprietà del prodotto: log₂[x(x−2)] = 3.
- Quindi x²−2x=8, ossia (x−4)(x+2)=0.
- Candidate: x=4 oppure x=−2; soltanto **x=4** rispetta il dominio.

## Disequazioni logaritmiche
- Se **a > 1**, logₐ(x) > c equivale a x > aᶜ (tenendo conto del dominio).
- Se **0 < a < 1**, il logaritmo è decrescente e il verso della disuguaglianza si inverte.

Esempio da svolgere: **log₂(x) > 3**.

## Verifica della comprensione
Motivare sempre i passaggi, controllare le condizioni di esistenza e correggere gli errori prima di avanzare.
