# Projeto Front-End

Este é um projeto de desenvolvimento front-end criado como parte de um estudo prático sobre as tecnologias fundamentais da web. O objetivo é construir uma interface de usuário moderna e funcional, aplicando as melhores práticas de organização de código e componentização.

## 🎯 Objetivos

- **Praticar HTML, CSS e JavaScript:** Solidificar o conhecimento na trinca fundamental do desenvolvimento web.
- **Estruturação de Projetos:** Aplicar um padrão de arquitetura de pastas (`assets`, `components`, `pages`) para um código mais limpo e manutenível.
- **Componentização:** Desenvolver partes da interface como componentes reutilizáveis.
- **Design Responsivo:** Garantir que a aplicação seja visualmente agradável em diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Para a estrutura semântica do conteúdo.
- **CSS3:** Para estilização e layout.
- **JavaScript:** Para interatividade.

## 📂 Estrutura de Pastas

O projeto segue uma arquitetura de pastas pensada para facilitar a manutenção e a escalabilidade:

```bash
/
├── 📁 assets/              # Arquivos estáticos (imagens, fontes, etc.)
│   ├── 📁 css/             # Folhas de estilo globais e reset
│   ├── 📁 fonts/           # Arquivos de fontes
│   ├── 📁 icons/           # Ícones (SVG, PNG, etc.)
│   ├── 📁 images/          # Imagens utilizadas no projeto
│   └── 📁 js/              # Scripts globais
│
├── 📁 components/          # Componentes reutilizáveis (header, footer, card, button)
│
├── 📁 pages/               # Páginas principais da aplicação (home, sobre, contato)
│
├── 📄 .gitignore           # Arquivos e pastas ignorados pelo Git
├── 📄 index.html           # Página inicial/ponto de entrada
└── 📄 README.md            # Documentação do projeto
```

- **`/assets`**: Contém todos os recursos estáticos. A estilização global, fontes, ícones e imagens ficam aqui.
- **`/components`**: Cada parte reutilizável da interface, como um cabeçalho ou um rodapé, deve ser desenvolvida aqui, possivelmente com seu próprio HTML, CSS e JS.
- **`/pages`**: Contém os arquivos HTML que representam as diferentes páginas do site. Essas páginas importam e organizam os componentes.
