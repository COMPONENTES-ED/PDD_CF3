<template lenguaje="pug">
  <div class="curso-main-container pb-3">
    <BannerInterno></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5 mb-5">
      <div class="titulo-principal color-acento-contenido">
        <div class="titulo-principal__numero"><span>1</span></div>
        <h1>Medidas de tendencia central</h1>
      </div>
      <p>
        Las medidas de tendencia central son valores que resumen un conjunto de
        datos, indicando el punto central o típico alrededor del cual los datos
        tienden a agruparse. Estas medidas proporcionan información sobre la
        distribución de los datos y permiten describir el comportamiento general
        de la muestra o población.
      </p>
      <div class="row justify-content-center align-items-center">
        <div class="col-lg-5 my-3">
          <div class="titulo-sexto color-acento-contenido aos-init">
            <h5>Figura 1.</h5>
            <span>Medidas de tendencia central</span>
          </div>
          <img
            class="contions mx-auto aos-init img-t bg-img"
            src="@/assets/curso/temas/figura1.svg"
            alt="La Figura 1 se denomina «Medidas de tendencia central», y muestra las diferentes medidas que proporcionan información sobre la distribución de los datos y permiten describir el comportamiento general de la muestra o población."
          />
          <figcaption
            class="border border-secundary border-start-0 border-end-0 border-2 mt-2"
          >
            <p class="text-center text-dark mb-0">Fuente: OIT, 2024.</p>
          </figcaption>
        </div>
        <div class="col-lg-5 my-3">
          <img class="img-a img-t" src="@/assets/curso/temas/4.png" />
        </div>
      </div>
      <Separador> </Separador>
      <div id="t_1_1" class="titulo-segundo color-acento-botones">
        <h2>1.1 Media aritmética</h2>
      </div>
      <p class="mb-5">
        La <b>media aritmética</b>, también conocida simplemente como media, es
        la medida de tendencia central más utilizada. Se calcula sumando todos
        los valores de los datos y dividiendo el resultado entre el número total
        de observaciones. La media es especialmente útil cuando los datos están
        distribuidos de manera simétrica, ya que refleja el valor promedio del
        conjunto.
      </p>
      <div class="row justify-content-center align-items-center">
        <div class="col-lg-3 my-3">
          <img
            class="img-t img-a d-lg-block d-none"
            src="@/assets/curso/temas/5.png"
          />
        </div>
        <div class="col-lg-7 my-3">
          <h5>Formula:</h5>
          <math
            xmlns="http://www.w3.org/1998/Math/MathML"
            style="font-size: 3rem"
          >
            <mrow>
              <mover>
                <mi>x</mi>
                <mo>¯</mo>
              </mover>
              <mo>=</mo>
              <mfrac>
                <mrow>
                  <munderover>
                    <mo>∑</mo>
                    <mrow>
                      <mi>i</mi>
                      <mo>=</mo>
                      <mn>1</mn>
                    </mrow>
                    <mi>n</mi>
                  </munderover>
                  <msub>
                    <mi>x</mi>
                    <mi>i</mi>
                  </msub>
                </mrow>
                <mi>n</mi>
              </mfrac>
            </mrow>
          </math>
          <div class="brad p-3 h-100">
            <div class="mb-3">
              <b>Donde:</b>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"> </i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <mrow>
                          <mover>
                            <mi>x</mi>
                            <mo>¯</mo>
                          </mover>
                        </mrow>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">es la medida aritmética.</p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <mrow>
                          <msub>
                            <mi>x</mi>
                            <mi>i</mi>
                          </msub>
                        </mrow>
                      </math>
                    </div>
                    <div class="col">
                      <p class="mb-0">
                        representa cada uno de los valores del conjunto de
                        datos.
                      </p>
                    </div>
                  </div>
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i>
                  <div class="row justify-content-center align-items-center">
                    <div class="col-auto">
                      <math
                        xmlns="http://www.w3.org/1998/Math/MathML"
                        style="font-size: 2rem"
                      >
                        <mrow>
                          <mi>n</mi>
                        </mrow>
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
          <div class="bg9 brad p-3 h-100">
            <p class="mb-3"><b>Propiedades</b></p>
            <ul class="lista-ul--color fa-ul">
              <li class="mb-3">
                <i class="fas fa-check v1"></i
                ><span>Es fácil de calcular y comprender.</span>
              </li>
              <li class="mb-3">
                <i class="fas fa-check v1"></i
                ><span
                  >Afectada por valores atípicos (<em>outliers</em>), lo que
                  puede distorsionar la interpretación.</span
                >
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_1_2" class="titulo-segundo color-acento-botones">
          <h2>1.2&#x9;Mediana</h2>
        </div>
        <div class="row justify-content-center align-items-center mb-5">
          <div class="col-lg-auto">
            <img
              class="img-a img-t mb-lg-0 mb-3"
              src="@/assets/curso/temas/9.png"
              alt=""
            />
          </div>
          <div class="col pt-lg-0 pt-md-4">
            <p class="mb-0">
              La <b>mediana</b> es el valor central de un conjunto de datos
              ordenado de menor a mayor. Divide el conjunto de datos en dos
              partes iguales, de tal manera que el 50 % de las observaciones son
              menores o iguales a la mediana, y el 50 % son mayores o iguales a
              ella. A diferencia de la media, la mediana no se ve afectada por
              valores atípicos, lo que la convierte en una medida más robusta en
              distribuciones asimétricas.
            </p>
            <p></p>
          </div>
        </div>
        <div class="mb-5">
          <div class="row justify-content-center">
            <div class="col-lg-4 my-3">
              <div class="bg10 brad p-4 h-100">
                <img
                  class="img-t img-a mb-4"
                  src="@/assets/curso/temas/10.png"
                />
                <div class="row justify-content-center mb-4">
                  <p class="col-lg-auto mb-4 bg11 text-white px-4 text-center">
                    <b>Cálculo:</b>
                  </p>
                </div>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Si el número de observaciones es impar, la mediana es el
                      valor que ocupa la posición central.</span
                    >
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Si el número de observaciones es par, la mediana es el
                      promedio de los dos valores centrales.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-4 my-3">
              <div class="bg10 brad p-4 h-100">
                <img
                  class="img-t img-a mb-4"
                  src="@/assets/curso/temas/11.png"
                />
                <div class="row justify-content-center mb-4">
                  <p
                    class="col-lg-auto mb-4 bg11 text-white px-4 &lt;p class="
                    mb-4=""
                    bg4=""
                  >
                    <b>Propiedades:</b>
                  </p>
                </div>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span>No está afectada por valores extremos.</span>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Es útil para distribuciones sesgadas, ya que ofrece una
                      representación más precisa del valor central.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-4 my-3">
              <div class="bg13 brad p-4 h-100">
                <img class="img-t img-a" src="@/assets/curso/temas/12.svg" />
              </div>
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_1_3" class="titulo-segundo color-acento-botones">
          <h2>1.3&#x9;Moda</h2>
        </div>
        <div class="row justify-content-center">
          <div class="col-lg-8 my-3 order-1">
            <p>
              La <b>moda</b> es el valor o los valores que más se repiten en un
              conjunto de datos. Es útil cuando se desea identificar el valor
              más frecuente en la distribución. Puede haber distribuciones
              <b>unimodales</b> (con una moda), <b>bimodales</b> (con dos modas)
              o <b>multimodales</b> (con más de dos modas).
            </p>
            <div class="bg7 brad p-4">
              <p class="mb-4 text-white"><b>Propiedades:</b></p>
              <div class="bgw p-3 brad mb-3">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span class="mb-0"
                      >Es la única medida de tendencia central que puede
                      aplicarse a variables cualitativas.</span
                    >
                  </li>
                </ul>
              </div>
              <div class="bgw p-3 brad">
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span class="mb-0"
                      >Puede no ser representativa del conjunto si los datos no
                      tienen una moda clara o si hay varias modas.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-4 my-3 order-lg-2">
            <div class="bg14 brad p-4 h-100">
              <img
                class="img-a img-t"
                src="@/assets/curso/temas/13.svg"
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
        <div id="t_1_4" class="titulo-segundo color-acento-botones">
          <h2>1.4&#x9;Media geométrica</h2>
        </div>
        <p class="mb-5">
          La <b>media geométrica</b> es una medida de tendencia central que se
          utiliza principalmente para conjuntos de datos positivos que están
          relacionados multiplicativamente, como tasas de crecimiento o
          porcentajes de cambio. Se calcula multiplicando todos los valores y
          extrayendo la raíz enésima del producto, donde n es el número total de
          observaciones.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-4 my-3">
            <div class="bg16 brad p-4 h-100">
              <img
                class="img-a img-t"
                src="@/assets/curso/temas/14.svg"
                alt=""
              />
            </div>
          </div>
          <div class="col-lg-8 my-3">
            <div class="bg15 brad br-d h-100 p-4">
              <h5>Fórmula:</h5>
              <math
                xmlns="http://www.w3.org/1998/Math/MathML"
                style="font-size: 2rem"
              >
                <mrow>
                  <!-- x̄g -->
                  <msub>
                    <mover>
                      <mi>x</mi>
                      <mo>¯</mo>
                    </mover>
                    <mi>g</mi>
                  </msub>

                  <mo>=</mo>

                  <!-- ( ∏ xi )^(1/n) -->
                  <msup>
                    <mrow>
                      <mo>(</mo>
                      <mrow>
                        <munderover>
                          <mo>&#x220F;</mo>
                          <!-- Product symbol -->
                          <mrow>
                            <mi>i</mi>
                            <mo>=</mo>
                            <mn>1</mn>
                          </mrow>
                          <mi>n</mi>
                        </munderover>
                        <msub>
                          <mi>x</mi>
                          <mi>i</mi>
                        </msub>
                      </mrow>
                      <mo>)</mo>
                    </mrow>
                    <mfrac>
                      <mn>1</mn>
                      <mi>n</mi>
                    </mfrac>
                  </msup>
                </mrow>
              </math>
              <div>
                <p class="mb-3"><b>Donde:</b></p>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem"
                        >
                          <mrow>
                            <msub>
                              <mover>
                                <mi>x</mi>
                                <mo>¯</mo>
                              </mover>
                              <mi> g</mi>
                            </msub>
                          </mrow>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">es la media geométrica.</p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem"
                        >
                          <mrow>
                            <msub>
                              <mi>x</mi>
                              <mi>i</mi>
                            </msub>
                          </mrow>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0">
                          representa cada valor en el conjunto de datos.
                        </p>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem"
                        >
                          <msub>
                            <mi>n</mi>
                          </msub>
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
              <p class="mb-4"><b>Propiedades:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span class="mb-0"
                    >Es adecuada para datos que varían en proporción, como en el
                    crecimiento de una población o el rendimiento de una
                    inversión.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span class="mb-0"
                    >Menos sensible a valores extremos que la media
                    aritmética.</span
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
        <div id="t_1_5" class="titulo-segundo color-acento-botones">
          <h2>1.5&#x9;Media ponderada</h2>
        </div>
        <p class="mb-5">
          La <b>media ponderada</b> es una variante de la media aritmética en la
          que cada valor del conjunto de datos se multiplica por un peso
          específico que refleja su importancia relativa. La media ponderada se
          usa cuando algunos valores tienen mayor relevancia o peso en el
          análisis que otros.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-4 my-3">
            <div class="bg7 brad h-100 p-4">
              <h5 class="text-white">Fórmula:</h5>
              <div
                class="p-3"
                style="background-color:white; border: solid 2px green"
              >
                <math
                  xmlns="http://www.w3.org/1998/Math/MathML"
                  style="font-size: 2rem"
                >
                  <mrow>
                    <!-- x̄p -->
                    <msub>
                      <mover>
                        <mi>x</mi>
                        <mo>¯</mo>
                      </mover>
                      <mi>p</mi>
                    </msub>

                    <mo>=</mo>

                    <!-- Fracción -->
                    <mfrac>
                      <!-- Numerador: sumatoria de w_i * x_i -->
                      <mrow>
                        <munderover>
                          <mo>&#x2211;</mo>
                          <mrow> <mi>i</mi><mo>=</mo><mn>1</mn> </mrow>
                          <mi>n</mi>
                        </munderover>
                        <mrow>
                          <msub><mi>w</mi><mi>i</mi></msub>
                          <mo>&#x2062;</mo>
                          <!-- Espaciado implícito (función implícita) -->
                          <msub><mi>x</mi><mi>i</mi></msub>
                        </mrow>
                      </mrow>

                      <!-- Denominador: sumatoria de w_i -->
                      <mrow>
                        <munderover>
                          <mo>&#x2211;</mo>
                          <mrow> <mi>i</mi><mo>=</mo><mn>1</mn> </mrow>
                          <mi>n</mi>
                        </munderover>
                        <msub><mi>w</mi><mi>i</mi></msub>
                      </mrow>
                    </mfrac>
                  </mrow>
                </math>
              </div>
              <div>
                <p class="mb-3"><b class="text-white">Donde:</b></p>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem; background-color: white"
                          class="p-2"
                        >
                          <mrow>
                            <msub>
                              <mover>
                                <mi>x</mi>
                                <mo>¯</mo>
                              </mover>
                              <mi> p</mi>
                            </msub>
                          </mrow>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0 text-white">es la media ponderada.</p>
                      </div>
                    </div>
                  </li>
                  <li>
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem; background-color: white"
                          class="p-2"
                        >
                          <mrow>
                            <msub>
                              <mi>w</mi>
                              <mi>i</mi>
                            </msub>
                          </mrow>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0 text-white">
                          es el peso asignado al valor
                        </p>
                      </div>
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem; background-color: white"
                          class="p-2"
                        >
                          <mrow>
                            <msub>
                              <mi>x</mi>
                              <mi>i</mi>
                            </msub>
                          </mrow>
                        </math>
                      </div>
                    </div>
                  </li>
                  <li class="mb-3"><i></i></li>
                  <li>
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 2rem; background-color: white"
                          class="p-2"
                        >
                          <mrow>
                            <mi>n</mi>
                          </mrow>
                        </math>
                      </div>
                      <div class="col">
                        <p class="mb-0 text-white">
                          es el número total de observaciones.
                        </p>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <div class="col-lg-8 my-3">
            <img
              class="img-a img-t mb-4"
              src="@/assets/curso/temas/19.png"
              alt=""
            />
            <div>
              <p class="mb-4"><b>Propiedades:</b></p>
              <ul class="lista-ul--color fa-ul">
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >Permite dar más relevancia a ciertos valores según su
                    importancia o frecuencia.</span
                  >
                </li>
                <li class="mb-3">
                  <i class="fas fa-check v1"></i
                  ><span
                    >Es especialmente útil cuando se necesita reflejar la
                    influencia desigual de los datos.</span
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
        <div id="t_1_6" class="titulo-segundo color-acento-botones">
          <h2>1.6&#x9;Media recortada</h2>
        </div>
        <div class="row justify-content-center align-items-center mb-5">
          <div class="col-lg-auto">
            <img class="img-a img-t" src="@/assets/curso/temas/25.png" alt="" />
          </div>
          <div class="col pt-lg-0 pt-md-4">
            <p class="mb-0">
              La <b>media recortada</b> es una versión modificada de la media
              aritmética, en la que se eliminan los valores más extremos (los
              mayores y menores) antes de calcular la media. Esto permite
              reducir el efecto de los valores atípicos en el cálculo.
            </p>
          </div>
        </div>
        <div class="mb-5">
          <div class="row justify-content-center">
            <div class="col-lg-4 my-3">
              <div class="bg10 brad p-4 h-100">
                <img
                  class="img-t img-a mb-4"
                  src="@/assets/curso/temas/26.png"
                />
                <div class="row justify-content-center mb-4">
                  <p class="col-lg-auto mb-4 bg11 text-white px-4 text-center">
                    <b>Cálculo:</b>
                  </p>
                </div>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Se elimina un porcentaje predeterminado de los valores
                      más altos y más bajos.</span
                    >
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Se calcula la media aritmética de los valores
                      restantes.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-4 my-3">
              <div class="bg10 brad p-4 h-100">
                <img
                  class="img-t img-a mb-4"
                  src="@/assets/curso/temas/27.png"
                />
                <div class="row justify-content-center mb-4">
                  <p
                    class="col-lg-auto mb-4 bg11 text-white px-4 &lt;p class="
                    mb-4=""
                    bg4=""
                  >
                    <b>Propiedades:</b>
                  </p>
                </div>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Proporciona una medida de tendencia central menos
                      sensible a valores atípicos.</span
                    >
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Es útil en situaciones donde los datos contienen valores
                      extremos que podrían distorsionar la media.</span
                    >
                  </li>
                </ul>
              </div>
            </div>
            <div class="col-lg-4 my-3">
              <div>
                <img
                  class="img-t img-a d-lg-block d-none"
                  src="@/assets/curso/temas/28.png"
                />
              </div>
            </div>
          </div>
        </div>
      </section>
      <div class="separador-container">
        <div class="separador"></div>
      </div>
      <section>
        <div id="t_1_7" class="titulo-segundo color-acento-botones">
          <h2>1.7&#x9;Trimedia</h2>
        </div>
        <p class="mb-5">
          La <b>trimedia</b> es una medida de tendencia central que toma en
          cuenta tanto la mediana como los cuartiles (primer y tercer cuartil)
          del conjunto de datos. Es una medida robusta que combina información
          de diferentes puntos de la distribución para proporcionar un resumen
          más equilibrado de la tendencia central.
        </p>
        <div class="row justify-content-center">
          <div class="col-lg-5 my-3">
            <div>
              <img
                class="img-a img-t"
                src="@/assets/curso/temas/29.png"
                alt=""
              />
            </div>
          </div>
          <div class="col-lg-7 my-3">
            <div>
              <h5>Fórmula:</h5>
              <math
                xmlns="http://www.w3.org/1998/Math/MathML"
                style="font-size: 1.5rem"
              >
                <mrow>
                  <mi>Trimedia</mi>
                  <mo>=</mo>
                  <mfrac>
                    <mrow>
                      <msub>
                        <mi>Q</mi>
                        <mn>1</mn>
                      </msub>
                      <mo>+</mo>
                      <mn>2</mn>
                      <mo>&#x2062;</mo>
                      <mi>Mediana</mi>
                      <mo>+</mo>
                      <msub>
                        <mi>Q</mi>
                        <mn>3</mn>
                      </msub>
                    </mrow>
                    <mn>4</mn>
                  </mfrac>
                </mrow>
              </math>
              <div>
                <p class="mb-3"><b>Donde:</b></p>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 1rem"
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
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i>
                    <div class="row justify-content-center align-items-center">
                      <div class="col-auto">
                        <math
                          xmlns="http://www.w3.org/1998/Math/MathML"
                          style="font-size: 1rem"
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
                    <i class="fas fa-check v1"></i
                    ><span class="mb-0"
                      >La mediana divide el conjunto de datos en dos mitades.
                    </span>
                  </li>
                </ul>
              </div>
              <div class="bgi p-4 brad">
                <p class="mb-4"><b>Propiedades:</b></p>
                <ul class="lista-ul--color fa-ul">
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Proporciona una medida que tiene en cuenta tanto la
                      dispersión como el centro de los datos.</span
                    >
                  </li>
                  <li class="mb-3">
                    <i class="fas fa-check v1"></i
                    ><span
                      >Es menos sensible a los valores atípicos que la media
                      aritmética.
                    </span>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Tema1',
  components: {},
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
