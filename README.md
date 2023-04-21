![header](doc/LogoHeader.png)

# Analisis matematico

#### Authors

Juan Ignacio Iribet 
Mariana Taglio 
FS 
2023

<div style="text-align: justify">
<p>En este repositorio se podrán encontrar los ejercicios resueltos de la materia <strong> Análisis Matemático</strong>.  Este trabajo práctico consistió en la resolución de problemas prácticos y teóricos vinculados con <em> Linear and Quadratic Discriminat Analysis (LDA y QDA respectivamente)</em> y nociones de <em>redes neuronales</em>. Para visualizar la resolución de los ejercicios propuestos y las respuestas a las preguntas teóricas abrir el archivo <mark><em>tp_final.ipnybn</em> </mark>.
<h4><em> Linear Discriminant Analysis (LDA)</em></h4>
Es un método basado en la hipótesis que cada una de las clases puede ser modelada por una distribución Gaussiana y que todas las clases usan la misma matriz de covarianza &#931<sub>k</sub>. Tales hipótesis  hacen de <em>LDA</em> un clasificador lineal.

<h4><em> Quadratic Discriminant Analysis (QDA)</em></h4>
QDA es una variante de LDA en el cuál la matriz de covarianza puede ser diferente para cada una de las clases  <em>k, k = 1, 2, ... K</em>.<br>
La función de discriminante cuadrático es dada por:
</p>
</div>

$$
\delta_{k} (x) =
-\frac{1}{2}log|\Sigma_{k}| - \frac{1}{2}(x-\mu_{k})^T\Sigma_{k}^{-1}(x-\mu_{k})+log\pi_{k}

<div style="text-align: justify">
    <p>
    La función <em>QDA</em> es similar a <em>LDA</em> excepto por la matriz de covarianza: &#931<sub>k</sub> <sup>1</sup>
    </p>
</div>

</p>

</div>

<sup>1</sup> Tomado de: <a href = https://online.stat.psu.edu/stat508/lesson/9/9.2/9.2.8>Applied Data Mining and Statiscal Learning</a>

![footer](doc/LogoFooter.png)
