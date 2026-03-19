## Talteori, Ma5

Wanmin Liu

20251117, Rum 2009.


---

Planering.

Pass 1. 14.35 - 15.35.

* Förkunskaper.
  - Faktorisering av heltal.
  - Decimalsystemet (basen 10).
* Binära talsystemet (basen 2).
  - Från binär till decimal form.
  - Från decimal till binär form.
* Kvot och rest för heltal
* Uppgifter i boken.

Pass 2. 15.55 - 17.00

* Representation av tal i olika talbaser.
  - Det oktala talsystemet (basen 8).
  - Det hexadecimala talsystemet (basen 16).
* Primalitet är en egenskap hos heltalet självt.
* Uppgifter i boken.


---

### Decimala talsystemet (basen 10)

Det decimala talsystemet är ett **positionssystem** med talet **tio** som bas, viket innebär två viktiga saker:  

  *  Varje tal kan skrivas med hjälp av de tio symboler (siffrorna), dvs $0,1,2,3,4,5,6,7,8,9$.
  *  Varje siffra i ett tal representerar en tiopotens, vars storlek beror på siffrans position i talet.
 
**Exempel 1.**
 
$$
\begin{align}
1984 &= 1\cdot 10^3+9\cdot 10^2+8\cdot 10^1+4\cdot 10^0,\\
3,14 &= 3\cdot 10^0+1\cdot 10^{-1}+4\cdot 10^{-2},\\
-67 &=  - \Big(67\Big)=-\Big(6\cdot 10^{1}+7\cdot 10^{0}\Big),\\
-2,7 &= - \Big(2,7\Big)=-\Big(2\cdot 10^{0}+7\cdot 10^{-1}\Big).
\end{align}
$$

De tal som skrivs i formen till högerledet kallas i **utvecklad form**.

Om vi ​​vill betona det i talet med basen tio, kan vi skriva ett subskript med tio, till exempel $1984_{\mathrm{tio}}$.


### Binära talsystemet (basen 2)

Det binära talsystemet är ett **positionssystem** med talet **två** som bas, viket innebär två viktiga saker:  

  *  Varje tal kan skrivas med hjälp av de två symboler $0,1$.
  *  Varje siffra i ett tal representerar en två-potens, vars storlek beror på siffrans position i talet.
 
**Exempel 2.** (_Från binär till decimal form._) Omskriv $100101_{\mathrm{två}}$ till decimal form. 
$$
\begin{align}
100101_{\mathrm{två}} &= 1\cdot 2^5+0\cdot 2^4+0\cdot 2^3+1\cdot 2^2+0\cdot 2^1+1\cdot 2^0\\
 &= 1\cdot 32+0\cdot 16+0\cdot 8+1\cdot 4+0\cdot 2+1\cdot 1\\
 &= 37_{\mathrm{tio}}.
\end{align}
$$
Så vi skriver ett tal från binär till decimal form.


| $\cdots$ | $2^7$ | $2^6$ | $2^5$ | $2^4$ | $2^3$ | $2^2$ | $2^1$ | $2^0$ |    $2^{-1}$   |    $2^{-2}$   | $\cdots$ |
|:--------:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|:-------------:|:-------------:|:--------:|
| $\cdots$ | $128$ |  $64$ |  $32$ |  $16$ |  $8$  |  $4$  |  $2$  |  $1$  | $\frac{1}{2}$ | $\frac{1}{4}$ | $\cdots$ |

**Exempel 3.** (_Från decimal till binär form._) Omskriv $67_{\mathrm{tio}}$ till binär form. 

**Metod 1.** Vi använder exponenttabellen för 2.
$$
\begin{align}
67_{\mathrm{tio}} &= 1\cdot 64+2+1\\
&= 1\cdot 2^6+0\cdot 2^5+0\cdot 2^4+0\cdot 2^3+0\cdot 2^2+1\cdot 2^1+1\cdot 2^0\\
 &= 1000011_{\mathrm{två}}.
\end{align}
$$


### Kvot och rest för heltal
**Definition.** Om $a$ och $b$ är två *heltal* och $b\neq 0$, så ger divisionen $\frac{a}{b}$ **kvoten** $k$ och **resten** $r$, där *heltalen* $k$ och $r$ uppfyller villkoret
$$a=k\cdot b +r.$$
Vi skriver att divisionen $a/b$ ger kvoten $k$ och resten $r$.

* Om $r$ även uppfyller villkoret $0\leq r<b$, så kallas $r$ för den principala resten.  
* Om $r=0$, säger vi att $a$ är **delbart** med $b$.


**Exempel 3.** (_Från decimal till binär form._) Omskriv $67_{\mathrm{tio}}$ till binär form. 

**Metod 2.** Successivt division med basen.

Vi skulle kunna tänka om hur vi kan hitta varje siffra i talet $1984_{\mathrm{tio}}$ i basen 10.

Dividera $1984_{\mathrm{tio}}$ successivt med $10$ tills **kvoten** är $\mathbf{0}$:

$1984/10$ ger kvoten $184$ och resten $4$.  
$198/10$ ger kvoten $19$ och resten $8$.  
$19/10$ ger kvoten $1$ och resten $9$.  
$1/10$ ger kvoten $\mathbf{0}$ och resten $1$.

Läs från botten till toppen: $1984_{\mathrm{tio}}$.

Vi gör samma spel med bas 2.

 _Steg 1:_ Dividera $67_{\mathrm{tio}}$ successivt med $2$ tills **kvoten** är $\mathbf{0}$:

$67/2$ ger kvoten $33$ och resten $1$.  
$33/2$ ger kvoten $16$ och resten $1$.  
$16/2$ ger kvoten $8$ och resten $0$.  
$8/2$ ger kvoten $4$ och resten $0$.  
$4/2$ ger kvoten $2$ och resten $0$.  
$2/2$ ger kvoten $1$ och resten $0$.  
$1/2$ ger kvoten $\mathbf{0}$ och resten $1$.  


_Steg 2:_ Läs från botten till toppen som $1000011_{\mathrm{två}}$.


**Exempel 4.** (Uppgift 1114.) Dominoeffekten och geometrisk serier.

* Vad blir $1+2+4+8+16$?  
* Kan vi tänka med hjälp av det binära talet? 

Ovanstående fråga översätts till frågan nedan.

* Vad blir $1_{\mathrm{två}}+10_{\mathrm{två}}+100_{\mathrm{två}}+1000_{\mathrm{två}}+10000_{\mathrm{två}}$?

Vi kan utföra uppställning i addition.
Det blir $11111_{\mathrm{två}}$.
$$
\begin{align}
1_{\mathrm{två}}+1_{\mathrm{två}} &= 10_{\mathrm{två}}.\\
11_{\mathrm{två}}+1_{\mathrm{två}}&= 100_{\mathrm{två}}.\\
111_{\mathrm{två}}+1_{\mathrm{två}}&= 1000_{\mathrm{två}}.\\
1111_{\mathrm{två}}+1_{\mathrm{två}}&= 10000_{\mathrm{två}}.\\
11111_{\mathrm{två}}+1_{\mathrm{två}}&= 100000_{\mathrm{två}}.
\end{align}
$$

Vi skulle kunna skriva om
$$11111_{\mathrm{två}}=2^0+2^1+2^2+2^3+2^4, \text{ och } 100000_{\mathrm{två}}=2^5.$$
Så får vi en formel
$$2^0+2^1+2^2+2^3+2^4=2^{4+1}-1.$$


Vi kunde hitta en generell formel
$$2^0+2^1+2^2+\cdots +2^n=2^{n+1}-1.$$

Vi är mer bekanta med detta dominoliknande talspel som använder decimalsystemet.
$$
\begin{align}
99999+1 &= 100000.\\
99999 &= 100000-1.\\
9(10^0+10^1+10^2+10^3+10^4)&= 10^5-1.\\
10^0+10^1+10^2+10^3+10^4&= \frac{10^5-1}{10-1}.
\end{align}
$$

Med samma metod av dominoeffekten, för ett positivt heltal $b$, har vi 
$$b^0+b^1+b^2+\cdots+b^n = \frac{b^{n+1}-1}{b-1}.$$


---


**Uppgifter i boken.**
s 11. Nivå 1. Alla (b)-uppgifter. Nivå 2. 1108,1110, 1111 a), b). (Nivå 3. 1114).

---


Pass 2. 15.55 - 17.00.

## Talsystem med andra talbaser


### 60-baserat system (basen 60)

Tidsenheter fungerar som ett lokalt exempel på ett 60-baserat system.

Kärna:  

* 60 sekunder → 1 minut. 
* 60 minuter → 1 timme. 

Exempel på beräkning i bas 60:    

* 45 min + 30 min → 75 min → 1 timme 15 min.  
Processen: 75 = 1·60 + 15.

* (Addition med sekunder) 5:12:45 + 0:03:30.   
Sekunder: 45 + 30 = 75 → 1·60 + 15.   
Minuter: 12 + 3 + 1 = 16.   
Resultat: 5:16:15. 

### Det oktala talsystemet (basen 8)

Det oktala talsystemet är ett **positionssystem** med basen 8, viket innebär två viktiga saker:  

  *  Varje tal kan skrivas med hjälp av de åtta symboler $0,1,2,3,4,5,6,7$.
  *  Varje siffra i ett tal representerar en 8-potens, vars storlek beror på siffrans position i talet.

Exempel

$$
\begin{align}
67_{\mathrm{åtta}} &= 6\cdot 8^1+7\cdot 8^0\\
 &= 6\cdot 8+7\cdot 1\\
 &= 55_{\mathrm{tio}}.
\end{align}
$$

### Det hexadecimala talsystemet (basen 16)

Det hexadecimala talsystemet är ett **positionssystem** med basen 16, viket innebär två viktiga saker:  

  *  Varje tal kan skrivas med hjälp av de 16 symboler $0,1,2,3,4,5,6,7,8,9,A,B,C,D,E,F$.
  *  Varje siffra i ett tal representerar en 16-potens, vars storlek beror på siffrans position i talet.

Vi vet att
$$A_{\mathrm{sexton}} = 10_{\mathrm{tio}},\quad B_{\mathrm{sexton}} = 11_{\mathrm{tio}}, \quad C_{\mathrm{sexton}} = 12_{\mathrm{tio}},$$
$$D_{\mathrm{sexton}} = 13_{\mathrm{tio}},\quad E_{\mathrm{sexton}} = 14_{\mathrm{tio}}, \quad F_{\mathrm{sexton}} = 15_{\mathrm{tio}}.$$

Fördelen med att använda symbolen $A$ är att den bara tar en plats, och symbolen $10$ tar två platser.

Exempel

$$
\begin{align}
67_{\mathrm{sexton}} &= 6\cdot 16^1+7\cdot 16^0\\
 &= 6\cdot 16+7\cdot 1\\
 &= 103_{\mathrm{tio}}.
\end{align}
$$

$$
\begin{align}
67_{\mathrm{tio}} &= 4\cdot 16+3\\
 &= 4\cdot 16^1+3\cdot 16^0\\
 &= 43_{\mathrm{sexton}}.
\end{align}
$$


Vi kan använda följande tabeller för att ändra ett tal i basen 10 till basen 8 eller basen 16.

|  $8^4$ | $8^3$ | $8^2$ | $8^1$ | $8^0$ |
|:------:|:-----:|:-----:|:-----:|:-----:|
| $4096$ | $512$ |  $64$ |  $8$  |  $1$  |

|  $16^4$ | $16^3$ | $16^2$ | $16^1$ | $16^0$ |
|:------:|:-----:|:-----:|:-----:|:-----:|
| $65536$ | $4096$ |  $256$ |  $16$  |  $1$  |


### Primalitet är en egenskap hos heltalet självt.

Ett **primtal** är ett heltal större än 1 som bara kan delas exakt (utan rest) med 1 och sig självt.

Exempel på primtal (i decimal form)
$$2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31\cdots $$

Tal som inte är primtal kallas **sammansatta tal** (de har fler än två delare).

Exempel:
$$4 = 2\cdot 2, 6 = 2\cdot 3, 8 = 2\cdot 4, 9 = 3\cdot 3.$$

Det minsta primtalet är 2, och det är också det enda jämna primtalet.

Primalitet är en egenskap hos heltalet självt, och påverkas inte av vilket talsystem (bas) som används för att skriva talet.

**Sats.** Om ett tal $p$ är ett primtal i vårt vanliga talsystem (bas 10), så är det också primtal i alla andra talsystem.

**Bevis.** Anta motsatsen: att $p$ inte är primtal i något annat talsystem med bas $b$. Då kan man skriva 
$$p=u_{b}\cdot v_{b}$$ för heltal $u_{b}$ och $v_{b}$ med 
$$1<u_{b}<p \text{ och } 1<v_{b}<p.$$
Vi skulle kunna skriva om $u_p$ och $v_p$ i basen 10-systemet, och resultaten är fortfarande heltal, betecknat $u$ respektive $v$. Dvs $$p=u\cdot v, \quad \text{och }1<u<p, \ 1<v<p.$$
Alltså skulle $p$ inte vara primtal heller i bas 10. Det blir en motsägelse.




---


**Uppgifter i boken.**
s 11. Nivå 1. Alla (b)-uppgifter. Nivå 2. 1108,1110, 1111 a), b). (Nivå 3. 1114).

---