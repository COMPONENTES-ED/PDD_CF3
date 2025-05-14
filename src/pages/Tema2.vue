<template>
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido">
        <div class="titulo-principal__numero"><span>2</span></div>
        <h1>Medidas de dispersión</h1>
      </div>
      <div class="row justify-content-center align-items-center mb-5">
        <div class="col-lg-auto">
          <img class="img-a img-t" src="@/assets/curso/temas/33.png" alt="" />
        </div>
        <div class="col pt-lg-0 pt-md-4">
          <p class="mb-0">
            Las <b>medidas de dispersion</b> son herramientas estadísticas que
            describen quí tan dispersos o esparcidos estín los datos en un
            conjunto. Estas medidas indican la variabilidad de los datos
            alrededor de una medida de tendencia central, como la media o la
            mediana. Cuanto mayor sea la dispersion, mís lejos estarín los datos
            de la tendencia central, lo que refleja una mayor variabilidad en el
            conjunto de datos.
          </p>
        </div>
      </div>
      <div class="row justify-content-center align-items-center">
        <div class="col-lg-5 my-3">
          <div class="titulo-sexto color-acento-contenido aos-init">
            <h5>Figura 2.</h5>
            <span>Medidas de dispersion.</span>
          </div>
          <img
            class="contions mx-auto aos-init img-t bg-img"
            src="@/assets/curso/temas/34.svg"
            alt="La Figura 2 se denomina «Medidas de dispersión», y muestra las diferentes medidas que indican la variabilidad de los datos alrededor de una medida de tendencia central."
          />
          <figcaption
            class="border border-secundary border-start-0 border-end-0 border-2 mt-2"
          >
            <p class="text-center text-dark mb-0">Fuente: OIT, 2024.</p>
          </figcaption>
        </div>
        <div class="col-lg-5 my-3">
          <img class="img-a img-t" src="@/assets/curso/temas/35.png" />
        </div>
      </div>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_2_1" class="titulo-segundo color-acento-botones">
          <h2>2.1&#x9;Rango</h2>
        </div>
        <p>
          El <b>rango</b> es la diferencia entre el valor mís alto y el mís bajo
          en un conjunto de datos. Es la medida de dispersion mís simple y se
          usa para describir la amplitud total de los valores observados.
        </p>
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-5 col-7 my-3">
            <img class="img-t img-a" src="@/assets/curso/temas/36.png" />
          </div>
          <div class="col-lg-7 my-3">
            <h5>Fórmula:</h5>
            <math
              xmlns="http://www.w3.org/1998/Math/MathML"
              style="font-size: 2rem"
            >
              <mrow>
                <mi>R</mi>
                <mo>=</mo>
                <msub>
                  <mi>x</mi>
                  <mi>max</mi>
                </msub>
                <mo>−</mo>
                <msub>
                  <mi>x</mi>
                  <mi>min</mi>
                </msub>
              </mrow>
            </math>
            <div class="brad p-3 h-100">
              <p class="mb-3"><b>Donde:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">x<sub>max</sub></div>
                    <div class="col">
                      <p class="mb-0">
                        es el valor míximo del conjunto de datos.
                      </p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">x<sub>min</sub></div>
                    <div class="col">
                      <p class="mb-0">
                        es el valor mínimo del conjunto de datos.
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
            <div class="bg7 brad p-3 h-100">
              <p class="mb-3"><b class="text-white">Propiedades</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span class="text-white"
                    >Es fícil de calcular, pero es muy sensible a los valores
                    atípicos, ya que solo depende de los extremos.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span class="text-white"
                    >No proporciona informacion sobre como se distribuyen los
                    datos entre los valores mís altos y bajos.</span
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
        <div id="t_2_2" class="titulo-segundo color-acento-botones">
          <h2>2.2&#x9;Desviacion media</h2>
        </div>
        <p>
          La<b>desviacion media</b> es la media de las diferencias absolutas
          entre cada valor del conjunto de datos y la media aritmítica.
          Proporciona una medida del promedio de la dispersion sin considerar la
          direccion de las desviaciones.
        </p>
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-4 col-7 my-3">
            <img class="img-t img-a" src="@/assets/curso/temas/42.png" />
          </div>
          <div class="col-lg-8 my-3">
            <h5>Fórmula:</h5>
            <div
              style="border: 2px solid green; background-color: white; display: inline-block; padding: 10px;"
            >
              <math
                xmlns="http://www.w3.org/1998/Math/MathML"
                style="font-size: 2rem"
              >
                <mrow>
                  <mtext>Desviación media</mtext>
                  <mo>=</mo>
                  <mfrac>
                    <mrow>
                      <munderover>
                        <mo>&#x2211;</mo>
                        <mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow>
                        <mi>n</mi>
                      </munderover>
                      <mo>|</mo>
                      <msub><mi>x</mi><mi>i</mi></msub>
                      <mo>−</mo>
                      <mover><mi>x</mi><mo>&#xAF;</mo></mover>
                      <mo>|</mo>
                    </mrow>
                    <mi>n</mi>
                  </mfrac>
                </mrow>
              </math>
            </div>
            <div class="brad p-3 h-100">
              <p class="mb-3"><b>Donde:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <msub>
                          <mi>x</mi>
                          <mi>i</mi>
                        </msub>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">es cada valor del conjunto de datos.</p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <mover>
                          <mi>x</mi>
                          <mo>¯</mo>
                        </mover>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">es la media aritmítica.</p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <mi>n</mi>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">
                        es el número total de observaciones.
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
            <div class="bgi brad p-3 h-100">
              <p class="mb-3"><b>Propiedades</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span
                    >Es una medida intuitiva de la dispersion, pero no es tan
                    común como otras medidas como la varianza o la desviacion
                    estíndar.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span
                    >Utiliza las desviaciones absolutas, lo que evita que las
                    diferencias positivas y negativas se cancelen entre
                    sí.</span
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
        <div id="t_2_3" class="titulo-segundo color-acento-botones">
          <h2>2.3&#x9;Varianza</h2>
        </div>
        <p class="mb-5">
          La <b>varianza</b> es una medida que refleja el promedio de los
          cuadrados de las desviaciones de cada valor respecto a la media. La
          varianza indica quí tan dispersos estín los datos, y es una de las
          medidas mís importantes en la estadística inferencial.
        </p>
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-4 my-3 bg17 p-3 brad">
            <h5>Fórmula:</h5>
            <div
              style="border: 2px solid green; background-color: white; display: inline-block; padding: 10px;"
            >
              <math
                xmlns="http://www.w3.org/1998/Math/MathML"
                style="font-size: 1.2rem"
              >
                <mrow>
                  <mtext>Varianza</mtext>
                  <mo>=</mo>
                  <msup><mi>&#x03C3;</mi><mn>2</mn></msup>
                  <mo>=</mo>
                  <mfrac>
                    <mrow>
                      <munderover>
                        <mo>&#x2211;</mo>
                        <mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow>
                        <mi>n</mi>
                      </munderover>
                      <msup>
                        <mrow>
                          <mo>(</mo>
                          <msub><mi>x</mi><mi>i</mi></msub>
                          <mo>−</mo>
                          <mover><mi>x</mi><mo>¯</mo></mover>
                          <mo>)</mo>
                        </mrow>
                        <mn>2</mn>
                      </msup>
                    </mrow>
                    <mi>n</mi>
                  </mfrac>
                </mrow>
              </math>
            </div>

            <div class="brad p-3 h-100">
              <p class="mb-3"><b>Donde:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <msub><mi>x</mi><mi>i</mi></msub>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">es cada valor del conjunto de datos.</p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <mover><mi>x</mi><mo>¯</mo></mover>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">es la media aritmítica.</p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <mi>n</mi>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">
                        es el número total de observaciones.
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-5 my-3">
            <div>
              <p class="mb-3"><b>Propiedades</b></p>
              <div class="bg18 p-3 brad mb-3">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i
                    ><span
                      >La varianza utiliza los cuadrados de las desviaciones, lo
                      que magnifica el impacto de las observaciones mís alejadas
                      de la media.</span
                    >
                  </li>
                </ul>
              </div>
              <div class="bg18 p-3 brad">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i
                    ><span
                      >Es muy útil para cílculos estadísticos avanzados, pero su
                      principal desventaja es que estí en unidades cuadradas, lo
                      que puede hacer que sea difícil de interpretar
                      directamente.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-3 col-7 my-3">
            <img class="img-t img-a" src="@/assets/curso/temas/51.png" />
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_2_4" class="titulo-segundo color-acento-botones">
          <h2>2.4&#x9;Desviacion estíndar</h2>
        </div>
        <p class="mb-5">
          La <b>desviacion estíndar</b> es la raíz cuadrada positiva de la
          varianza y es quizís la medida de dispersion mís utilizada. A
          diferencia de la varianza, la desviacion estíndar estí en las mismas
          unidades que los datos originales, lo que facilita su interpretacion.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-3 col-7 my-3">
            <img class="img-t img-a" src="@/assets/curso/temas/52.png" />
          </div>
          <div class="col-lg-5 my-3">
            <div class="bg17 p-3 brad h-100">
              <h5>Fórmula:</h5>
              <div
                style="border: 2px solid green; background-color: white; display: inline-block; padding: 10px;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 2rem"
                >
                  <mrow>
                    <mi>&#x03C3;</mi>
                    <mo>=</mo>
                    <msqrt>
                      <mfrac>
                        <mrow>
                          <munderover>
                            <mo>&#x2211;</mo>
                            <mrow><mi>i</mi><mo>=</mo><mn>1</mn></mrow>
                            <mi>n</mi>
                          </munderover>
                          <msup>
                            <mrow>
                              <mo>(</mo>
                              <msub><mi>x</mi><mi>i</mi></msub>
                              <mo>−</mo>
                              <mover><mi>x</mi><mo>¯</mo></mover>
                              <mo>)</mo>
                            </mrow>
                            <mn>2</mn>
                          </msup>
                        </mrow>
                        <mi>n</mi>
                      </mfrac>
                    </msqrt>
                  </mrow>
                </math>
              </div>

              <div class="brad p-3 h-100">
                <p class="mb-3"><b>Donde:</b></p>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem"
                        >
                          <mi>&#x03C3;</mi>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">
                          es la desviacion estíndar.
                        </p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem"
                        >
                          <msub><mi>x</mi><mi>i</mi></msub>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">es cada valor del conjunto de datos.</p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem"
                        >
                          <mover><mi>x</mi><mo>¯</mo></mover>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">es la media aritmítica.</p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem"
                        >
                          <mi>n</mi>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">
                          es el número total de observaciones.
                        </p>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-4 my-3">
            <div class="bg19 p-3 brad h-100">
              <p class="mb-3"><b>Propiedades</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span
                    >Indica quí tan dispersos estín los valores con respecto a
                    la media.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span
                    >Es fícil de interpretar porque estí en las mismas unidades
                    que los datos originales.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span
                    >Es sensible a los valores atípicos, ya que utiliza las
                    desviaciones cuadradas.</span
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
        <div id="t_2_5" class="titulo-segundo color-acento-botones">
          <h2>2.5&#x9;Coeficiente de variacion</h2>
        </div>
        <p class="mb-5">
          El <b>coeficiente de variacion (CV)</b> es una medida de dispersion
          relativa que expresa la desviacion estíndar como un porcentaje de la
          media. Es útil para comparar la variabilidad entre diferentes
          conjuntos de datos que pueden tener diferentes unidades o medias.
        </p>
        <div class="row justify-content-center bg20 brad">
          <div class="col-lg-3 p-0">
            <img
              class="img-t d-lg-block d-none"
              src="@/assets/curso/temas/58.png"
            />
          </div>
          <div class="col-lg-4 my-3 my-lg-0 py-3">
            <div>
              <h5>Fórmula:</h5>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: inline-block; margin-bottom: 20px;"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 2rem;"
                >
                  <mi>C</mi>
                  <mi>V</mi>
                  <mo>=</mo>
                  <mfrac>
                    <mi>σ</mi>
                    <mover>
                      <mi>x</mi>
                      <mo>¯</mo>
                    </mover>
                  </mfrac>
                  <mo>×</mo>
                  <mn>100</mn>
                </math>
              </div>
              <div class="brad p-3 h-100">
                <p class="mb-3"><b>Donde:</b></p>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem;"
                        >
                          <mi>σ</mi>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">
                          es la desviacion estíndar.
                        </p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem;"
                        >
                          <mover>
                            <mi>x</mi>
                            <mo>¯</mo>
                          </mover>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">es cada valor del conjunto de datos.</p>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-5 my-3 my-lg-0 py-3">
            <div class="bg19 p-3 brad h-100">
              <p class="mb-3"><b>Propiedades</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span
                    >Permite comparar la dispersion de diferentes conjuntos de
                    datos, incluso cuando tienen unidades o escalas
                    diferentes.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i
                  ><span
                    >Un coeficiente de variacion mís alto indica una mayor
                    dispersion en relacion con la media.</span
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
        <div id="t_2_6" class="titulo-segundo color-acento-botones">
          <h2>2.6&#x9;Rango intercuartílico</h2>
        </div>
        <div class="row justify-content-center align-items-center mb-5">
          <div class="col-lg-auto">
            <img class="img-a img-t" src="@/assets/curso/temas/62.png" alt="" />
          </div>
          <div class="col pt-lg-0 pt-md-4">
            <p class="mb-0">
              El <b>rango intercuartílico (IQR)</b> mide la dispersion de los
              datos entre el primer cuartil (Q1Q_1Q1) y el tercer cuartil
              (Q3Q_3Q3), es decir, la dispersion del 50 % central de los datos.
              Es una medida robusta de dispersion, ya que no se ve afectada por
              valores atípicos.
            </p>
          </div>
        </div>
        <div class="row justify-content-center align-items-center">
          <div class="col-lg-5 my-3 bg17 p-3 brad">
            <h5>Fórmula:</h5>
            <div
              style="border: 2px solid green; background: white; padding: 10px; display: inline-block; margin-bottom: 15px;"
            >
              <math
                xmlns="http://www.w3.org/1998/Math/MathML"
                style="font-size: 2rem;"
              >
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
              </math>
            </div>
            <div class="brad p-3 h-100">
              <p class="mb-3"><b>Donde:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem;"
                      >
                        <msub>
                          <mi>Q</mi>
                          <mn>3</mn>
                        </msub>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">
                        es el tercer cuartil (75 % de los datos por debajo).
                      </p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem;"
                      >
                        <msub>
                          <mi>Q</mi>
                          <mn>1</mn>
                        </msub>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">
                        es el primer cuartil (25 % de los datos por debajo).
                      </p>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
          </div>
          <div class="col-lg-7 my-3">
            <div>
              <p class="mb-3"><b>Propiedades</b></p>
              <div class="bg18 p-3 brad mb-3">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i
                    ><span
                      >El rango intercuartílico es mís robusto que la varianza o
                      la desviacion estíndar, ya que excluye los extremos.</span
                    >
                  </li>
                </ul>
              </div>
              <div class="bg18 p-3 brad">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i
                    ><span
                      >Es útil cuando se quiere analizar la dispersion central
                      sin la influencia de valores extremos o atípicos.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_2_7" class="titulo-segundo color-acento-botones">
          <h2>2.7&#x9;Amplitud de variacion</h2>
        </div>
        <p class="mb-5">
          La <b>amplitud de variacion</b> (rango total) es otra forma de medir
          la dispersion, y representa la diferencia entre el valor míximo y el
          mínimo de un conjunto de datos.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-7 my-3 order-1">
            <div class="bg7 brad p-4">
              <h5 class="text-white">Fórmula:</h5>
              <div
                style="border: 2px solid green; background: white; padding: 10px; display: inline-block;"
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
              <p class="mb-4 text-white"><b>Propiedades:</b></p>
              <div class="bgw p-3 brad mb-3">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i
                    ><span class="mb-0"
                      >Es una medida simple que ofrece una indicacion rípida de
                      la variabilidad.</span
                    >
                  </li>
                </ul>
              </div>
              <div class="bgw p-3 brad">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"> </i
                    ><span class="mb-0"
                      >No toma en cuenta como se distribuyen los datos entre el
                      valor míximo y el mínimo.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-5 my-3 order-lg-2">
            <div>
              <img
                class="img-a img-t"
                src="@/assets/curso/temas/67.png"
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
        <div id="t_2_8" class="titulo-segundo color-acento-botones">
          <h2>2.8&#x9;Coeficiente de variacion</h2>
        </div>
      </section>
      <div
        class="bloque-texto-g bloque-texto-g--inverso color-acento-botones p-3 p-sm-4 p-md-5"
      >
        <div
          class="bloque-texto-g__img"
          :style="{
            'background-image': `url(${require('@/assets/curso/temas/68.png')})`,
          }"
        ></div>
        <div class="bloque-texto-g__texto p-4">
          <p class="mb-0">
            El coeficiente de variacion es una medida que estandariza la
            desviacion estíndar respecto a la media, expresando la dispersion en
            tírminos porcentuales.
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Tema2',
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
