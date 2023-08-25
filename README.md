## Bernouilli - Binomial distribution

Example of Binomial distribution

Question : on lance un dé à 6 faces 20 fois, quelle est la probabilité d'obtenir 12 fois 6  ?

Nous pouvons modéliser cette situation en utilisant une distribution binomiale. 
Dans ce cas, nous avons $n=20$ essais (lancers de dé), et nous sommes intéressés par la probabilité d'obtenir exactement 
$k=12$ succès (obtenir un $6$). 

La probabilité de succès à chaque essai est $p=\dfrac{1}{6}$, puisqu'il y a $6$ faces égales sur un dé standard.

La probabilité de $k$ succès dans une distribution binomiale est donnée par la formule :

$$P(X=k) = \binom{n}{k} p^k (1-p)^{n-k}$$


