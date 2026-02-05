Regras:



Parte 1 – Clonar e preparar ambiente

Clonar o repositório e atualizar a branch develop.





Parte 2 – Criar branch de trabalho

Criar branch no padrão feature/seu-nome.

Comando: git checkout -b feature/seu-nome



Parte 3 – Regras de commits

Cada alteração relevante deve gerar um commit. Não agrupar tudo em um único commit.



Parte 4 – Tarefas obrigatórias

1\) Editar README.md colocando o seu nome completo.

2\) Criar uma receita em receitas/salgados e receitas/doces.

3\) Criar diário em docs/diario-de-bordo/seu-nome.md (Coloque suas dificuldades e o que vc conseguiu aprender de novo).

4\) Editar conflitos/edite-aqui.md e preencher uma linha numerada.



Parte 5 – Enviar branch



Após cada tarefa você deve enviar ao repositório remoto, não pode fazer as 4 juntas e depois enviar, tem que ser uma por vez.



Parte 6 – Atualizar branch com develop

git pull origin develop

Resolver conflitos manualmente se ocorrerem.



Parte 7 – Fluxo final

Quando todos finalizarem, façam o git flow.

Merge feature → develop → release → main.

