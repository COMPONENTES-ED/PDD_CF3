<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido">
        <div class="titulo-principal__numero"><span>3</span></div>
        <h1>Medidas de posición</h1>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-4 my-3 h-100 j1">
          <img class="img-t img-a" src="@/assets/curso/temas/69.png" />
        </div>
        <div class="col-lg-5 my-3">
          <div class="bg17 p-3 brad">
            <p class="mb-0">
              Las <b>medidas de posición</b> son herramientas estadísticas que
              permiten dividir un conjunto de datos en partes iguales para
              identificar la ubicación de un valor en relación con el resto del
              conjunto. Estas medidas son fundamentales para describir la
              posición relativa de una observación dentro de una distribución.
              Las principales medidas de posición son los
              <b>cuartiles, deciles y percentiles</b>, que permiten dividir los
              datos en diferentes porcentajes, y también se utilizan para
              identificar valores atípicos.
            </p>
          </div>
        </div>
        <div class="col-lg-3 my-3">
          <img class="img-t img-a" src="@/assets/curso/temas/70.png" />
        </div>
      </div>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_3_1" class="titulo-segundo color-acento-botones">
          <h2>3.1&#x9;Cuartiles</h2>
        </div>
        <p>
          Los <b>cuartiles</b> dividen un conjunto de datos ordenados en cuatro
          partes iguales, de modo que cada cuartil contiene el 25 % de los
          datos. Los cuartiles son particularmente útiles para describir la
          dispersión de los datos y su distribución en el rango intercuartílico.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-5 my-3">
            <div class="bg10 brad p-4 h-100">
              <p class="mb-4"><b>Fórmula:</b></p>
              <div class="bgw p-3 brad">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span class="mb-0"
                      ><b>Primer cuartil</b> (Q<sub>1</sub>): Valor que deja por
                      debajo al 25 % de los datos.</span
                    >
                  </li>
                </ul>
              </div>
              <div class="bgw p-3 brad my-3">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span class="mb-0"
                      ><b>Segundo cuartil</b> (Q<sub>2</sub>): Valor que deja
                      por debajo al 50 % de los datos (es equivalente a la
                      mediana).</span
                    >
                  </li>
                </ul>
              </div>
              <div class="bgw p-3 brad">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span class="mb-0"
                      ><b>Tercer cuartil</b> (Q<sub>3</sub>): Valor que deja por
                      debajo al 75 % de los datos.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-4 my-3">
            <div class="bg21 brad p-4 h-100">
              <p class="mb-4"><b>Interpretación:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >Q<sub>1</sub> divide el conjunto en un 25 % de valores por
                    debajo y un 75 % por encima.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >Q<sub>2</sub>, o mediana, divide el conjunto en dos partes
                    iguales.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >Q<sub>3</sub> divide el conjunto en un 75 % de valores por
                    debajo y un 25 % por encima.</span
                  >
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-3 my-3">
            <div class="bg14 brad p-4 h-100 j1">
              <img class="img-t img-a" src="@/assets/curso/temas/71.svg" />
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_3_2" class="titulo-segundo color-acento-botones">
          <h2>3.2&#x9;Deciles</h2>
        </div>
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-8 my-3">
            <p>
              Los <b>deciles</b> dividen el conjunto de datos en diez partes
              iguales, de modo que cada decil contiene el 10 % de las
              observaciones. Son útiles para observar la posición de un valor
              dentro de una división más detallada del conjunto de datos que los
              cuartiles.
            </p>
            <div class="row justify-content-center align-items-center">
              <div class="col-lg-auto my-3">
                <img class="img-t img-a" src="@/assets/curso/temas/72.png" />
              </div>
              <div class="col my-3">
                <p class="mb-4"><b>Fórmula:</b></p>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      ><b>Primer decil</b> (D<sub>1</sub>): Valor que deja por
                      debajo al 10 % de los datos.</span
                    >
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      ><b>Segundo decil</b> (D<sub>2</sub>): Valor que deja por
                      debajo al 20 % de los datos.</span
                    >
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i><span> ... </span>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      ><b>Noveno decil</b> (D<sub>9</sub>): Valor que deja por
                      debajo al 90 % de los datos.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="bg22 brad p-4 h-100">
              <p class="mb-4"><b>Interpretación:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >Cada decil indica la posición del conjunto de datos en
                    fracciones del 10 %, proporcionando una idea más granular de
                    cómo se distribuyen los valores.</span
                  >
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4 my-3">
            <img class="img-t img-a" src="@/assets/curso/temas/73.png" />
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_3_3" class="titulo-segundo color-acento-botones">
          <h2>3.3&#x9;Percentiles</h2>
        </div>
        <p>
          Los <b>percentiles</b> dividen un conjunto de datos en cien partes
          iguales, de modo que cada percentil contiene el 1 % de las
          observaciones. Los percentiles son ampliamente utilizados en muchos
          campos, como la educación y la salud, para determinar la posición
          relativa de un individuo o una observación dentro de una población.
        </p>
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-4 my-3">
            <img class="img-t img-a" src="@/assets/curso/temas/74.png" />
          </div>
          <div class="col-lg-8 my-3">
            <p class="mb-4"><b>Fórmula:</b></p>
            <ul class="lista-ul--color fa-ul">
              <li class="mb-3">
                <i class="fas fa-check v1"></i
                ><span
                  ><b>Primer percentil (P<sub>1</sub>)</b>: Valor que deja por
                  debajo al 1 % de los datos.</span
                >
              </li>
              <li class="mb-3">
                <i class="fas fa-check v1"></i>
                <p>
                  <b>Décimo percentil (P<sub>10</sub>)</b>: Valor que deja por
                  debajo al 10 % de los datos.
                </p>
              </li>
              <li class="mb-3">
                <i class="fas fa-check v1"></i
                ><span
                  ><b></b><b>Percentil 50 (P<sub>50</sub>):</b> Es equivalente a
                  la mediana, ya que deja por debajo al 50 % de los datos.</span
                >
              </li>
              <li class="mb-3">
                <i class="fas fa-check v1"></i
                ><span
                  ><b>Percentil 90 (P<sub>90</sub>):</b> Valor que deja por
                  debajo al 90 % de los datos.</span
                >
              </li>
            </ul>
            <div class="bg7 brad p-4 h-100">
              <p class="mb-4">
                <b class="text-white">Interpretación:</b>
              </p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span class="text-white"
                    >El percentil proporciona información sobre la posición de
                    un valor respecto a un grupo más amplio. Por ejemplo, si una
                    persona se encuentra en el percentil 80 de un examen,
                    significa que su puntuación es superior a la del 80 % de los
                    participantes.</span
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_3_4" class="titulo-segundo color-acento-botones">
          <h2>3.4&#x9;Rango intercuartílico</h2>
        </div>
        <p>
          El <b>rango intercuartílico (IQR)</b> es una medida de dispersión que
          se basa en los cuartiles y representa la diferencia entre el tercer
          cuartil (Q3) y el primer cuartil (Q1). Es útil para medir la
          variabilidad de la parte central de los datos, eliminando el efecto de
          los valores extremos o atípicos.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-9 my-3">
            <div class="bg17 brad p-4 h-100">
              <p class="mb-4"><b>Fórmula:</b></p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: inline-block; margin-bottom: 2rem"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 2rem;"
                  display="block"
                >
                  <mstyle displaystyle="true">
                    <mi>I</mi>
                    <mi>Q</mi>
                    <mi>R</mi>
                    <mo>=</mo>
                    <msub>
                      <mi>Q</mi>
                      <mn>3</mn>
                    </msub>
                    <mo>−</mo>
                    <msub>
                      <mi>Q</mi>
                      <mn>1</mn>
                    </msub>
                  </mstyle>
                </math>
              </div>
              <p class="mb-4"><b>Interpretación:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >El rango intercuartílico mide la dispersión del 50 %
                    central de los datos, lo que proporciona una visión más
                    clara de cómo están distribuidos los valores centrales del
                    conjunto.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >Es menos sensible a los valores extremos que otras medidas
                    de dispersión, como la desviación estándar.</span
                  >
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-3 col-7 my-3">
            <div class="bgw brad p-4 h-100 j1">
              <img class="img-t img-a" src="@/assets/curso/temas/75.png" />
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
