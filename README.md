<img src="https://github.com/gusantos1/icons/blob/main/Git-Logo-2Color.png" width="50%">  

# 1° Configurações usuário  
**Definindo nome do usuário no git**:`$ git config --global user.name "seu_nome"`       
**Definindo email do usuário no git**:`$ git config --global user.email "seu_email"`     
**Definindo editor do usuário no git**: `$ git config --global core.editor pycharm(exemplo)`  
**Visualizando configuração do usuário**: `$ git config --list`

---

# 2° Sobre git
**Criando repositório do git (diretamente local)**: `$ git init`  
**Conectando com o github**: `$ git remote add origin link_do_github`
    
**Visualizando Branch**: `$ git branch`  
**Novo Branch**: `$ git branch novo_branch`  
**Mudando Branch**: `$ git checkout escolha_seu_branch`  
**Deletando um Branch(remoto e local)**:
* _Remoto:_ `$ git push origin :nome_do_branch`
* _Local:_ `$ git branch -D nome_do_branch`   
   
**Atualizar repositório**: `$ git status`      
**Adicionando arquivos**: `$ git add -A ou add nome_do_arquivo`    
**Adicionando um commit**: `$ git commit -m "comentario_sobre_alteracao_feita"`    
**Dando Push**:`$ git push -u origin branch_que_está_trabalhando`  
**Puxando o log de um git**: `$ git log`    
**Mostrando as modificações no git**: `$ git diff ou git diff --name-only`  
**Mostrando servidores remotos**: `$ git remote -v`  
**Atualizando repositório(Pull)**: `$ git pull origin nome_do_branch`  
**fatal: refusing to merge unrelated histories**: `$ gitgit pull origin main --allow-unrelated-histories`
**Clonar um projeto**: `$ git clone link_github`  
     
**Revertendo modificações**:  
* `$ git revert --no-edit commit_desejado` _(basicamente é como voltar no tempo deixando salvo o que estava dando problema, o commit ainda fica salvo no git log)_  
* `$ git reset --soft commit_desejado` _(volta pro estado antes do commit da alteração anterior)_ 
* `$ git reset --mixed commit_desejado` _(igual o soft mas precisa dar o add)_ 
* `$ git reset --hard commit_desejado` _(basicamente é como voltar no tempo mas você perde o que foi feito anteriormente, o commit não aparecerá mais no git log)_ 


---

## Contato
*Quer trocar uma idéia, ficou com alguma dúvida ou tem algo que eu posso te ajudar ? **Fique a vontade!** :wink:*
|Canais||
|--|---|
<img src="https://github.com/gusantos1/icons/blob/main/gmail.jpg" width="20" height="20"> |*gusantos.ok@gmail.com*
<img src="https://github.com/gusantos1/icons/blob/main/telegram.svg" width="20" height="20"> | *guilhermemak*
<img src="https://github.com/gusantos1/icons/blob/main/010-linkedin.svg" width="20" height="20"> | *gusantosdev*

---
