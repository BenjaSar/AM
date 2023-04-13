### Implementación

### Preguntas teóricas

3. La implementación de QDA estima la probabilidad condicional utilizando `0.5*np.log(det(inv_cov)) -0.5 * unbiased_x.T @ inv_cov @ unbiased_x` que no es *exactamente* lo descrito en el apartado teórico ¿Cuáles son las diferencias y por qué son expresiones equivalentes?

La principal diferencia es que en la fórmula teórica, tenemos el término $-\frac{1}{2}\log |\Sigma_j|$, mientras que en la implementación del código, tenemos el término $\frac{1}{2}\log |\Sigma_j^{-1}|$. Estos dos términos son equivalentes porque $|\Sigma_j^{-1}| = \frac{1}{|\Sigma_j|}$.

En la fórmula teórica, hay un término adicional $C$. Sin embargo, este término constante no afecta el cálculo de los máximos, ya que es el mismo para todas las clases y, por lo tanto, no cambia qué clase maximiza la función.