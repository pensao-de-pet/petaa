# Guia de contribuição

Estas regras existem para que muita gente consiga mexer no mesmo projeto sem se atrapalhar.

## Regra de ouro

**NINGUÉM faz commit direto na `main`.** Todo trabalho passa por uma branch e uma Pull Request (PR).

## Fluxo de trabalho

1. Escolha uma issue (ou crie uma) e se atribua a ela, para ninguém fazer a mesma tarefa em dobro.
2. Atualize sua cópia local:
   ```bash
   git checkout main
   git pull
   ```
3. Crie uma branch para a tarefa:
   ```bash
   git checkout -b tipo/descricao-curta
   ```
4. Faça seus commits, abra a PR e peça revisão.
5. Depois de aprovada, a PR é mesclada na `main` e a branch pode ser apagada.

## Nome das branches

Use `tipo/descricao-curta`, em minúsculas e com hífens:

- `feat/cadastro-disciplinas`
- `fix/erro-leitura-arquivo`
- `docs/atualiza-readme`
- `test/grafo-prerequisitos`

## Mensagens de commit

Curtas, no imperativo e dizendo o que mudou:

- `Adiciona cadastro de disciplinas`
- `Corrige leitura do arquivo de professores`

Evite mensagens como "ajustes" ou "arrumei".

## Pull Requests

- Uma PR deve resolver uma coisa só. PRs pequenas são revisadas mais rápido.
- Descreva o que mudou e referencie a issue (por exemplo, `Fecha #12`).
- Precisa de pelo menos **uma aprovação** de outra pessoa antes de mesclar.
- Quem revisa: seja gentil e específico. Quem recebeu a revisão: não leve para o lado pessoal, o objetivo é aprender juntos.

## Issues

- Use rótulos para facilitar a busca: `feat`, `bug`, `documentação`, `good first issue`.
- Escreva o que precisa ser feito e como saber que está pronto.
- Dúvida ou travamento? Comente na issue ou avise o seu squad.

## Boas práticas

- Rode o código e os testes antes de abrir a PR.
- Não suba senhas, tokens, dados reais de alunos nem arquivos pessoais.
- Comente o que não for óbvio e registre decisões importantes em `docs/`.
- Siga o estilo de código combinado pelo grupo (será definido junto com a linguagem principal).

## Rotina do grupo

- Reunião semanal curta, com três perguntas: o que eu fiz, o que vou fazer e o que me travou.
- Quem ficar sem conseguir avançar por mais de um dia deve pedir ajuda, sem esperar a reunião.
