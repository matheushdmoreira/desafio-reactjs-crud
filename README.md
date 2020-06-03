<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 10: GoRestaurant Web
</h3>

<blockquote align="center">“O tempo que leva para realizar seus sonhos vai passar de qualquer forma”!</blockquote>

## :rocket: Sobre o desafio

Nesse desafio, foi desenvolvido mais uma aplicação, a GoRestaurant. Pratiquei o que foi aprendido até agora no React.js junto com TypeScript, praticando o conceito de CRUD (Create, Read, Update, Delete).

Essa será uma aplicação que se conecta a uma fake API, e exibe os pratos de comida criados e permite a criação, remoção e atualização desses pratos.

### Funcionalidades da aplicação

- **`Listar os pratos de comida da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem, com o campo `title`, `value`, e  `description` e `available` de todos os pratos de comida que estão cadastrados na sua API.

**Dica**: Para exibir se o prato de comida está disponível ou não, você pode validar o campo `available` que é retornado da API e exibir `Disponível` caso seja true, e `Indisponível` caso seja false.

- **`Adicionar novos pratos de comida a sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Novo Prato` no Header. Esse modal deve ser responsável por cadastrar uma nova `food` passando os campos `image`, `name`, `description`, `value`.

**Dica 1**: O campo image deve ser uma URL, deixamos três URL de imagens como exemplo no arquivo server.json.

**Dica 2**: Ao enviar o request para sua API para salvar a `food`, lembre-se sempre de setar o campo `available` como true.

- **`Editar pratos de comida da sua API`**: Em sua página Dashboard você deve abrir um modal ao clicar no botão `Editar Prato`. Esse modal deve ser responsável por editar uma `food` passando os campos `image`, `name`, `description`, `value`.

**Dica**: Ao editar um item, quando for envia-lo para o backend, lembre de copiar os dados anteriores como o `available` e o `id`, ou eles serão  perdidos do seu arquivo server.json.

- **`Remover pratos de comida da sua API`**: Em sua página Dashboard você deve remover um prato de comida ao clicar no botão com ícone de lixeira no componente Food.

**Dica**: Após remover o item da sua API, lembre-se de remover ele também da listagem.

- **`Alterar disponibilidade dos pratos de comida da sua API`**: Em sua página Dashboard você deve alterar a disponibilidade de um prato de comida ao clicar no switch que é controlado pelo valor de `available`.

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com 💜 by Rocketseat
