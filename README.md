<h1> Robotron 2000 </h1>

O código é parte de um site que permite ao usuário controlar e visualizar as estatísticas de diferentes partes de um robô fictício chamado "Robotron". O código permite que o usuário clique em elementos de controle para ajustar os valores de contagem associados às peças do robô e, em seguida, atualiza as estatísticas do robô com base nesses valores.

## Funcionalidades

O script usa o método querySelectorAll() para selecionar todos os elementos HTML que possuem o atributo data-controle ou data-estatistica, que são elementos de interface com o usuário para controlar e exibir estatísticas sobre as peças do robô.

O objeto pecas é um objeto JavaScript que armazena informações sobre as diferentes peças do robô e suas estatísticas, incluindo "força", "poder", "energia" e "velocidade". Cada peça é representada como uma propriedade do objeto e contém um objeto com as estatísticas correspondentes.

O método forEach() é usado para iterar sobre os elementos selecionados com querySelectorAll(), adicionando um listener de evento 'click' em cada elemento. Quando o usuário clica em um elemento de controle, a função manipulaDados() é chamada para atualizar o valor do elemento "data-contador" do respectivo controle.

A função atualizaEstatistica() é chamada a cada vez que um controle é clicado, para atualizar as estatísticas exibidas no elemento HTML "data-estatistica" correspondente a cada peça do robô.

## Vitrine.Dev

| :placard: Vitrine.Dev |<a href="https://cursos.alura.com.br/vitrinedev/christianoliver">Christian Oliveira</a> |
| -------------  | --- |
| :sparkles: Nome        | **Robotron 2000**
| :label: Tecnologias | HTML, CSS, JS

![image](https://user-images.githubusercontent.com/85292359/233507229-5f249f37-f17e-42ec-ab67-d641e6cc59b8.png)
