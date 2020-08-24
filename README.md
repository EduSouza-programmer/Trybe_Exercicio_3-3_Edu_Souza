<h1 align="center">
    <img alt="Image Trybe" src="https://i.ibb.co/d4W2x4g/trybe.png" width="400px" />
</h1>

<h3 align="center">
  Exercício 3-3: HTML & CSS - Seletores e posicionamento - 
  
  ~~_Concluído o/ o/ o/_~~
</h3>

<blockquote align="center">“Quanto mais você estuda, mais aprende e se aproxima de realizar seu sonhos!”</blockquote>

<h1></h1>

<p align="center">

  <a href="https://www.linkedin.com/in/eduardosouzaprogrammer/">
    <img alt="Made by Eduardo Souza" src="https://img.shields.io/badge/made%20by-Edu%20Souza-%23F8952D">
  </a>&nbsp;

 <a href="https://edusouza-programmer.github.io/">
<img alt="Github page Edu Souza " src="https://img.shields.io/badge/Github%20page-Edu_Souza-orange">
</a>&nbsp;

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>

<p align="center">
  <a href="#rocket-Sobre-o-Exercício">Sobre o Exercício</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Entrega">Entrega</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Licença">Licença</a>
</p>

# :rocket: Sobre o Exercício

Hoje vamos finalizar a primeira versão do seu Portfólio Web adicionando seletores e CSS de layout.
Com este exercício, você será capaz de:

-   Aplicar layout mais consistente usando elementos de bloco e inline aplicando todo o conhecimento que você construiu hoje;

-   Salvar todas as alterações dentro de um arquivo externo style.css;

-   Usar Box Model para organizar melhor os elementos no seu Portfólio Web!;

-   Atualizar seu Portfólio Web no GitHub Pages.

### Layout e Box Model no seu Portfólio Web

Antes de começar, você deve seguir estas instruções e fazer o setup para o exercício de hoje:

1. Entre no diretório que você criou no dia anterior;
2. Procure a tag <style></style>, onde você fez as alterações ontem. Mova todo o conteúdo da tag style e coloque em um arquivo style.css;
3. Adicione as novas alterações dentro do arquivo style.css;
4. Não se esqueça de importar esse arquivo na sua página;
5. Depois de importar o arquivo style.css, você já pode remover a tag style do seu documento.

### Requisitos

Seu Portfólio Web deve ter ter um layout usando Box Model com as informações a seguir:

-   Coloque seu nome, sua foto e a descrição que você escreveu sobre você dentro de blocos;

-   A descrição deve ficar ao lado da foto;

-   Centralize seu nome na página;

-   Use padding e coloque uma cor de fundo na sua foto que seja diferente da cor de fundo do resto da página;

-   Adicione margin e padding nos elementos com pelo menos 35px de distância;

-   Coloque espaçamento entre os elementos para que você se sinta mais confortável com o que você fez;

-   Coloque estilo somente nos ítens ímpares da lista das suas habilidades.

#

# Entrega

## Sumário

-   <p><a href="#1">1.</a> Adicione bordas, margem e espaçamento;</p>

### **_Projetos_**

-   <p><a href="#Project_1">Projeto_1:</a> Esse projeto, você vai usar tudo o que aprendeu até agora para criar um site de viagens incentivando as pessoas a visitar um lugar exótico. Você deve ter imagens do que elas vão ver, listas de coisas para ver e lugares para ir e parágrafos de detalhes interessantes. Você também deve usar CSS para estilizar o site, usando uma mistura de seletores simples que você aprendeu.</p>

## Questões sobre os desafios [Meus códigos]

### 1°

#### Adicione bordas

-   Essa página web mostra uma galeria de fotos de cachorros da raça boxer. Nesse primeiro passo, adicione uma borda a todas as fotos. Se puder , tent fazer com que elas pareçam a moldura das fotos.

#### Adicione margem

-   As fotos parecem estar muito próximas uma das outras. Adicione margem a elas, de todos os lados, ou apenas nos lados que as separam.

#### Adicione espaçamento

-   As fotos estão muito próximas ao lado da div que represnta a galeria, e isso parece estranho. Adicione espaçamento em torno de todos os lados da div da galeria, para que a aparência fique melhor.

#### Resposta:

<details>
 <summary>Código HTML</summary>

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8" />
        <title>Challenge: The boxer model</title>
        <style>
            body {
                font-family: cursive;
            }

            .photo-gallery {
                background: rgb(255, 254, 217);
                padding: 100px;
            }

            .photo {
                width: 200px;
                border: 10px ridge gray;
                margin: 7px 7px;
            }
        </style>
    </head>

    <body>
        <h1>Boxers are beautiful?</h1>

        <div class="photo-gallery">
            <img class="photo" src="https://www.kasandbox.org/programming-images/animals/boxer-getting-tan.png" />

            <img class="photo" src="https://www.kasandbox.org/programming-images/animals/boxer-laying-down.png" />

            <img class="photo" src="https://www.kasandbox.org/programming-images/animals/boxer-wagging-tongue.png" />
        </div>
    </body>
</html>
```

</details>

<p align="right">
    <a href="https://edusouza-programmer.github.io/Trybe_Exercicio_3-3_Edu_Souza//parte-1/challenge_1-o_modelo_boxer.html">
    <img alt="Go index.html" src="https://img.shields.io/badge/Go-index.html-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 2°

### Pinte o título inverno

-   Essa página web descreve as estações favoritas de Olaf, um boneco de neve que ama o sol. Ambas as tags "h2" têm ids, mas não há regras CSS para estilizá-las. Adicione 2 regras que atribuam cor aos títulos.

#### Resposta:

<details>
<summary>Código HTML</summary>

```html

```

</details>

<p align="right">
    <a href="https://edusouza-programmer.github.io/Trybe_Exercicio_3-2_Edu_Souza/parte-1/challenge-ids_sazonais.html">
    <img alt="Go index.html" src="https://img.shields.io/badge/Go-index.html-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 3°

#### Faça citações em itálico e Faça declarações em negrito

-   Essa página web mostra algumas citações e declarações famosas de filmes e programas de TV. Adicione uma regra CSS que
    faz com que todas as citações tenham uma fonte de estilo itálico, de forma que elas se pareçam mais com citações.
    Adicione uma regra CSS que faz com que todas as declarações tenham uma fonte destacada em negrito, assim vai parecer que elas foram ditas em voz alta.

#### Resposta:

<details>
<summary>Código HTML</summary>

```html

</html>
```

</details>

<p align="right">
    <a href="https://edusouza-programmer.github.io/Trybe_Exercicio_3-2_Edu_Souza/parte-2/challenge_formatos_de_fonte_famosos.html">
    <img alt="Go index.html" src="https://img.shields.io/badge/Go-index.html-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 4°

#### Crie tamanhos de fonte grandes

-   Essa página web inclui a letra de uma música sobre palavras grandes. Colocamos as classes 'big' e 'bigger' nas tags "em" que descrevem palavras grandes, mas não as estilizamos. Adicione uma propriedade às regras CSS para tornar grande o tamanho das palavras 'big', e para tornar ainda maior o tamanho das palavras 'bigger'. Use as mesmas unidades para ambas as propriedades.

#### Resposta:

<details>
<summary>Código HTML</summary>

```html

</html>
```

</details>

<p align="right">
    <a href="https://edusouza-programmer.github.io/Trybe_Exercicio_3-2_Edu_Souza/parte-2/challenge_tamanhos_de_fonte_enormes.html">
    <img alt="Go index.html" src="https://img.shields.io/badge/Go-index.html-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

## Projetos

### Project_1°

#### Página web sobre viagens

-   Esse projeto, você vai usar tudo o que aprendeu até agora para criar um site de viagens incentivando as pessoas a visitar um lugar exótico. Você deve ter imagens do que elas vão ver, listas de coisas para ver e lugares para ir e parágrafos de detalhes interessantes. Você também deve usar CSS para estilizar o site, usando uma mistura de seletores simples que você aprendeu.

#### Resposta:

<details>
<Summary>Código HTML & CSS</summary>

```html

```

</details>

<p align="right">
    <a href="https://edusouza-programmer.github.io/Trybe_Exercicio_3-2_Edu_Souza/parte-1/challenge_projeto-_pagina_web_sobre_viagens.html">
    <img alt="Go index.html" src="https://img.shields.io/badge/Go-index.html-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

## Licença

Este projeto está licenciado sob a Licença MIT - consulte [LICENSE](https://opensource.org/licenses/MIT) para maiores detalhes.
