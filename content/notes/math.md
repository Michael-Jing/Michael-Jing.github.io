+++
+++
Is $ 2018^{1991}+2018^{1990}+1 $ prime or not
===


\begin{equation} 
\begin{aligned}
 a^{1991} + a^{1990} + 1 \\
 &= a^{1991} + a^{1990} + 1 + a^{1989} - a^{1989} \\
 &= (a^2 + a + 1)a^{1989} - (a^{1989} - 1) \\
 &= (a^2 + a + 1)a^{1989} - (a^3 - 1)(a^{1989} - 1) / (a^3 - 1) \\
 &= (a^2 + a + 1)a^{1989} - (a - 1)(a^2 + a + 1)(a^{1989} - 1)/(a^3 - 1) \\
 &= (a^2 + a + 1)(a^{1989} - (a - 1)(a^{1989} - 1)/(a^3 - 1)) \\
 &= (a^2 + a + 1)(a^{1989} - (a - 1)({a^3}^{663} - 1)/(a^3 - 1)) \\
 &= (a^2 + a + 1)(a^{1989} - (a - 1)(A^{663} - 1)/(A - 1)) \\
 &= (a^2 + a + 1)(a^{1989} - (a - 1)(A^{662} + A^{661} + ... + 1))
 \end{aligned}
\end{equation}


{% include lib/mathjax.html %}
