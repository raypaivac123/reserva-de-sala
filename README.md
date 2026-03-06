# Sistema de Reserva e Gestão de Salas

Projeto desenvolvido com **HTML, CSS e JavaScript** para auxiliar no gerenciamento acadêmico de turmas, unidades curriculares e uso de espaços, com foco em organização, praticidade e controle das informações.

## Sobre o projeto

O sistema foi criado para facilitar a gestão de salas e turmas em um contexto educacional, permitindo cadastrar turmas, vincular unidades curriculares e acompanhar informações relacionadas ao andamento das aulas.

A proposta é oferecer uma navegação simples e objetiva, com uma interface leve e funcional, utilizando apenas tecnologias front-end.

## Funcionalidades

- Login e controle de sessão do usuário
- Portal principal do sistema
- Cadastro e listagem de turmas
- Cadastro de unidades curriculares (UCs)
- Associação de UCs a uma turma específica
- Acesso à área de frequência
- Armazenamento local dos dados com `localStorage`
- Tela de confirmação de cadastro

## Tecnologias utilizadas

- **HTML5**
- **CSS3**
- **JavaScript**
- **LocalStorage** para persistência de dados no navegador

## Estrutura do projeto

```bash
reseva-de-salas/
├── css/
│   └── style.css
├── img/
├── js/
│   ├── alunos.js
│   ├── auth.js
│   ├── frequencia.js
│   ├── index.html
│   ├── script.js
│   ├── storage.js
│   ├── turmas.js
│   └── ucs.js
├── cadastro-sucesso.html
├── portal.html
├── turma.html
├── uc.html
└── README.md
