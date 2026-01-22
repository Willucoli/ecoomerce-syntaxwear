# SyntaxWear - E-commerce de Tênis e Sneakers



Bem-vindo ao repositório do SyntaxWear, um projeto de e-commerce focado na venda de tênis e sneakers. Este projeto foi desenvolvido como parte do DevQuest 2026, com o objetivo de criar uma interface de usuário moderna e responsiva para uma loja online.

## 🚀 Começando

Para visualizar o projeto, não é necessário nenhuma instalação complexa. Basta clonar o repositório e abrir o arquivo `index.html` em seu navegador de preferência, Ou acessar o link do gitghub pages

```bash 
git https://willucoli.github.io/ecoomerce-syntaxwear/

 git https://github.com/Willucoli/ecoomerce-syntaxwear.git
cd ecoomerce-syntaxwear
# Abra o arquivo index.html no navegador
```

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as seguintes tecnologias:

- **HTML5**: Para a estruturação do conteúdo e semântica da página.
- **CSS3**: Para a estilização e layout, seguindo a metodologia BEM (Block, Element, Modifier) para a organização das classes.
- **Git e GitHub**: Para o versionamento do código e gerenciamento do projeto.

## 📂 Estrutura de Arquivos

A estrutura de arquivos do projeto foi organizada de forma a separar as responsabilidades e facilitar a manutenção:

```
ecoomerce-syntaxwear/
├── index.html
├── README.md
└── src/
    ├── css/
    │   ├── base.css
    │   ├── reset.css
    │   ├── variables.css
    │   └── components/
    │       ├── header.css
    │       ├── hero.css
    │       ├── product-category.css
    │       └── product-grid.css
    └── images/
        ├── banners/
        │   └── hero.jpg
        ├── favicon/
        ├── icons/
        │   ├── bag.svg
        │   ├── help.svg
        │   └── user.svg
        ├── logo/
        │   └── Logo.svg
        └── products/
            ├── ...
```

- **`index.html`**: O coração da aplicação, este arquivo contém toda a estrutura HTML da página principal.
- **`src/css/`**: Esta pasta contém todos os arquivos de estilização.
  - **`reset.css`**: Um arquivo para resetar os estilos padrão do navegador, garantindo uma aparência consistente em diferentes browsers.
  - **`variables.css`**: Define as variáveis CSS globais do projeto, como cores, fontes e tamanhos, para facilitar a manutenção do tema.
  - **`base.css`**: Contém os estilos base aplicados a todo o projeto, como a tipografia e estilos de corpo.
  - **`components/`**: Cada arquivo nesta pasta corresponde a um componente específico da página, como o cabeçalho (`header.css`) ou a seção de herói (`hero.css`), promovendo a modularidade.
- **`src/images/`**: Repositório de todas as mídias visuais.
  - **`banners/`**: Imagens para banners e seções de destaque.
  - **`icons/`**: Ícones utilizados na interface, como os de usuário, sacola e ajuda.
  - **`logo/`**: Onde o logo da marca é guardado.
  - **`products/`**: Imagens dos produtos que são vendidos na loja.

## 🌟 Principais Funcionalidades

- **Layout Responsivo**: O site foi desenhado para ser totalmente acessível e funcional em diversos tamanhos de tela, de desktops a dispositivos móveis.
- **Navegação Intuitiva**: Um menu claro e categorias bem definidas permitem que o usuário encontre facilmente o que procura.
- **Componentização**: O estilo do site é dividido em componentes, o que torna o código mais limpo, reutilizável e fácil de dar manutenção.

## 🤝 Como Contribuir

Contribuições são o que fazem a comunidade open source um lugar incrível para aprender, inspirar e criar. Qualquer contribuição que você fizer será **muito apreciada**.

1. Faça um *fork* do projeto
2. Crie uma *branch* para sua modificação (`git checkout -b feature/sua-feature`)
3. Faça o *commit* de suas mudanças (`git commit -m 'Adicionando uma feature incrível'`)
4. Faça o *push* para a *branch* (`git push origin feature/sua-feature`)
5. Abra um *Pull Request*
