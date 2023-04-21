![header](doc/LogoHeader.png)

# Analisis matematico

#### Authors

Juan Ignacio Iribet <br/>
Mariana Taglio <br/>
FS <br/>
2023


En este repositorio se podrán encontrar los ejercicios resueltos de la materia **Análisis Matemático**.  Este trabajo práctico consistió en la resolución de problemas prácticos y teóricos vinculados con *Linear and Quadratic Discriminat Analysis (LDA y QDA respectivamente)* y nociones de *redes neuronales*. Para visualizar la resolución de los ejercicios propuestos y las respuestas a las preguntas teóricas abrir el archivo <mark><em>tp_final.ipnybn</em> </mark>.
### *Linear Discriminant Analysis (LDA)*
Es un método basado en la hipótesis que cada una de las clases puede ser modelada por una distribución Gaussiana y que todas las clases usan la misma matriz de covarianza &#931<sub>k</sub>. Tales hipótesis  hacen de <em>LDA</em> un clasificador lineal.

### *Quadratic Discriminant Analysis (QDA)*
QDA es una variante de LDA en el cuál la matriz de covarianza puede ser diferente para cada una de las clases  *k, k = 1, 2, ... K*.<br>
La función de discriminante cuadrático es dada por:

$$
\delta_{k} (x) =
-\frac{1}{2}log|\Sigma_{k}| - \frac{1}{2}(x-\mu_{k})^T\Sigma_{k}^{-1}(x-\mu_{k})+log\pi_{k}

La función **QDA** es similar a **LDA** excepto por la matriz de covarianza: $\Sigma_{k}$<sup>1</sup>.

</p>

</div>

<sup>1</sup> Tomado de: <a href = https://online.stat.psu.edu/stat508/lesson/9/9.2/9.2.8>Applied Data Mining and Statiscal Learning</a>

![footer](doc/LogoFooter.png)
