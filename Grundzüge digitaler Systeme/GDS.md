
### EK

Positive Zahl:
	Vorne auffüllen bis länge m (zb. 1010, m=5 ⟶01010)
Negative Zahl:
	Vorne auffüllen bis länge m (zb. 1010, m=5 ⟶01010)
	Alle Bits flippen
### ZK

EK nehmen und +1 rechnen

### Exzessdarstellung

Symmetrischer Exzess

![[Pasted image 20251109170446.png]]



Nicht-symmetrischer Exzess

![[Pasted image 20251109170731.png]]


### Exponentialschreibweise

$x=m\cdot b^e$

Normalisierung:
- Genau eine stelle vor dem Komma
- Exponent ganzzahlig
- Basis ganzzahlig $b>1$

### Gleitkomma

![[Pasted image 20251109172124.png]]

Normalisierung:

- Erste Stelle der Mantisse $m_{0}\neq 0$ 
- Genau eine Stelle vor dem Komma

Denormalisierung:

Wird genutzt für Zahlen nahe oder gleich Null. Wenn der $e=e_{min}$ dann heben wir die $m_{0}\neq 0$ Bedingung auf.

Schreibweise:
$F(b, p, emin, emax, denorm)$

b . . . Basis (base, radix) (b ≥ 2) 
p . . . Mantissenlänge (precision) (p ≥ 2) 
emin . . . kleinster Exponent 
emax . . . größter Exponent 
denorm . . . Normalisierungsindikator 
	true ⇒ enthält denormalisierte Zahlen 
	false ⇒ enthält keine denormalisierten Zahlen
