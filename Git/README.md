# CADT - Git


Comandos | Descrição
---------|----------
`git init` | Cria a estrutura do repositório para versionamento do projeto.
`git clone [repositório-remoto]` | Cria um clone local do repositório remoto no diretório onde o comando foi executado.
`git add -A` | Adiciona todos os arquivo modificados a árvore de trabalho tornando-os prontos para serem 'comitados'.
`git add [arquivo ou pasta]` | Adiciona um ou mais arquivo e pastas a árvore de trabalho.
`git remote --staged *` | Restaura o status de todos os arquivos, ou seja, retira-os da árvore de trabalho, dessa forma os arquivo não estão prontos para serem 'comitados'.
`git remote --staged [arquivo ou pasta]` | Restaura o status de arquivos ou pastas especificos.
`git commit -m "Mensagem"` | Cria um _commit_ dos arquivos da nossa árvore de trabalho, com uma mensagem para descrever as modificações.
`git status` | Mostra o status de tudo o que está acontecendo no nosso repositório local
`git remote add origin [repositório-remoto]` | Adiciona na configuração do nosso repositório iniciado com git init, a origen remota do nosso repositório.
`git push -u origin master`[^1] | Faz um 'push' de todos os commits do repositório local para o nosso repositório remoto configurado para a branch 'master'.
`git pull` | Literalmente puxa as alterações que estão no repositório remoto para o nosso repositório local.


[^1]: Utilizar o `-u` faz com que o nosso repositório fique "escutando" o branch especificado do nosso repositório remoto, dessa forma podemos usar os comando git push e pull sem nenhum outro parâmetro depois.