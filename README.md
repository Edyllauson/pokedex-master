<p align="center">
  <img alt="Pokedex logo" src=".github/logo.svg" width="400px" />
</p>

<p align="center" fontSize="60px">
  Plataforma para listagem de pokémons
</p>

<p align="center">
  <img alt="Layout da aplicação" width="100%" src="./.github/screenshot.png" />
</p>

## 💻 Projeto

Desenvolver uma plataforma web para listagem e visualização de pokémons, para a construção deste projeto foi usado ReactJS. Todos os dados sobre os pokémons como nome, número, tipo, imagem e entre outras coisas, foram possíveis com o uso da API REST [PokéApi](https://pokeapi.co/).

### Funcionalidades

- [x] **Listagem dos pokémons**: Listar os pokémons com o uso da API REST.

- [x] **Ampliar a listagem dos pokémons**: Método para adicionar mais pokémons a lista, ampliando-se a quantia de pokémons mostrada ao usuário.

- [x] **Buscar pokémons**: Método para filtrar os pokémons a partir do seu nome.

- [x] **Efeito no cartão do pokémon**: Criar uma animação ao usuário apresentar foco no cartão do pokémon.

- [x] **Selecionar pokémon**: Criar uma página na aplicação com mais detalhes sobre o pokémon escolhido.

- [x] **Criar seções do pokémons**: Separar as informações do pokémon em três seções: Sobre, Estatísticas, Evoluções.

- [x] **Seção Sobre**: Dados básicos sobre o pokémon, como altura, peso, fraquezas.

- [x] **Seção Estatísticas**: Pontos de batalha do pokémon, como vida, ataque, defesa, velocidade, especial ataque e especial defesa.

- [x] **Seção Evoluções**: Construir a árvore de evolução do pokémon.

### Conceitos abordados

- Uso de flexbox para alinhar e ajustar elementos na página.

- Manipulação no eixo z com o uso da propriedade `z-index` no css.

- Consumo de api com o uso da lib [axios](https://github.com/axios/axios).

- Conceitos de tipagem no typescript.

- Uso do conceito de função recursiva para criar a árvore de evolução do pokémon.

- Controle de paginação na listagem dos pokémons e filtro por nome.

- Configuração de fonte local.

- Criando tema global de cores com o `DefaultTheme` do [styled-components](https://www.styled-components.com/).

### Notas

- A listagem dos pokémons foi limitada em 700, pois a partir desse número a api apresenta alguns erros nas informações do pokémon, como imagem, dados de batalha, caracteríscas, dados sobre a evolução.

- As características de batalha de cada pokémon não estão precisas, o motivo disso foi que eu não achei a base do calcúlo de cada espécie, como não existe um padrão geral e são várias espécies eu decidi limitar as informações desse campo.

## :rocket: Tecnologias

-  [React](https://pt-br.reactjs.org/)
-  [Styled-components](https://www.styled-components.com/)
-  [React-Icons](https://react-icons.netlify.com/)
-  [Axios](https://github.com/axios/axios)
-  [React Router](https://reactrouter.com/web/guides/quick-start)
-  [TypeScript](https://www.typescriptlang.org/)


## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.
