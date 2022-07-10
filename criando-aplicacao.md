- Arquivo json trará todas as dependências da nossa aplicação.
-- Podemos adicionar dependências que podem ser úteis para desenvolvimento.
-- Scripts podem ajudar na hora de fazer determinadas atividades.

- Arquivo angular.json contém as informações globais da aplicação.
-- Define qual arquivo vamos usar para inicializar a aplicação.
-- Index.html define a página base da nossa aplicação.
-- Main.ts serve para fazermos o start da aplicação.
--- Vai ser uma hook que recebe o módulo raiz para inicialização. 

- Node_modules traz todas as dependências da aplicação.
- A maioria dos arquivos que são modificados fazem parte da pasta src.
- Styles: qualquer coisa que seja definida aqui pode ser aplicada para os componentes.
- Assets traz os arquivos estáticos (isso pode ser visto no arquivo angular.json).

- App.module.ts é a partir dele que se faz a leitura do componente pai -> app.component.ts (componente responsável por envelopar todos os componentes criados).
