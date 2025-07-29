# Projeto de Recuperação — Controlo de Versões com Git

## Descrição do Projeto

Este é um projeto simples criado para demonstrar o uso do Git e GitHub com práticas de controlo de versões. O objetivo foi simular um ambiente de desenvolvimento colaborativo, utilizando funcionalidades como branches, pull requests, resolução de conflitos e gestão de tarefas com Kanban.

O projeto contém páginas HTML separadas com conteúdo básico:
- `index.html`: Página principal
- `contact.html`: Formulário de contacto
- `about.html`: Página "Sobre nós"
- `hobby.html`: Página "Hobbies"

---

## Workflow Utilizado

O fluxo de trabalho usado foi baseado em Git Flow simplificado:

1. Criação da branch `main` com o ficheiro base `index.html`.
2. Criação de 3 branches adicionais: `feature/contact-form`, `feature/about` e `feature/hobby`.
3. Alterações realizadas em cada branch foram submetidas via Pull Request.
4. Simulação de revisões de código nos PRs.
5. Um conflito foi intencionalmente criado e resolvido entre `index.html` na `main` e numa branch funcional.
6. Todas as funcionalidades foram integradas na `main`.

---

## Lista de comandos Git usados

```bash
git init
git clone <link-do-repositório>
git status
git add .
git commit -m "mensagem"
git push origin main
git branch feature/contact
git checkout feature/contact
git checkout -b feature/about
git merge main
git pull origin main
git push origin feature/about

```

## Quadro Kanban

![Quadro Kanban](images/kanbanv2.png)
![Quadro Kanban2](images/kanban2.png)

## Reflexão do Projeto 

Este projeto foi fundamental para consolidar os meus conhecimentos de Git e GitHub. A criação de branches ajudou a separar funcionalidades e evitou conflitos diretos. Ao fazer pull requests e simular revisões de código, ganhei experiência no processo colaborativo que é comum em equipas de desenvolvimento.

A resolução de conflitos foi especialmente útil para perceber como o Git trata alterações simultâneas em ficheiros. Apesar de inicialmente parecer confuso, consegui perceber a lógica e resolver o problema com sucesso.

O uso do Kanban ajudou na gestão de tarefas e permitiu visualizar o progresso de forma clara. Senti que esta organização facilitou o foco e a distribuição equilibrada do trabalho. Em geral, foi uma experiência positiva e prática, que me preparou melhor para projetos reais.
