# ☘️ Regras e Convenções Internas

## :seedling: Nomes de Branches

:rotating_light: **DEVEM** ser criadas a partir da branch principal, a **main**

**DEVEM** seguir o padrão **(tipo)/(nome_da_branch)**
  > Os tipos podem ser:
  > - bugfix: correção de problemas
  > - feat: criação de nova funcionalidade
  > - refactor: refatorações
  > - docs: criação de documentações

  > **Exemplo:** bugfix/create_user_layout

## :rocket: Mensagens de Commit

**DEVEM** seguir o padrão **(tipo):(mensagem)**
  > Os tipos podem ser:
  > - bugfix: correção de problemas
  > - feat: criação de nova funcionalidade
  > - refactor: refatorações
  > - docs: criação de documentações

  > **Exemplo:** feat: adicionado novo campo no formulario

**Recomendado** que sejam escritas em portugês

**Recomendado** que não sejam utilizados caracteres especiais e letras com acentos

## :hammer: Mensagem de PULL REQUEST

**DEVEM** seguir o padrão presente em [Padrão PULL REQUEST](https://github.com/starplast/.github/blob/main/.github/pull_request_template.md)

> **Obs**: Quando for criado um novo PR, o padrão automáticamente já será aplicado, então basta preencher com as informações de acordo com o contexto.


## :sparkles: Novos repositórios

:rotating_light: **TODOS** os novos repositórios e projetos **DEVEM**:
 - Ser desenvolvidos em:
    -  Se for uma API: **python ou typescript (nodejs)**
    -  Se for um aplicativo mobile: **typescript com React Native**
    -  Se for um website: **typescript com React**

- Conter testes unitários 

Os novos repositórios e projetos **PODEM** ser gerados a partir de templates pré estabelecidos

- Caso seja uma API simples em python: [Template base PYTHON](http://link)
- Caso seja uma API simples em typescript: [Template base TYPESCRIPT](https://github.com/starplast/template-api-nodejs)

> **Obs:** Os templates serão utilizados dependendo do contexto e complexidade da aplicação que será implementada. 

> Caso o novo sitema seja muito complexo, a arquitetura escolhida para os templates pode não comportar a compexidade requerida.

## :label: Arquivos README 

:rotating_light: **TODOS** os repositórios **devem** seguir o padrão de arquivos readme disponível em: [Padrão README](https://github.com/starplast/.github/blob/main/profile/Documentations/template_readme_file.md)

