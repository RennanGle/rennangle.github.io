# AGENTS

## Resumo do projeto

Este repositório contém a interface web e o backend em Google Apps Script da **Agenda de Gestão**. O objetivo é permitir o cadastro de tarefas e colaboradores, além de importar e exportar esses dados.

## Diretrizes de estilo e formatação

- Use indentação de 2 espaços.
- Limite de 100 caracteres por linha.
- Utilize [Prettier](https://prettier.io/) para formatar arquivos HTML, CSS e JavaScript.
- Prefira nomes de variáveis descritivos e em inglês.

## Executar o site localmente

1. Abra um terminal na raiz do projeto.
2. Execute `python3 -m http.server`.
3. Acesse `http://localhost:8000` no navegador para visualizar o site.

## Validar mudanças

- Formate o código com `npx prettier --write <arquivo>` antes de commitar.
- Execute `npx htmlhint index.html` para verificar a sintaxe HTML.
- Após aplicar mudanças, rode o servidor local e teste manualmente funcionalidades de importação e exportação.
