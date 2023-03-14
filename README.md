#
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href=" https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">"
    <title>List Group </title>
    <style>
    .list-group {
               margin-left: 40px;
               margin-right: 40px;
              margin: 40px;
    }
    .p {
        text-align: center;
    }
    </style>
</head>
<body>
   <h3><p class="p">Exemplo básico de um List Group</p></h3>
    <ul class="list-group">
        <li class="list-group-item"> item um </li>
        <li class="list-group-item">item dois</li>
        <li class="list-group-item">item três</li>
        <li class="list-group-item">item quatro</li>
        <li class="list-group-item">item cinco</li>
      </ul>
      <p class="p">itens ativos para indicar a seleção ativa atual.</p>
      <ul class="list-group">
        <li class="list-group-item active" aria-current="true"> item um ativo</li>
        <li class="list-group-item">item dois</li>
        <li class="list-group-item">item três</li>
        <li class="list-group-item">item quatro</li>
        <li class="list-group-item">item cinco</li>
      </ul>
   <p class="p">Itens desabilitados,<br> Adicione .disabled a um .list-group-item para fazê-lo parecer desativado.</p>
      <ul class="list-group">
  <li class="list-group-item disabled" aria-disabled="true">item um desativado</li>
  <li class="list-group-item">item dois</li>
  <li class="list-group-item">item três</li>
  <li class="list-group-item">item quatro</li>
  <li class="list-group-item">item cinco</li>
</ul>

   <h3><p class="p">Links and buttons</p></h3>
   <p class="p">
    para criar itens de grupo de lista acionáveis com estados de foco, desativado e ativo adicionando </p>
     
   <div class="list-group">
    <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action active" aria-current="true">
       primeiro link
    </a>
    <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action">segundo link </a>
    <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action">terceiro link</a>
    <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action">quarto link</a>
    <a class="list-group-item list-group-item-action disabled">Um link desativado </a>
  </div>
  <p class="p">
    Com < button > s, você também pode usar o disabled atributo em vez da .disabled classe.</p>
  <div class="list-group">
    <button type="button" class="list-group-item list-group-item-action active" aria-current="true">
      primeiro botão
    </button>
    <button type="button" class="list-group-item list-group-item-action">segundo botão</button>
    <button type="button" class="list-group-item list-group-item-action">terceiro botão</button>
    <button type="button" class="list-group-item list-group-item-action">quarto botão</button>
    <button type="button" class="list-group-item list-group-item-action" disabled>quinto botão</button>
  </div>

  <h3><p class="p">Flush </p></h3>
  <p class="p">
    Adicione .list-group-flush para remover algumas bordas e cantos arredondados para renderizar 
    itens de grupo de lista de ponta a ponta em um contêiner pai (por exemplo, cartões).</p>


  <ul class="list-group list-group-flush">
    <li class="list-group-item">item um</li>
    <li class="list-group-item">item dois</li>
    <li class="list-group-item">item três</li>
    <li class="list-group-item">item quatro</li>
    <li class="list-group-item">item cinco</li>
  </ul>
   
  <h3><p class="p">Numbered </p></h3>
  <p class="p">
    Adicione a .list-group-numbered classe modificadora (e, opcionalmente, use um < ol > elemento) para optar por itens de grupo de lista numerada</p>

    <ol class="list-group list-group-numbered">
        <li class="list-group-item">A list item</li>
        <li class="list-group-item">A list item</li>
        <li class="list-group-item">A list item</li>
      </ol>

      <p class="p">
        Eles também funcionam muito bem com conteúdo personalizado.</p>

        <ol class="list-group list-group-numbered">
            <li class="list-group-item d-flex justify-content-between align-items-start">
              <div class="ms-2 me-auto">
                <div class="fw-bold">Subtítulo</div>
                Conteúdo para item de lista
              </div>
              <span class="badge bg-primary rounded-pill">14</span>
            </li>
            <li class="list-group-item d-flex justify-content-between align-items-start">
              <div class="ms-2 me-auto">
                <div class="fw-bold">Subtítulo</div>
                Conteúdo para item de lista
              </div>
              <span class="badge bg-primary rounded-pill">20</span>
            </li>
            <li class="list-group-item d-flex justify-content-between align-items-start">
              <div class="ms-2 me-auto">
                <div class="fw-bold">Subtítulo</div>
                Conteúdo para item de lista
              </div>
              <span class="badge bg-primary rounded-pill">20000</span>
            </li>
          </ol>

          <h3><p class="p"> Horizontal  </p></h3>
          <p class="p">Adicione .list-group-horizontal para alterar o layout dos itens do grupo de lista de vertical 
            para horizontal em todos os pontos de interrupção. Como alternativa, escolha uma variante responsiva .list-group-horizontal-{sm|md|lg|xl|xxl}para tornar um grupo de lista horizontal começando no ponto de interrupção min-width. 
            Atualmente, grupos de listas horizontais não podem ser combinados com grupos de listas niveladas.</p>

            <ul class="list-group list-group-horizontal">
                <li class="list-group-item">Um item</li>
                <li class="list-group-item">Um segundo item</li>
                <li class="list-group-item">Um segundo item</li>
              </ul>
              <ul class="list-group list-group-horizontal-sm">
                <li class="list-group-item">Um item</li>
                <li class="list-group-item">Um segundo item</li>
                <li class="list-group-item">Um segundo item</li>
              </ul>
              <ul class="list-group list-group-horizontal-md">
                <li class="list-group-item">Um item</li>
                <li class="list-group-item">Um segundo item</li>
                <li class="list-group-item">Um segundo item</li>
              </ul>
              <ul class="list-group list-group-horizontal-lg">
                <li class="list-group-item">Um item</li>
                <li class="list-group-item">Um segundo item</li>
                <li class="list-group-item">Um segundo item</li>
              </ul>
              <ul class="list-group list-group-horizontal-xl">
                <li class="list-group-item">Um item</li>
                <li class="list-group-item">Um segundo item</li>
                <li class="list-group-item">Um segundo item</li>
              </ul>
              <ul class="list-group list-group-horizontal-xxl">
                <li class="list-group-item">Um item</li>
                <li class="list-group-item">Um segundo item</li>
                <li class="list-group-item">Um segundo item</li>
              </ul>


              <h3><p class="p"> Contextual classes   </p></h3>
              <p class="p">Use classes contextuais para estilizar itens de lista com fundo e cor com estado.</p>
              
              <ul class="list-group">
                <li class="list-group-item">A simple default list group item</li>
              
                <li class="list-group-item list-group-item-primary">A simple primary list group item</li>
                <li class="list-group-item list-group-item-secondary">A simple secondary list group item</li>
                <li class="list-group-item list-group-item-success">A simple success list group item</li>
                <li class="list-group-item list-group-item-danger">A simple danger list group item</li>
                <li class="list-group-item list-group-item-warning">A simple warning list group item</li>
                <li class="list-group-item list-group-item-info">A simple info list group item</li>
                <li class="list-group-item list-group-item-light">A simple light list group item</li>
                <li class="list-group-item list-group-item-dark">A simple dark list group item</li>
              </ul>

             
              <p class="p"> também funcionam com .list-group-item-action, Também é suportado o .active estado; aplique-o para indicar uma seleção ativa em um item de grupo de lista contextual.</p>

              <div class="list-group">
                <a href="#" class="list-group-item list-group-item-action">A simple default list group item</a>
              
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-primary">A simple primary list group item</a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-secondary">A simple secondary list group item</a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-success">A simple success list group item</a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-danger">A simple danger list group item</a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-warning">A simple warning list group item</a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-info">A simple info list group item</a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-light">A simple light list group item</a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action list-group-item-dark">A simple dark list group item</a>
              </div>

              <h3><p class="p"> com Badges   </p></h3>
              <p class="p">Adicione emblemas a qualquer item de grupo de lista para mostrar contagens não lidas, atividades e muito mais com a ajuda de alguns utilitários .</p>

              <ul class="list-group">
                <li class="list-group-item d-flex justify-content-between align-items-center">
                  Um item de lista
                  <span class="badge bg-primary rounded-pill">14</span>
                </li>
                <li class="list-group-item d-flex justify-content-between align-items-center">
                  Um segundo item da lista
                  <span class="badge bg-primary rounded-pill">2</span>
                </li>
                <li class="list-group-item d-flex justify-content-between align-items-center">
                  Um terceiro item da lista
                  <span class="badge bg-primary rounded-pill">1</span>
                </li>
              </ul>


              <h3><p class="p"> Custom content  </p></h3>
              <p class="p">Adicione praticamente qualquer HTML, mesmo para grupos de listas vinculadas como o abaixo, com a ajuda dos utilitários flexbox .</p>

              <div class="list-group">
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action active" aria-current="true">
                  <div class="d-flex w-100 justify-content-between">
                    <h5 class="mb-1"> Cabeçalho do item do grupo de lista</h5>
                    <small>3 dias atrás</small>
                  </div>
                  <p class="mb-1">Algum conteúdo de espaço reservado em um parágrafo.</p>
                  <small>E algumas letras pequenas</small>
                </a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action">
                  <div class="d-flex w-100 justify-content-between">
                    <h5 class="mb-1">Cabeçalho do item do grupo de lista</h5>
                    <small class="text-muted">3 dias atrás</small>
                  </div>
                  <p class="mb-1">Algum conteúdo de espaço reservado em um parágrafo.</p>
                  <small class="text-muted">E algumas letras miúdas discretas.</small>
                </a>
                <a href="https://getbootstrap.com/docs/5.2/components/list-group/#basic-example" class="list-group-item list-group-item-action">
                  <div class="d-flex w-100 justify-content-between">
                    <h5 class="mb-1">Cabeçalho do item do grupo de lista</h5>
                    <small class="text-muted">3 dias atrás</small>
                  </div>
                  <p class="mb-1">Algum conteúdo de espaço reservado em um parágrafo.</p>
                  <small class="text-muted">E algumas letras miúdas discretas.</small>
                </a>
              </div>


              <h3><p class="p"> Checkboxes and radios </p></h3>
              <p class="p">Coloque as caixas de seleção e rádios do Bootstrap nos itens do grupo de listas 
                e personalize conforme necessário. Você pode usá-los sem < label >s, mas lembre-se de incluir um aria-label atributo e um valor para acessibilidade.</p>


                <ul class="list-group">
                  <li class="list-group-item">
                    <input class="form-check-input me-1" type="checkbox" value="" id="firstCheckbox">
                    <label class="form-check-label" for="firstCheckbox"> Primeira caixa de seleção</label>
                  </li>
                  <li class="list-group-item">
                    <input class="form-check-input me-1" type="checkbox" value="" id="secondCheckbox">
                    <label class="form-check-label" for="secondCheckbox"> Segunda caixa de seleção</label>
                  </li>
                  <li class="list-group-item">
                    <input class="form-check-input me-1" type="checkbox" value="" id="thirdCheckbox">
                    <label class="form-check-label" for="thirdCheckbox">Terceira caixa de seleção</label>
                  </li>
                </ul>

                <ul class="list-group">
                  <li class="list-group-item">
                    <input class="form-check-input me-1" type="radio" name="listGroupRadio" value="" id="firstRadio" checked>
                    <label class="form-check-label" for="firstRadio">primeiro radio</label>
                  </li>
                  <li class="list-group-item">
                    <input class="form-check-input me-1" type="radio" name="listGroupRadio" value="" id="secondRadio">
                    <label class="form-check-label" for="secondRadio">Segundo  radio</label>
                  </li>
                  <li class="list-group-item">
                    <input class="form-check-input me-1" type="radio" name="listGroupRadio" value="" id="thirdRadio">
                    <label class="form-check-label" for="thirdRadio">terceiro  radio</label>
                  </li><br>
                  
                  <p class="p"> Você pode usar .stretched-link on < label >s para tornar clicável todo o item do grupo da lista.</p>

                  <ul class="list-group">
                    <li class="list-group-item">
                      <input class="form-check-input me-1" type="checkbox" value="" id="firstCheckboxStretched">
                      <label class="form-check-label stretched-link" for="firstCheckboxStretched"> Primeira caixa de seleção
                      </label>
                    </li>
                    <li class="list-group-item">
                      <input class="form-check-input me-1" type="checkbox" value="" id="secondCheckboxStretched">
                      <label class="form-check-label stretched-link" for="secondCheckboxStretched">Segunda caixa de seleção</label>
                    </li>
                    <li class="list-group-item">
                      <input class="form-check-input me-1" type="checkbox" value="" id="thirdCheckboxStretched">
                      <label class="form-check-label stretched-link" for="thirdCheckboxStretched"> Terceira caixa de seleção
                      </label>
                    </li>
                  </ul>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-OERcA2EqjJCMA+/3y+gxIOqMEjwtxJY7qPCqsdltbNJuaOe923+mo//f6V8Qbsw3" crossorigin="anonymous"></script>
</body>
</html>
