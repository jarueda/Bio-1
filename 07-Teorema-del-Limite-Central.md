# Teorema del Límite Central {#TLC}



Este postulado es uno de los más importantes para la teoría clásica de la estadística.  Enuncia que, sin importar la distribución de probabilidades de la cual provengan las observaciones de una variable aleatoria, bajo ciertas condiciones, la distribución de los promedios tiende a parecerse a la distribución **normal** \@ref(function).

Si X es una variable aleatoria que tiene media y varianza finita, $X \,\ \tilde \,\ f(x)$ con $E(X)=\mu$ y $Var(x)= \sigma^2$.
Si se definen:

$$\bar X= \frac{\sum_{i=1}^nx_i}{n} $$
$$S^2 = \frac{\sum_{i=1}^n(x_i-\mu)^2}{n-1} $$

Entonces, bajo ciertas condiciones, la distribución muestral de $\bar X$ tendrá distribución aproximadamente normal con  $E(\bar X)=\mu$ y $Var(\bar X)= \frac{\sigma^2}{n}$ y con esto,

$$\frac{\bar X -E(x)}{\sqrt\frac{\sigma^2}{n}} \,\ \tilde \,\ \eta \ (\mu= 0; \sigma^2 = 1) $$

**Esto es que los promedios estandarizados se distribuyen normal o aproximadamente normal.  La calidad de la aproximación a la normal es función de qué tan simétrica es la distribución original, $f(x)$**

## Note {-}

Si X es una variable aleatoria normal, $X \,\ \tilde \,\ \eta(\mu;\sigma^2)$

Entonces la distribución muestral de $\bar X$ tendrá distribución normal con  $E(\bar X)=\mu$ y $Var(\bar X)= \frac{\sigma^2}{n}$ y con esto,

$$\frac{\bar X -E(x)}{\sqrt\frac{\sigma^2}{n}} \,\ \tilde \,\ \eta \ (0; 1) $$

También es normal estándar, independientemente del Teorema del Limite Central.

**______________________________________________________**
