




$$
\[
\begin{array}{ll}
\textbf{Atomare Aussagen:} \\[4pt]
s &: \text{„kleines Menü“} \\[2pt]
g &: \text{„großes Menü“} \\[2pt]
u &: \text{„Suppe gewählt“} \\[2pt]
a &: \text{„Salat gewählt“} \\[2pt]
m &: \text{„Miso-Suppe“} \\[2pt]
ss &: \text{„Süß-saure Suppe“} \\[2pt]
c &: \text{„Cashew Chicken“} \\[2pt]
d &: \text{„Knusprige Ente“} \\[2pt]
t &: \text{„Frittierter Tofu“} \\[2pt]
mo &: \text{„Mochi (Dessert)“} \\[2pt]
se &: \text{„Sesambällchen (Dessert)“} \\[2pt]
e &: \text{„Eierreis (1€ Aufpreis)“}
\end{array}
\]
$$
$$
\begin{aligned}
\Phi :=\;& (s \oplus g) \\[4pt]
&\land (c \oplus d \oplus t) \\[4pt]
&\land (u \oplus a) \\[4pt]
&\land \big(u \rightarrow (m \oplus ss)\big) \\[2pt]
&\land \big(a \rightarrow (\neg m \land \neg ss)\big) \\[2pt]
&\land \big((m \lor ss) \rightarrow u\big) \\[4pt]
&\land \big(g \rightarrow (mo \oplus se)\big) \\[2pt]
&\land \big(s \rightarrow (\neg mo \land \neg se)\big) \\[2pt]
&\land \big((mo \lor se) \rightarrow g\big) \\[4pt]
&\land \big(e \rightarrow (c \lor d \lor t)\big).
\end{aligned}
$$
