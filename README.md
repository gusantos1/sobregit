<img src="https://github.com/gusantos1/icons/blob/main/Git-Logo-2Color.png" width="50%">  

# 1° Configurações usuário  
**Definindo nome do usuário no git**:`$ git config --global user.name "seu_nome"`       
**Definindo email do usuário no git**:`$ git config --global user.email "seu_email"`     
**Definindo editor do usuário no git**: `$ git config --global core.editor pycharm(exemplo)`  
**Visualizando configuração do usuário**: `$ git config --list`

---

# 2° Conectando com a repo já criada
**1. Criando repositório local**: `$ git init`  
**2. Adicionando remote da repo criada pela ui do github**: `$ git remote add origin {link_https}`
**3. Atualizando repositório local:** `$ git fetch`
**4. Sincronizando as branches remotes com local:** `$ git switch --track origin/{nome_da_branch}` 
**5. Atualizando branch:** `$ git pull ou git pull --rebase`
**6. Push:** `$ git push origin {nome_da_branch}` 
    
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
**fatal: refusing to merge unrelated histories**: `$ git pull origin main --allow-unrelated-histories`
**Clonar um projeto**: `$ git clone link_github`  
     
**Revertendo modificações**:  
* `$ git revert --no-edit commit_desejado` _(basicamente é como voltar no tempo deixando salvo o que estava dando problema, o commit ainda fica salvo no git log)_  
* `$ git reset --soft commit_desejado` _(volta pro estado antes do commit da alteração anterior)_ 
* `$ git reset --mixed commit_desejado` _(igual o soft mas precisa dar o add)_ 
* `$ git reset --hard commit_desejado` _(basicamente é como voltar no tempo mas você perde o que foi feito anteriormente, o commit não aparecerá mais no git log)_ 

---
