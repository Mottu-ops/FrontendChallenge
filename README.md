
<p align="center"><img src="https://mottu.com.br/wp-content/uploads/2022/02/Mottu-grupo-verde-horizontal.png" width="150" /></p>
<h1 align="center">Mottu Front-end Challenge</h1>

Olá! 
Primeiramente, parabéns por ter avançado ao desafio técnico para frontends da Mottu! 

## DESAFIO

<p>
  Aplicação de consulta, visualização e cadastro de personagens favoritos do seriado Rick & Morty.
</p>

## API
Na aplicação, será utilizada a API pública [rickandmortyapi](https://rickandmortyapi.com/documentation/#introduction) para o consumo das requisições dos personagens, deve ser utilizado a abordagem REST.

## PROTÓTIPO
[Link Figma](https://www.figma.com/file/c8xS5wew3KBVVY62BS2imT/.%F0%9F%94%93-%5BInterno%5D-Teste-t%C3%A9cnico?type=design&node-id=1%3A210&mode=design&t=vHzykxexPvSxZoFk-1) 

## REQUISITOS
Deve-se criar uma aplicação Angular, atendendo os seguintes requisitos:
* Buscar um personagem pelo nome;
* Exibir mensagem de erro caso o personagem não exista;
* Exibir informações mínimas sobre o(s) personagem(ns) caso ele(s) exista(m);
* Registrar o personagem na lista de favoritos utilizando alguma biblioteca de controle de estado global (NgRx, Ngxs, Akita) ou utilizar os Subjects do RxJs;
* O contador no topo da página deve ser atualizado dinamicamente em tempo real;
* Visualizar a lista de personagens favoritos;
* Remover o personagem da lista de favoritos;

## DIFERENCIAL
* Busca por nome: utilizar operadores do RxJs para deixar mais eficiente a pesquisa e fazer uma nova chamada na API para o filtro não ficar no front-end;
* Utilizar o pipe async no contador dos favoritos no header;
* Adicionar ao projeto a fonte personalizada que foi utilizada no prótotipo: [Google Fonts](https://fonts.google.com/share?selection.family=Creepster|Poppins);
* Otimizar o uso de diretivas estruturais;
* Carregamento lento dos módulos das páginas;
* Seja criativo. Você decide quais funcionalidades irá incluir além dos requisitos.

## HISTÓRIAS DE USUÁRIO
1. Buscar personagem.
2. Ao pesquisar um personagem, gostaria de ver nome, genero e sua foto(se existir) antes de decidir favoritá-lo.
3. Ao pesquisar um personagem, gostaria de salvá-lo para que fique listado nos meus favoritos.
4. Ao pesquisar um um personagem que não existe, gostaria de ser avisado que ele não existe.

## :rocket: TECNOLOGIAS
Tecnologias obrigatórias:
- **Angular 13+** 
- **Typescript** 
- **RxJs**

 Tecnologias opcionais:

- **Angular Material**
- **Bootstrap**
- **NgRx**
- **NGXS** 

Envio da solução
-------------------------
Você deve criar um novo repositóro público, implementar a solução e enviar para gente o link do seu repositório.
