$$
\begin{aligned}
&\text{Para }\sum = \{0,1\}, \text{escribir } \Sigma^0, \Sigma^1, \Sigma^2\\
&\Sigma^0 = \{\epsilon\}\\
&\Sigma^1 = \{0,1\}\\
&\Sigma^2 = \{00,01,10,11\}
\end{aligned}
$$
$$
\begin{aligned}
&\text{Decidir cuales son cadenas parte de } \{a,b\}:\\
&n, abba, \{a\}, \epsilon, baaaab&\\
&\text{Cadenas: abba | baaaab | }\epsilon\\
&\text{No Cadenas: n, \{a\}}
\end{aligned}
$$

$$
\begin{aligned}
&\text{Si }x = aba\text{, entonces:}\\
&|x| = 3\\
&x^2 = abaaba\\
&x^0 = \epsilon
\end{aligned}
$$

$$
\begin{aligned}
&\text{Para } w = ababa \text{, encuentre sus prefijos, sufijos y subcadenas.}\\
&\text{prefijos: } \{\epsilon, a, ab, aba, abab\}\\
&\text{sufijos: } \{\epsilon, a, ba, aba, baba\}\\
&\text{subcadenas:} \{\epsilon, a,ab,aba,abab,bab,baba, \cdots\}
\end{aligned}
$$
Sea $L = \{a,ab\}$ y $M = \{b, ba\}$, calcular: $L \cdot M$
$$
L \cdot M = \{ab,aba,abb,abba\}
$$
