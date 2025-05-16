<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido">
        <div class="titulo-principal__numero"><span>4</span></div>
        <h1>Probabilidades</h1>
      </div>
      <div class="row justify-content-center">
        <div class="col-lg-4 my-lg-0 my-3 j1">
          <img class="img-t img-a" src="@/assets/curso/temas/77.png" />
        </div>
        <div class="col-lg-5 my-lg-0 my-3">
          <div class="bg21 p-3 brad j1 h-100">
            <p class="mb-0">
              La <b>probabilidad</b> es una rama de la matemática que estudia la
              posibilidad de que ocurra un evento o fenómeno aleatorio. En
              estadística, la probabilidad permite cuantificar la incertidumbre
              asociada con los resultados de un experimento o evento,
              proporcionando una medida numérica entre 0 y 1, donde 0 indica que
              el evento no ocurrirá y 1 indica que el evento es seguro.
            </p>
          </div>
        </div>
        <div class="col-lg-3 my-lg-0 my-3 j1">
          <img class="img-t img-a" src="@/assets/curso/temas/78.png" />
        </div>
      </div>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_4_1" class="titulo-segundo color-acento-botones">
          <h2>4.1&#x9;Cálculo de probabilidades</h2>
        </div>
        <p>
          La <b>probabilidad</b> de que ocurra un evento AAA se define como la
          proporción de casos favorables entre el número total de casos
          posibles. La fórmula básica es:
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-7 my-3">
            <div class="bg21 brad p-3 h-100">
              <p class="mb-4"><b>Fórmula:</b></p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: inline-block; margin-bottom: 2rem;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 1.5rem;"
                  display="block"
                >
                  <mstyle displaystyle="true">
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>)</mo>
                    <mo>=</mo>
                    <mfrac>
                      <mtext>Número de casos favorables</mtext>
                      <mtext>Número total de casos posibles</mtext>
                    </mfrac>
                  </mstyle>
                </math>
              </div>
              <p class="mb-4"><b>Donde:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span>P(A) es la probabilidad del evento A.</span>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >El <b>número de casos favorables</b> son las situaciones
                    que cumplen la condición del evento.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >El <b>número total de casos posibles</b> incluye las
                    situaciones que podrían ocurrir.</span
                  >
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-5 my-3">
            <div class="bgw brad p-4 h-100 j1">
              <img class="img-t img-a" src="@/assets/curso/temas/79.png" />
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_4_2" class="titulo-segundo color-acento-botones">
          <h2>4.2&#x9;Probabilidades marginales</h2>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg-7 my-3">
            <p>
              Las <b>probabilidades</b> marginales se refieren a la probabilidad
              de que ocurra un solo evento sin considerar ningún otro evento. Es
              la probabilidad simple de un evento particular.
            </p>
            <div class="bg7 brad p-4">
              <ul class="lista-ul--color fa-ul mb-4">
                <li>
                  <i class="fas fa-check v1"></i
                  ><span class="text-white"
                    ><b>Ejemplo:</b> En un lanzamiento de un dado de 6 caras, la
                    probabilidad marginal de obtener un número par (eventos
                    favorables: 2, 4, 6) es:</span
                  >
                </li>
              </ul>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: inline-block; margin-bottom: 2rem;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 2rem;"
                  display="block"
                >
                  <mstyle displaystyle="true">
                    <mi>P</mi>
                    <mo>(</mo>
                    <mtext>Número par</mtext>
                    <mo>)</mo>
                    <mo>=</mo>
                    <mfrac>
                      <mn>3</mn>
                      <mn>6</mn>
                    </mfrac>
                    <mo>=</mo>
                    <mn>0.5</mn>
                  </mstyle>
                </math>
              </div>
            </div>
          </div>
          <div class="col-lg-5 my-3">
            <div class="bgw brad p-4 h-100 j1">
              <img
                class="img-t img-a"
                src="@/assets/curso/temas/82.png"
                alt=""
              />
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_4_3" class="titulo-segundo color-acento-botones">
          <h2>4.3&#x9;Regla de la adición</h2>
        </div>
        <p class="mb-4">
          La <b>regla de la adición</b> se utiliza para calcular la probabilidad
          de que ocurra uno de varios eventos. Existen dos casos:
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-4 my-lg-0 my-3 j1">
            <img class="img-t img-a" src="@/assets/curso/temas/84.png" />
          </div>
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg23  p-4 brad h-100">
              <div class="row justify-content-start mb-4">
                <p class="col-lg-auto mb-4 bg11 text-white px-3">
                  <b>Eventos mutuamente excluyentes</b>
                </p>
              </div>
              <p class="text-white">
                Son aquellos eventos que no pueden ocurrir al mismo tiempo. La
                probabilidad de que ocurra AAA o BBB es la suma de las
                probabilidades de cada evento:
              </p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: block; margin: 0 auto 2rem; width: fit-content; color:black"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 1.4rem; color:black"
                  display="block"
                >
                  <mstyle displaystyle="true">
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>∘</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                    <mo>=</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>)</mo>
                    <mo>+</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                  </mstyle>
                </math>
              </div>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3 j1">
            <div class="bg24  p-4 brad h-100">
              <div class="row justify-content-start mb-4">
                <p class="col-lg-auto mb-4 bg11 text-white px-3">
                  <b>Eventos no mutuamente excluyentes</b>
                </p>
              </div>
              <p class="text-white">
                Son eventos que pueden ocurrir juntos. En este caso, es
                necesario restar la intersección de ambos eventos:
              </p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: block; margin: 0 auto 2rem; width: fit-content; text-align: center;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 1rem; display: inline-block;"
                >
                  <mrow>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>∘</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                    <mo>=</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>)</mo>
                    <mo>+</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                    <mo>-</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>∧</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                  </mrow>
                </math>
              </div>
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_4_4" class="titulo-segundo color-acento-botones">
          <h2>4.4&#x9;Regla de la multiplicación</h2>
        </div>
        <p>
          La <b>regla de la multiplicación </b> se utiliza para calcular la
          probabilidad de que ocurran dos o más eventos de manera conjunta
          (intersección de eventos). Existen dos casos:
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg17 p-4 brad h-100">
              <div class="row justify-content-start mb-4">
                <p class="col-lg-auto mb-2 bg11 text-white px-3">
                  <b>Eventos independientes</b>
                </p>
              </div>
              <p>
                Si los eventos no afectan la probabilidad del otro, la
                probabilidad conjunta de que ocurra AAA y BBB es:
              </p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: block; margin: 0 auto 2rem; width: fit-content; text-align: center;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 1.2rem; display: inline-block;"
                >
                  <mrow>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>∩</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                    <mo>=</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>)</mo>
                    <mo>×</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                  </mrow>
                </math>
              </div>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg7  p-4 brad h-100">
              <div class="row justify-content-start mb-4">
                <p class="col-lg-auto mb-2 bg11 text-white px-3">
                  <b>Eventos dependientes</b>
                </p>
              </div>
              <p class="text-white">
                Si los eventos están relacionados, la probabilidad conjunta se
                calcula:
              </p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: block; margin: 0 auto 2rem; width: fit-content; text-align: center;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 1.2rem; display: inline-block;"
                >
                  <mrow>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>∨</mo>
                    <mi>B</mi>
                    <mo>)</mo>
                    <mo>=</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>A</mi>
                    <mo>)</mo>
                    <mo>×</mo>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>B</mi>
                    <mo>|</mo>
                    <mi>A</mi>
                    <mo>)</mo>
                  </mrow>
                </math>
              </div>
              <p class="text-white">
                Donde P(B|A) es la probabilidad de que ocurra B dado que ya
                ocurrió A.
              </p>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3 j1">
            <img class="img-t img-a" src="@/assets/curso/temas/87.png" />
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_4_5" class="titulo-segundo color-acento-botones">
          <h2>4.5&#x9;Teorema de Bayes</h2>
        </div>
        <p>
          El <b>teorema de Bayes</b> es una fórmula que describe la probabilidad
          de que ocurra un evento AAA, dado que ya ha ocurrido otro evento BBB.
          Este teorema es útil cuando se tiene información condicional sobre la
          probabilidad de un evento y se desea actualizar esa probabilidad a la
          luz de nueva información.
        </p>
        <div class="row justify-content-center mb-4">
          <div class="col-lg-3 my-lg-0 my-3 j1">
            <img class="img-t img-a" src="@/assets/curso/temas/88.png" />
          </div>
          <div class="col-lg-7 my-lg-0 my-3">
            <div class="bg25 brad p-3 h-100">
              <p class="mb-4"><b>Fórmula:</b></p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: block; margin: 0 auto 2rem; width: fit-content; text-align: center;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 2rem; display: inline-block;"
                >
                  <mrow>
                    <mi>P</mi>
                    <mo>(</mo>
                    <mi>B</mi>
                    <mo>|</mo>
                    <mi>A</mi>
                    <mo>)</mo>
                    <mo>=</mo>
                    <mfrac>
                      <mrow>
                        <mi>P</mi>
                        <mo>(</mo>
                        <mi>B</mi>
                        <mo>|</mo>
                        <mi>A</mi>
                        <mo>)</mo>
                        <mo>×</mo>
                        <mi>P</mi>
                        <mo>(</mo>
                        <mi>A</mi>
                        <mo>)</mo>
                      </mrow>
                      <mrow>
                        <mi>P</mi>
                        <mo>(</mo>
                        <mi>B</mi>
                        <mo>)</mo>
                      </mrow>
                    </mfrac>
                  </mrow>
                </math>
              </div>
              <p class="mb-4"><b>Donde:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span>P(B|A) es la probabilidad de A dado B.</span>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span>P(A|B) es la probabilidad de B dado A.</span>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >P(A) y P(B) son las probabilidades marginales de A y B,
                    respectivamente.</span
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div class="row justify-content-start mb-5">
          <div class="col-auto">
            <div class="list">
              <div class="list__item">
                <div class="list__item__icon">
                  <img src="@/assets/curso/temas/icon.svg" alt="" />
                </div>
              </div>
              <div class="list__txt bgicon brad p-0 px-4 text-white">
                <h4 class="mb-0">Distribución de probabilidades</h4>
              </div>
            </div>
          </div>
        </div>
        <p class="mb-4">
          Una <b>distribución de probabilidades</b> describe cómo se distribuyen
          las probabilidades entre los diferentes resultados de un experimento
          aleatorio. Hay diferentes tipos de distribuciones de probabilidad,
          según el tipo de variable (discreta o continua) y el contexto del
          problema.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg15 p-4 brad h-100">
              <img class="img-t img-a mb-4" src="@/assets/curso/temas/90.png" />
              <div class="row justify-content-center mb-4">
                <p class="col-lg-auto mb-2 bg26 px-3">
                  <b>Distribución de probabilidad discreta</b>
                </p>
              </div>
              <p>
                Describe la probabilidad de que una variable aleatoria discreta
                tome ciertos valores. Ejemplos incluyen la distribución binomial
                o la distribución de Poisson.
              </p>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg15 p-4 brad h-100">
              <img class="img-t img-a mb-4" src="@/assets/curso/temas/91.png" />
              <div class="row justify-content-center mb-4">
                <p class="col-lg-auto mb-2 bg26 px-3">
                  <b>Distribución de probabilidad discreta</b>
                </p>
              </div>
              <p>
                Describe la probabilidad de que una variable aleatoria continua
                caiga dentro de un rango de valores. Ejemplos incluyen la
                distribución normal y la distribución uniforme.
              </p>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3 j1">
            <img class="img-t img-a" src="@/assets/curso/temas/92.png" />
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_4_6" class="titulo-segundo color-acento-botones">
          <h2>4.6&#x9;Distribución normal</h2>
        </div>
        <p class="mb-5">
          La <b>distribución normal</b>, también conocida como campana de Gauss,
          es una de las distribuciones de probabilidad más importantes en
          estadística. Muchos fenómenos naturales y sociales siguen una
          distribución normal. Está completamente definida por dos parámetros:
          la media (&mu;\mu&mu;) y la desviación estándar
          (&sigma;\sigma&sigma;).
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-8 my-lg-0 my-3">
            <div class="bg19 br-d brad p-3 h-100">
              <div class="row justify-content-center">
                <div class="col-lg-3 my-lg-0 my-3 j1">
                  <img class="img-t img-a" src="@/assets/curso/temas/93.png" />
                </div>
                <div class="col-lg-9 my-lg-0 my-3">
                  <div>
                    <p><b>Características:</b></p>
                    <ul class="lista-ul--color fa-ul">
                      <li class="mb-3">
                        <i class="fas fa-check v1"></i
                        ><span>Es simétrica respecto a la media.</span>
                      </li>
                      <li class="mb-3">
                        <i class="fas fa-check v1"></i
                        ><span
                          >La media, la mediana y la moda son iguales.</span
                        >
                      </li>
                      <li class="mb-3">
                        <i class="fas fa-check v1"></i
                        ><span
                          >Aproximadamente el 68 % de los datos se encuentra
                          dentro de una desviación estándar de la media, el 95 %
                          dentro de dos desviaciones estándar, y el 99.7 %
                          dentro de tres desviaciones estándar (regla
                          empírica).</span
                        >
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="col-lg-2 my-lg-0 my-3 j1">
            <img class="img-t img-a" src="@/assets/curso/temas/94.png" />
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_4_7" class="titulo-segundo color-acento-botones">
          <h2>4.7&#x9;Distribución <em>t-student</em></h2>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg-3 my-lg-0 my-3 j1">
            <img class="img-t img-a" src="@/assets/curso/temas/95.png" />
          </div>
          <div class="col-lg-9 my-lg-0 my-3">
            <p>
              La <b>distribución <em>t-student</em></b> se utiliza cuando el
              tama&ntilde;o de la muestra es peque&ntilde;o y la desviación
              estándar de la población es desconocida. Es similar a la
              distribución normal, pero con colas más gruesas, lo que refleja
              una mayor probabilidad de valores extremos.
            </p>
            <div class="bg17 br-d brad p-4">
              <p class="mb-4"><b>Aplicaciones:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >La distribución t se utiliza principalmente en pruebas de
                    hipótesis, como la prueba t, cuando se trabaja con muestras
                    peque&ntilde;as (generalmente n &lt; 30n &lt; 30n &lt;
                    30).</span
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
        <div id="t_4_8" class="titulo-segundo color-acento-botones">
          <h2>4.8&#x9;Prueba de valor z</h2>
        </div>
        <p>
          La <b>prueba de valor z</b> es una técnica estadística que permite
          calcular la probabilidad de que una observación en particular esté
          alejada de la media de un conjunto de datos, medida en unidades de
          desviación estándar.
        </p>
        <div class="row justify-content-center mb-4">
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg27 brad p-3 h-100 j1">
              <img class="img-t img-a" src="@/assets/curso/temas/97.png" />
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg25 brad p-3 h-100">
              <p class="mb-4"><b>Fórmula:</b></p>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: block; margin: 0 auto 2rem; width: fit-content; text-align: center;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 2rem; display: inline-block;"
                >
                  <mrow>
                    <mi>z</mi>
                    <mo>=</mo>
                    <mfrac>
                      <mrow>
                        <mi>x</mi>
                        <mo>-</mo>
                        <mi>μ</mi>
                      </mrow>
                      <mi>σ</mi>
                    </mfrac>
                  </mrow>
                </math>
              </div>
              <p class="mb-4"><b>Donde:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i>
                  <p>x es el valor de la observación.</p>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i>
                  <p>&mu; es la media de la población.</p>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i>
                  <p>
                    &sigma; es la desviación estándar de la población.
                  </p>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg21 brad p-3 h-100">
              <p class="mb-4"><b>Interpretación:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i>
                  <p>
                    Un valor z positivo indica que el valor está por encima de
                    la media.
                  </p>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i>
                  <p>
                    Un valor z negativo indica que el valor está por debajo de
                    la media.
                  </p>
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
        <div id="t_4_9" class="titulo-segundo color-acento-botones">
          <h2>
            4.9&#x9;Aplicaciones de la probabilidad en el análisis estadístico
          </h2>
        </div>
        <p class="mb-4">
          La probabilidad se utiliza en una amplia variedad de aplicaciones en
          el análisis estadístico, desde la estimación de probabilidades de
          eventos simples hasta la toma de decisiones basada en información
          incompleta o incierta. Algunos ejemplos de uso incluyen:
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg15 p-4 brad h-100">
              <img class="img-t img-a mb-4" src="@/assets/curso/temas/98.png" />
              <div class="row justify-content-center mb-4">
                <p class="col-lg-auto mb-2 bg26 px-3">
                  <b>Pruebas de hipótesis</b>
                </p>
              </div>
              <p>
                Se utilizan probabilidades para evaluar si una hipótesis es
                válida o no, con base en la evidencia de los datos muestrales.
              </p>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg15 p-4 brad h-100">
              <img class="img-t img-a mb-4" src="@/assets/curso/temas/99.png" />
              <div class="row justify-content-center mb-4">
                <p class="col-lg-auto mb-2 bg26 px-3">
                  <b>Modelos predictivos</b>
                </p>
              </div>
              <p>
                La probabilidad es fundamental en modelos predictivos, como el
                análisis de regresión y las redes bayesianas, donde se calcula
                la probabilidad de resultados futuros con base en datos
                históricos.
              </p>
            </div>
          </div>
          <div class="col-lg-4 my-lg-0 my-3">
            <div class="bg15 p-4 brad h-100">
              <img
                class="img-t img-a mb-4"
                src="@/assets/curso/temas/100.png"
              />
              <div class="row justify-content-center mb-4">
                <p class="col-lg-auto mb-2 bg26 px-3">
                  <b>Toma de decisiones</b>
                </p>
              </div>
              <p>
                En la teoría de la decisión, se usan probabilidades para evaluar
                el riesgo y la incertidumbre en situaciones donde se deben tomar
                decisiones, como en inversiones o análisis de riesgos.
              </p>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema5',
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
