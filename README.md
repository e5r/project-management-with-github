Gerenciamento de Projetos com GitHub
====================================

## Requisitos

1. Tenha uma organização para agrupar todos os seus projetos
2. Tenha um repositório para agrupar a documentação do negócio
3. Cada outro repositório representará seus componentes de software
4. Configure as seguintes "labels":
   - `bug` para os defeitos
   - `user story` para as histórias de usuário
   - `epic` para os épicos de histórias de usuário
   - `initiative` para as iniciativas de épicos
   - `theme` para os temas negociais

## Como vai funcionar?

Na organização, crie o projeto para gerenciamento geral, pois lá criaremos nossos temas e épicos.
Também precisará ligar todos os repositórios de componentes de software e o repositório de
documentação do negócio a esse projeto.

Para cada outro repositório de componente de software também crie um projeto para gerenciar
exclusivamente seus cards.

Todos os temas, iniciativas e épicos serão criados como **issue** no repositório de documentação do negócio.
Os **bugs** e **user stories** serão criados em seus respectivos projetos, porém relacionados
nos épicos do repositório de documentação e no projeto central da organização.

Seguiremos a idéia proposta em: https://www.atlassian.com/agile/project-management/epics-stories-themes
