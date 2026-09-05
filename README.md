# Projeto de currículo

Este repositório serve para manter um currículo vivo, ajustado a partir de três fontes:

- `curriculum-initial.md`: versão base do currículo.
- arquivos da pasta `vagas/`: vagas de interesse copiadas para calibrar linguagem, prioridades e palavras-chave. Essa pasta fica fora do Git pelo `.gitignore`.
- `career-stories.md`: fatos, histórias e resultados reais da carreira, para fortalecer o currículo sem inventar experiência.

## Arquivos do currículo

- `curriculum.pt.md`: versão editorial em português.
- `curriculum.en.md`: versão editorial em inglês.
- `index.html`: versão para tela e impressão, com alternância PT/EN, CSS embutido e pronta para ser publicada pelo GitHub Pages.

## Como atualizar

1. Salve novas vagas como `vagas/example3.md`, `vagas/example4.md`, e assim por diante.
2. Adicione histórias e resultados em `career-stories.md`, de preferência com contexto, ação, tecnologia e impacto.
3. Peça para atualizar `curriculum.pt.md`, `curriculum.en.md` e `index.html` com base nos novos arquivos.
4. Mantenha as duas línguas conceitualmente equivalentes: as vagas podem influenciar prioridade, palavras-chave e ênfase, mas não devem criar duas narrativas diferentes de carreira.

## GitHub Pages

Para publicar pela raiz do repositório no GitHub Pages, o arquivo de entrada deve se chamar `index.html`. Por isso a versão HTML gerada usa esse nome.

## Critérios usados

- Priorizar aderência real às vagas, sem afirmar tecnologias que ainda não estejam sustentadas pelo histórico.
- Preservar a senioridade multidisciplinar: desenvolvimento, requisitos, dados, produto, agilidade e sustentação.
- Manter português e inglês alinhados em conceito, senioridade, escopo e fatos, mesmo quando a tradução não for literal.
- Reforçar palavras-chave ATS quando forem verdadeiras: C#, .NET, APIs REST, SQL Server, Oracle, Agile, Scrum, Kanban, CI/CD, testes, documentação, stakeholders e inglês.
- Manter uma versão visual limpa para impressão em PDF pelo navegador.
