# Teste para candidatos à vaga de desenvolvedor Front-End

Nesta etapa, você deverá desenvolver uma tela de listagem de usuários e outra para gerenciar as informações desses usuários. Ao final, a aplicação deve exibir no console um JSON com os dados atualizados do usuário, que serão enviados para uma API.

Você pode utilizar a [API DummyJSON](https://dummyjson.com/docs/users) para obter uma lista de usuários. Existem outros endpoints relacionados ao usuário na documentação, caso necessário.

## Desafio:

- Crie uma tela que liste os usuários de uma plataforma:
  - Apresente na listagem informações relevantes de cada usuário para facilitar a identificação;
  - Ao selecionar um usuário da lista, deve-se navegar para uma tela de edição e detalhes;
- Crie uma tela que apresente os detalhes de um usuário;
  - Os dados do usuário devem ser editáveis, com campos de input correspondentes;
  - Os campos devem incluir validação de dados;
  - É necessário ter pelo menos 8 campos editáveis;
  - Criar botões de cancelar e salvar edição:
    - Botão de cancelar volta o usuário para a lista;
    - Botão de salvar deve jogar no console o JSON que seria utilizado para enviar no payload de uma API:
    ```json
    {
    	"id": 1,
    	"firstName": "John",
    	"lastName": "Doe",
    	...
    }
    ```

## Instruções:

1. Para iniciar o teste, faça um fork deste repositório;
2. Crie um branch com o seu nome;
3. Crie o diretório /octa-app e desenvolva a aplicação nesse diretório;
4. Após terminar, submeta um pull request e aguarde seu feedback.

   Observação: Se você apenas clonar o repositório não vai conseguir fazer push e depois vai ser mais complicado fazer o pull request.

## Requisitos:

- Crie um cliente HTTP com Axios ou Fetch;
- Desenvolva uma experiência de navegação agradável e fluida;
- Utiliza uma SPA com rotas nomeadas;
- Utilize commits atômicos;
- Crie um arquivo com todas as instruções necessárias para rodar o projeto;

## Você pode:

- Utilizar CSS puro, pré-processador, pós-processador ou framework CSS;
- Utilizar qualquer framework JavaScript;
  - Utilizar biblioteca de componentes e ícones;
  - Utilizar ferramentas de build;
- Utilizar biblioteca de gerenciamento de estado;

## O que nós vamos avaliar:

- HTML semântico;
- Boas práticas de SEO;
- Componentização;
- Navegação pela aplicação;
- Funcionamento correto do projeto sem erros;
- Tratamento de dados;
- Qualidade do código;
- Legibilidade;
- Consistência no estilo do código;

## Ganha pontos extras se:

- Criar testes unitários;
- Utilizar Vue.js;
- Utilizar TypeScript;
