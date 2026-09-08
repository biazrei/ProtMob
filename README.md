# Atividade Prototipo Mobile e BEM
Protótipo Mobile e Organização dos Estilos com BEM

## Integrantes

- Beatriz Rei Ribeiro
- Gabrielle Rodrigues de Alencar
- Julia Leão de Oliveira
- Melissa Oliveira Dias
- Pietro Silva Soares

## Descrição da aplicação

HABIT é uma aplicação de publicação de conteúdo (blog). O usuário navega por
categorias, lê posts em destaque, pesquisa conteúdos e pode assinar
uma newsletter. Usuários autenticados têm acesso a uma área de perfil, onde acompanham
suas postagens e comentários. Administradores têm acesso a um painel para gerenciar
categorias, criar e revisar posts, moderar comentários, gerenciar usuários e definir as
escolhas do editor.

## Estrutura de Telas

- **tela 1:** Home
- **tela 2:** Categoria (Techno)
- **tela 3:** Destaques
- **tela 4:** Assinar Newsletter
- **tela 5:** Admin — Categorias
- **tela 6:** Admin — Criar Post
- **tela 7:** Admin — Escolhas do Editor
- **tela 8:** Admin — Usuários
- **tela 9:** Admin — Fila de revisão
- **tela 10:** Admin — Fila de comentários
- **tela 11:** Resultados de busca
- **tela 12:** Login
- **tela 13:** Criar Conta
- **tela 14:** Perfil

## Componentes Identificados

- **Header** — Todas as telas (única)
- **Footer** — Todas as telas (única)
- **Navigation** — Telas públicas (única)
- **Button** — Todas as telas (primary, secondary)
- **Card** — Home, Categoria, Destaques, Busca (padrão, featured)
- **Category-link** — Home - Todas as Categorias (única)
- **Form** — Criar Post, Login, Cadastro, Newsletter, campos de busca (campo de texto, textarea)
- **Admin (menu + indicadores)** — Todas as telas administrativas (5 a 10) (menu aberto, menu fechado)
- **List** — Escolhas do Editor, Usuários, Fila de revisão, Fila de comentários, Busca (1 linha para posts, múltiplas linhas para usuários)
- **Recommendation** — Home - Escolhas do Editor (única)

## Organização dos arquivos

```text
.
├── HTML/                         → Páginas de exemplo/vitrine dos componentes
│   ├── adminprofile.html
│   ├── buttons.html
│   ├── cards.html
│   ├── form.html
│   └── header-footer.html
├── css/                          → Estilos organizados por componente (Padrão BEM)
│   ├── admin.css
│   ├── buttons.css
│   ├── card-destaque.css
│   ├── card-horizontal.css
│   ├── card.css
│   ├── categories.css
│   ├── category-link.css
│   ├── checkbox.css
│   ├── footer.css
│   ├── form.css
│   ├── header.css
│   ├── indicators.css
│   ├── input.css
│   ├── menu.css
│   ├── navigation.css
│   ├── profile.css
│   ├── recommendation-list.css
│   └── variables.css
├── docs/                         → Proposta da atividade e materiais de apoio
│   ├── image.png
│   ├── proposta-atividade.pdf
│   └── tabela.png
├── wireframes/                   → As 14 telas mobile em baixa fidelidade (Imagens)
│   ├── tela 1.png
│   ├── tela 2.png
│   ├── tela 3.png
│   ├── tela 4.png
│   ├── tela 5.png
│   ├── tela 6.png
│   ├── tela 7.png
│   ├── tela 8.png
│   ├── tela 9.png
│   ├── tela 10.png
│   ├── tela 11.png
│   ├── tela 12.png
│   ├── tela 13.png
│   └── tela 14.png
├── .gitattributes
├── LICENSE
└── README.md
