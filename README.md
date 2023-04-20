# Desafio.DIO.anotacao
Anotação da aula sobre Git e GitHub

Este desafio tem como objetivo adicionar no GitHub um arquivo .txt contendo minhas anotações sobre as aulas de Git e GitHub.
Todo o conteúdo foi escrito em bloco de notas.

Minha maior dificuldade foi fazer o push para o repositório remoto. Pelos seguintes motivos:
- Primeiro, assim que eu fazia o push para o github, percebi que a branch no github estava como MAIN enquanto no Git estava como MASTER. Assim, no GitHub, os meus arquivos apareciam numa trilha filha e não na principal.
- Segundo, No Git, pesquisei a documentação oficial e vários fóruns na internet para verifcar como poderia alterar a minha branch padrão. O jeito mais prático que achei foi alterar aqui, diretamente no GitHub.
- Terceiro, no Git, a branch alterava automaticamente para MAIN. Ainda não entendi o pôrque, mas vou descobrir e escrever aqui,
- Quart, a pior parte. Fiz um PULL e Clonei o primeiro commit que empurrei para o GitHub. Neste fiz as alterações que aqui já se encontram. Mas, por alguma razão, só dava erro no momento de dar o  PUSH. Abaixo está o erro:
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/soares-r/Desafio.DIO.anotacao.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

Tentei vários comandos. Pelo Stack Overflow, vi o seguinte comando: git push -f origin main. Fiquei horas tentando realizar o novo PUSH. Mas, este só funcionou depois que eu o forcei. E aqui estamos!

Gostei do desafio! Vou precisar melhorar e muito no modo como lido com essa ferramenta. Mas, estou contente comigo, pois consegui entregar o desafio proposto.
