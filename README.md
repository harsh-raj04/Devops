# Table of Probability Distribution Formulas

| Distribution | PMF | Mean | Variance | MGF |
|-------------|-----|------|----------|-----|
| **Bernoulli** | $P(X=x) = p^x q^{1-x}$ for $x \in \{0,1\}$ | $p$ | $pq$ | $M_X(t) = q + pe^t$ |
| **Binomial** | $P(X=x) = \binom{n}{x}p^x q^{n-x}$ for $x \in \{0,1,...,n\}$ | $np$ | $npq$ | $M_X(t) = (q+pe^t)^n$ |
| **Negative Binomial** | $P(X=x) = \binom{x+r-1}{x}p^r q^x$ for $x \in \{0,1,2,...\}$ | $\frac{rq}{p}$ | $\frac{rq}{p^2}$ | $M_X(t) = \left(\frac{p}{1-qe^t}\right)^r$ for $t < -\ln(q)$ |
| **Geometric** | $P(X=x) = p q^{x-1}$ for $x \in \{1,2,3,...\}$ | $\frac{1}{p}$ | $\frac{q}{p^2}$ | $M_X(t) = \frac{pe^t}{1-qe^t}$ for $t < -\ln(q)$ |
| **Poisson** | $P(X=x) = \frac{\lambda^x e^{-\lambda}}{x!}$ for $x \in \{0,1,2,...\}$ | $\lambda$ | $\lambda$ | $M_X(t) = e^{\lambda(e^t-1)}$ |
