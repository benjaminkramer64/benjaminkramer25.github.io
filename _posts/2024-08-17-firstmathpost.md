---
layout: post
title: Initial Mathematics Post!
author: Benjamin Kramer
subtitle: 5-Minute Galois Theory 
tags: mathematics
---

Eisenstein's criterion for irreducibly may be stated in different ways, however it will be presented how it was presented in class. Usually, it states that if there are no integer coefficients, than the coefficients would take the form of radicals. This can also be proved in the contrapositive form.

\begin{theorem}[Eisenstein's Irreducibility Criterion]
Let there exist a polynomial of degree $n$ defined as 
\[a_0 x^n + \ldots + a_n \quad \text{where } a_i \in \mathbb{Z} \text{ for every index } i\]
\[\frac{p}{q} \in \mathbb{Q} \quad \text{where } p, q \text{ are relatively prime.}\]
\[\ \text{If }  \frac{p}{q} \text{ is a root of the sum of } a_{n-i} x^i \text{, then } q \text{ divides } a_0 \text{ and } p \text{ divides } a_n.\]
\end{theorem}


\emph{Proof.}
Let there be a n-th degree polynomial which we represent as 
\begin{align*}
f(x) &= a_{n}x^{n} + \ldots + a_{1}x + a_{0} \\
f\left(\frac{p}{q}\right) &= a_{n}\left(\frac{p}{q}\right)^{n} + \ldots + a_{1}\left(\frac{p}{q}\right) + a_{0} \\
\end{align*}
For this proof, we shall suppose that
\begin{align*}
f\left(\frac{p}{q}\right) &= 0, \\
\end{align*}
then
\begin{align*}
a_{n}\left(\frac{p}{q}\right)^{n} + \ldots + a_{1}\left(\frac{p}{q}\right) + a_{0} = 0 \\
\end{align*}
Thus, this means that
\begin{align*}
a_{n}\frac{p^n}{q^n} + \ldots + a_{1}\frac{p}{q} + a_{0} &= -a_{n} \\
\end{align*}
Which means that
\begin{align*}
p\left(a_{n}p^{n-1} + a_{n-1}p^{n-2} + \ldots + a_{1}\right) = -a_{n}q^{n} \\
\end{align*}
\begin{align*}
\text{Thus, } p \text{ divides } -a_{n}q^{n} \text{ but since } p \text{ and } q^{n} \text{ are relatively prime, then } p \text{ divides } a_{n}. \\
\text{A similar argument proves that } q \text{ divides } a_{0}.
\end{align*}
\qed

Using this criterion, if all of the coefficients on a monic polynomial are integers, this means that the roots are either non-rational or in Z. If the roots r are in the integers, f(r) = 0, and d must divide the constant terms of the polynomial. Hence, by taking all of the positive and negative factors of the constant term and substituting them into the function, we can find the roots of a n-th degree polynomial.


\section{Bibliography}

\begin{enumerate}
    \item Infeld, Leopold (1948), Whom the Gods Love: The Story of Evariste Galois, Classics in Mathematics Education Series, Reston, Va: National Council of Teachers of Mathematics, ISBN 978-0-87353-125-2 – Classic fictionalized biography by physicist Infeld.
    \item Orendain, Juan "228L21.pdf". Lecture Notes on Canvas, Differential Equations. Spring 2024.
