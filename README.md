<h1 align="center">:arrow_forward: Criando requisições - Alura Play</h1>

<div>
  <p align="center">
    <img alt="Licença do projeto com os dizeres: MIT" src="https://img.shields.io/github/license/RodrigoHarder/criando-requisicoes.svg">
    <img alt="Status do projeto com os dizeres: Concluído" src="https://img.shields.io/static/v1?label=Status&message=Concluído &color=green">
  </p>
</div>

## **Descrição**

O projeto foi desenvolvido no curso de [JavaScript: criando requisições](https://cursos.alura.com.br/course/javascript-criando-requisicoes) ministrado pela instrutora Mônica Hillman. O objetivo foi simular e consumir dados de uma API, além de inserir novos dados e realizar pesquisas de vpideos por meio de palavras chaves, tudo isso sendo realizado através de requisições.

## **Aprendizagens** 

- Como diferenciar projetos estáticos de projetos dinâmicos e entender a importância do JS para a criação dessa dinamicidade;
- Como instalar o Node.js e os pacotes necessários para mockar uma API (json-server) por meio do gerenciador de pacotes NPM;
- Manipulação do DOM;
- Como inserir novos objetos no arquivo json;
- Uso de `data-attributes`;
- Como salvar dados na API por meio do Método POST;
- Como estruturar requisições do tipo GET e POST enviadas por meio do fetch API;
- Diferenciar os métodos GET e POST:
    - **Requisição GET:** solicitamos a API que retorne os dados, sem executar nada, além disso.
    - **Requisição POST:** são usadas para enviar dados para a API. Por exemplo, criar um novo registro de usuário. Diferente de requisições do tipo GET, você precisará passar um objeto das opções de configuração como um segundo argumento em requisições POST.
        - `"Content-type"`: especifica o tipo de arquivo está sendo enviado ou recebido. Ao receber ou enviar um arquivo json usamos o `"application/json"`
        - Enviando o corpo da requisição contendo dentro das chaves um objeto de valores no modelo de string (`JSON.stringify`)
- Diferenciar method, header e body;
- Capturar eventos de envio (submit) em formulários;
- Endpoint: é a URL onde seu serviço pode ser acessado por uma aplicação;
- Utilização de parâmetros para buscar objetos específicos na API;
- Recolher dados escritos em um campo de digitação;
- Verificar se há elementos filhos em um elemento por meio do `firstChild` e remover elementos filhos por meio do `removeChild`, utilizando um laço de repetição para apagar todos os itens da lista;
- Como lidar com erro utilizando try e catch;
- Criar novos erros com `throw new Error`;
- Detectar erros por condicionais;
- `if(!conexao.ok)`: quer dizer que a conexão pode estar com problemas;
- Verificar se uma lista está vazia pelo seu tamanho, utilizando o `.length`;
- Imprimir mensagens de erro na tela por meio da manipulação do DOM e utilizando alertas;

## **Funcionalidades**

O resultado pode ser visto no gif abaixo:

![Gif da tela do site da Alura Play mostrando uma pesquisa sendo realizada na parte central superior com a palavra memes e retornando um vídeo logo abaixo e em seguida é mostrado a realização da inserção de um vídeo clicando-se no ícone de câmera no canto superior direito e depois preenchendo os campos com a URL do vídeo, o título e a URL da imagem](video-resultado.gif)

## **Como usar os arquivos?**

- Inicialmente você precisa ter instalado em seu computador um editor de código-fonte, no meu caso eu utilizo o [Visual Studio Code](https://code.visualstudio.com/download). 
- Depois, você pode fazer o download do projeto clicando na opção **Code** e em seguida selecionando **Download Zip**.

Ou

1. Clonar o repositório

```
git clone https://github.com/RodrigoHarder/criando-requisicoes.git
```
2. Localizar e abrir a pasta *criando-requisicoes*

```
cd criando-requisicoes
```

## **Tecnologias usadas**

Neste projeto foram fornecidas os arquivos HTML e CSS e usada a linguagem JavaScript realizar a parte dinâmica.

Para a construção dos códigos que compõem a página foi utilizado o editor de código-fonte abaixo:

<img align="center" alt="VS Code" src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white">

## Desenvolvedor

[<img src="https://avatars.githubusercontent.com/u/114362538?v=4" width=115><br><sub>Rodrigo Silva Harder</sub>](https://github.com/RodrigoHarder)
