<template>
  <div class="container">
    <div class="titulo">
      <h1>Itens de Avaliação</h1>
    </div>
    <div class="form">
      <div class="titulo1">
        <h1>1. Limpeza e conservação da sala de aula e da oficina</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="one" value="One" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="two" value="Two" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="three" value="Three" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input type="radio" id="three" value="Three" v-model="picked" />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="three" value="Three" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>
          2. Disponibilidade de equipamentos, máquinas e ferramentas para a
          realização do curso
        </h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>
          3. Qualidade de apostilas, livros e textos, quanto a impressão e a
          adequação da informação
        </h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>4. Cumprimento do horário das aulas</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>5. Cumprimento dos objetivos propostos pelo curso</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>6. Preocupação do docente com o aproveitamento dos alunos</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>7. Domínio do docente sobre os assuntos tratados</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>
          8. O aprendizado, na teoria e na prática, em relação ao esperado
        </h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>9. Conteúdo do curso, em relação às expectativas</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>10. Atendimento da recepção / secretaria da escola</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>11. Atendimento telefônico da escola</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>12. Atendimento da cantina / lanchonete</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

    <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>13. Atendimento da Biblioteca</h1>
      </div>
      <main class="pergunta1">
        <section class="right-1">
          <div class="pg1">
            <h6 id="txUm">Nível de importância:</h6>
            <div class="rbt_importancia" id="v-model-radiobutton">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Alta</label>
              <br />
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Media</label>
              <br />
              <input type="radio" id="three" value="Three" v-model="picked" />
              <label for="three">Baixa</label>
            </div>
          </div>
        </section>

        <section class="left-1">
          <div class="pg1">
            <h6 id="txdois">Nível de satisfação:</h6>
            <div class="rbt_satis" id="v-model-radiobutton">
              <div class="ruim">
                <input type="radio" id="otimo" value="otimo" v-model="picked" />
                <label for="one">Otimo</label>
                <br />
                <input type="radio" id="bom" value="bom" v-model="picked" />
                <label for="two">Bom</label>
                <br />
                <input type="radio" id="nda" value="nda" v-model="picked" />
                <label for="three">Não se aplica</label>
                <br />
              </div>

              <div class="ruim">
                <input
                  type="radio"
                  id="regular"
                  value="regular"
                  v-model="picked"
                />
                <label for="three">Regular</label>
                <br />
                <input type="radio" id="ruim" value="ruim" v-model="picked" />
                <label for="three">Ruim</label>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>

  <div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>Justifique a sua insatisfação.</h1>
      </div>
      <div>
        <textarea class="box" rows="10" cols="40" placeholder="insira seu texto aqui..."></textarea>
      </div>
    </div>


<div class="divisor"></div>
    <div class="form">
      <div class="titulo1">
        <h1>Deseja enviar seu formulário anonimamente?</h1>
      <main class="pergunta1">
        <section class="right-2">
            <div class="pg9" id="v-model-radiobutton">
            <div id="123">
              <input type="radio" id="one" value="One" v-model="picked" />
              <label for="one">Sim</label>
            </div>
              <br />
            <div id="456">  
              <input type="radio" id="two" value="Two" v-model="picked" />
              <label for="two">Não</label>
            </div>
          </div>
        </section>    
      </main>
    </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "Home",

  data() {
    return {
      picked: "",
    };
  },
};
</script>

<style lang="scss">
@import "./scss/home.scss";
</style>
