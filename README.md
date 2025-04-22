# Curso TMW Git & GitHub 2025

Um curso para iniciantes aprenderem a trabalhar com versionamento de código e repositórios remotos com GitHub.

Além disso, trabalharemos com GitFlow ao final do curso e Virtual Studio Code.

Link do curso no YT:

[Curso Git 2025](https://youtube.com/@teomewhy)

# Fluxo de trabalho Git local

1. git checkout -b
2. cria ou atualiza os arquivos
3. git status
4. git add arquivos
5. git status
6. git commit -m "minha mensagem"
7. git checkout main
8. git merge <nova_branch>

# Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)

1. git clone
2. git checkout -b <nova_branch>
3. alterações de arquivos
4. git status
5. git add arquivos
6. git status
7. git commit -m "nova mensagem"
8. git push origin <nova_branch>
9. abri Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

# Fluxo de trabalho GitHub <> Local (projetos open-source)

1. Fork do projeto para seu próprio github
2. git clone
3. git checkout -b <nova_branch>
4. alterações de arquivos
5. git status
6. git add arquivos
7. git status
8. git commit -m "nova mensagem"
9. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>

# Nomeando branches

Nomes de branches são compostos de 3 partes:

1. type ou categoria do branch. Os types podem ser os seguintes:

	- docs: apenas mudanças de documentação;
	- feat: uma nova funcionalidade;
	- fix: a correção de um bug;
	- perf: mudança de código focada em melhorar performance;
	- refactor: mudança de código que não adiciona uma funcionalidade e também não corrigi um bug;
	- style: mudanças no código que não afetam seu significado (espaço em branco, formatação, ponto e vírgula, etc);
	- test: adicionar ou corrigir testes.

2. o que o branch faz em si.

3. Código da tarefa no Jira. Ex.: PL-123.