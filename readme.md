# Revisão GIT

### Comandos que eu já sei



- [x] git config --global user.name "nome"
- [x] git config --global user.email email
- [x] git config --global core.editor code --wait
- [x] git config --list 
- [x] git init (inicializa um novo repositório na minha máquina local)
- [x] git branch -M main (Muda a branch principal do seu repositório (master) para main)
- [x] git add file ou git add . (coloca os arquivos em modo stage)
- [x] git commit -m "meu commit" (identifica as alterações)
- [x] git remote add origin https://github.com/my_account/repository_name.git

* Aqui é feita a criação de um repositório de apelido origin que irá receber os arquivos do seu repositório local* 

- [x] git push -u origin main (joga o seus arquivos da máquina local no repositório remoto)

- [x] git log (permite a visualização do histórico de alterações)

- [x] git log --oneline (mostra as informações em uma só linha)

- [x] git log -p (mostra o estado anterior à alteração e o posterior)

### Comandos que eu ainda não sei

- [] git commit --amend (para corrigir commits errados)
- [] git push origin --delete nome_branch_antiga (ex: master) seguido de git push origin branch_atual
- [] git add arquivo_esquecido + git commit --amend (para adicionar um arquivo que você esqueceu no último commit)

* ammend: quer dizer corrigir, arrumar *

- [] git reset arquivo_que_vc_mandou_sem_querer (ex: senhas.txt)

Eu já até comitei o arquivo e agora?

- [] git reset --soft HEAD~1 (Retorna para o estado antes do commit) / git reset arquivo.txt

- [] git branch nova_ramificacao (cria uma nova ramificacao que aponta para onde HEAD está apontando)
- [] git checkout -b nova_ramificacao (HEAD agora aponta para essa branch)
- [] git reflog (histórico de tudo que fizemos desde a inicialização do repositório local)


