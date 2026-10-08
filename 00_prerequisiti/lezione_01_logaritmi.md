# Lezione 01 · Logaritmi

> **Modulo 00 — Prerequisiti** · Stato: in corso  
> [Indice del corso](../README.md) · [Esercizi e correzioni](esercizi_lezione_01.md) · [Progressi](../PROGRESSI.md)

## Obiettivi didattici

Al termine della lezione saprai interpretare un logaritmo, utilizzare le tre proprietà fondamentali, risolvere semplici equazioni logaritmiche e affrontare disequazioni rispettando le condizioni di esistenza.

## 1. Definizione

Per $a>0$, $a\ne1$ e $b>0$:

$$
\boxed{\log_a(b)=c\iff a^c=b}
$$

Il logaritmo chiede: **a quale esponente devo elevare $a$ per ottenere $b$?**

| Esempio | Verifica |
|:--|:--|
| $\log_2(8)=3$ | $2^3=8$ |
| $\log_3(81)=4$ | $3^4=81$ |
| $\log_2(\frac18)=-3$ | $2^{-3}=\frac18$ |
| $\log_9(3)=\frac12$ | $9^{1/2}=\sqrt9=3$ |

> **Attenzione:** $2^{-3}=\frac{1}{8}$, **non** $-8$. L'esponente negativo indica il reciproco.

## 2. Le proprietà fondamentali

Per argomenti strettamente positivi e basi ammissibili:

### Prodotto

$$
\boxed{\log_a(bc)=\log_a(b)+\log_a(c)}
$$

**Esempio:** $\log_2(8)+\log_2(4)=\log_2(32)=5$.

> Non confondere il prodotto con la somma: $\log_a(b)+\log_a(c)$ **non** è, in generale, $\log_a(b+c)$.

### Quoziente

$$
\boxed{\log_a\left(\frac{b}{c}\right)=\log_a(b)-\log_a(c)}
$$

**Esempio:** $\log_3(81)-\log_3(9)=\log_3(9)=2$.

### Potenza

$$
\boxed{\log_a(b^n)=n\log_a(b)}
$$

**Esempio:** $\log_3(9^4)=4\log_3(9)=8$.

## 3. Equazioni logaritmiche

### Esempio 1

Risolvere:

$$
\log_3(x+2)=2
$$

1. **Dominio:** $x+2>0$, quindi $x>-2$.
2. **Passaggio alla forma esponenziale:** $x+2=3^2=9$.
3. **Soluzione candidata:** $x=7$.
4. **Verifica:** $7>-2$, dunque la soluzione è ammissibile.

$$
\boxed{S=\{7\}}
$$

### Esempio 2 — Somma di logaritmi

$$
\log_2(x)+\log_2(x-2)=3
$$

Per il dominio servono contemporaneamente $x>0$ e $x-2>0$, quindi $x>2$.

$$
\begin{aligned}
\log_2(x(x-2))&=3\\
x(x-2)&=2^3\\
x^2-2x-8&=0\\
(x-4)(x+2)&=0
\end{aligned}
$$

Le soluzioni algebriche sono $x=4$ e $x=-2$; soltanto $x=4$ rispetta il dominio.

$$
\boxed{S=\{4\}}
$$

## 4. Disequazioni logaritmiche

Per $a>1$ la funzione logaritmica è **crescente**:

$$
\log_a(x)>c\iff x>a^c
$$

Per $0<a<1$ è **decrescente**, quindi il verso si inverte. In tutti i casi si controlla il **dominio**.

### Esempio — Con un argomento traslato

$$
\log_3(x-2)>2
$$

- Dominio: $x-2>0\Rightarrow x>2$.
- Poiché $3>1$: $x-2>3^2=9$.
- Si somma $2$ a entrambi i membri: $x>11$.

$$
\boxed{S=(11,+\infty)}
$$

## 5. Errori da evitare

| Errore frequente | Correzione |
|:--|:--|
| Scambiare base ed esponente | $\log_a(B)=c\iff a^c=B$ |
| Sommare gli argomenti di due logaritmi | Nella proprietà di somma gli argomenti **si moltiplicano** |
| Trascurare il dominio | Ogni argomento deve essere **maggiore di zero** |
| Sbagliare lo spostamento di un termine | Da $x-2>9$ segue $x>11$, non $x>7$ |

---

**Ripresa del corso:** [Esercizio 1.15](esercizi_lezione_01.md) — $\log_2(x+3)<4$. Non leggere una soluzione prima di aver tentato l'esercizio.
