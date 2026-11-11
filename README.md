# 🎮 HitBox — Portal de Notícias e Mídia Gamer

O **HitBox** é um portal web interativo voltado para publicação de notícias, artigos e mídias sobre o universo de jogos eletrônicos. O sistema foi desenvolvido com foco em desempenho, design responsivo e navegação fluida.

🌐 **Acesse a aplicação:** [hitbox.blog](https://www.hitbox.blog)

---

## 🏗️ Arquitetura e Estrutura de Pastas

O repositório está organizado de forma modular, dividindo as responsabilidades da interface e da lógica de servidor:

```text
hitbox/
├── assets/             # Recursos estáticos
│   ├── css/            # Folhas de estilo e temas responsivos (CSS Grid / Flexbox)
│   ├── js/             # Scripts client-side (interatividade e requisições HTTP)
│   └── img/            # Mídias e artefatos visuais da plataforma
├── config/             # Módulos de conexão e parâmetros de runtime
├── database/           # Scripts de schema, migrations e relacionamentos SQL
├── views/              # Templates de interface e componentes visuais de renderização
├── index.php           # Entry point (roteador principal da aplicação)
└── README.md           # Documentação do repositório
```
🛠️ Tecnologias Utilizadas
Frontend: HTML5 semântico, CSS3 (Grid e Flexbox) e Vanilla JavaScript para manipulação assíncrona do DOM.

Backend: PHP para processamento do fluxo de dados, roteamento de requisições e regras de negócio.

Banco de Dados: PostgreSQL para persistência relacional de artigos, categorias e autores.

Infraestrutura: Hospedagem em ambiente Cloud (Render) com roteamento via DNS gerenciado e suporte HTTPS.

📌 Principais Funcionalidades
Feed Dinâmico: Exibição de artigos e matérias organizadas por categorias.

Leitura Otimizada: Layout focado na legibilidade em telas desktop e mobile.

Gerenciamento de Conteúdo: Estrutura modular para atualização contínua do portal.
