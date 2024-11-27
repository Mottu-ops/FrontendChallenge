
<p align="center"><img src="https://mottu.com.br/wp-content/uploads/2022/02/Mottu-grupo-verde-horizontal.png" width="150" /></p>
<h1 align="center">Mottu Front-end Challenge</h1>

Olá! 
Primeiramente, parabéns por ter avançado ao desafio técnico para front-end da Mottu! 

## DESAFIO

<p>
  Aplicação de consulta, visualização e cadastro de personagens favoritos do seriado Rick & Morty.
</p>

## API
Na aplicação, será utilizada a API pública [rickandmortyapi](https://rickandmortyapi.com/documentation/#introduction) para o consumo das requisições dos personagens, deve ser utilizado a abordagem REST.

## PROTÓTIPO (OBRIGATÓRIO)
[Link Figma](https://www.figma.com/file/c8xS5wew3KBVVY62BS2imT/.%F0%9F%94%93-%5BInterno%5D-Teste-t%C3%A9cnico?type=design&node-id=1%3A210&mode=design&t=vHzykxexPvSxZoFk-1) 

## REQUISITOS
Deve-se criar uma aplicação Angular, atendendo os seguintes requisitos:
* Seguir o protótipo indicado acima;
* Buscar um personagem pelo nome;
* Exibir informações mínimas sobre o(s) personagem(ns) caso ele(s) exista(m);
* Registrar o personagem na lista de favoritos utilizando alguma biblioteca de controle de estado global (NgRx, Ngxs, Akita) ou utilizar os Subjects do RxJs;
* O contador no topo da página deve ser atualizado dinamicamente em tempo real;
* Visualizar a lista de personagens favoritos;
* Remover o personagem da lista de favoritos;
* A listagem de personagens deve conter uma paginação (infinite scroll, paginator, ou outra forma de sua preferência);

## DIFERENCIAL
* Busca por nome: utilizar operadores do RxJs para deixar mais eficiente a pesquisa e fazer uma nova chamada na API para o filtro não ficar no front-end;
* Adicionar internacionalização no projeto. 
* Adicionar ao projeto a fonte personalizada que foi utilizada no prótotipo: [Google Fonts](https://fonts.google.com/share?selection.family=Creepster|Poppins);
* Otimizar o uso de diretivas estruturais;
* Carregamento lento dos módulos das páginas;
* Layout responsivo;
* Fazer o deploy da aplicação;
* Seja criativo. Você decide quais funcionalidades irá incluir além dos requisitos;


## HISTÓRIAS DE USUÁRIO
1. Buscar personagem.
2. Ao pesquisar um personagem, gostaria de ver nome, espécie e sua foto (se existir) antes de decidir favoritá-lo.
3. Ao pesquisar um personagem, gostaria de salvá-lo para que fique listado nos meus favoritos.
4. Ao pesquisar um um personagem que não existe, gostaria de ser avisado que ele não existe.

## INSTRUÇÕES

* O desafio é válido para diversos níveis, portanto não se preocupe se não conseguir resolver por completo.
* A aplicação só será avaliada se estiver rodando, se necessário crie um passo a passo para isso.
* Faça um clone do repositório em seu git pessoal para iniciar o desenvolvimento e não cite nada relacionado a Mottu.
* Após teste realizado, favor encaminha-lo via Link abaixo: Link: [Formulário - Mottu](https://forms.office.com/pages/responsepage.aspx?id=tJOWeiUlFUGvgqknx7NW8yCRV67umA9NjmtPmSXxeBlUNFVXNkk4TjdTTElRUksxWTVIVlI3QjU1Ty4u&route=shorturl)

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
