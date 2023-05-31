#REPOSITÓRIO LOCAL E REMOTO

* Local --> pasta que pedimos para o git observar na nossa máquina
* Remoto --> pasta na web que o git tbm obeserva 

#COMMANDS

* __git remote add {nome_do_repo_na_web} {link_do_repo}__ --> define um repo na web que irá se concetar ao nosso repo local
* __git remote remove {nome_do_repo_na_web}__ --> remove a ligação desse repo na web com o nosso repo local
* __git push {nome_do_repo_na_web} {branch}__ --> coloca uma branch local nesse repo da web
* 

#DUVIDAS

* Toda vez que damos um git push, salvamos o estado do repo no github. Dessa forma, toda vez que damos um push, atualizamos o estado salvo
na última vez que demos um push. No final, isso não reflete o estado atual do github, só o estado na nossa cópia, portanto devemos sempre dar um __git fetch__ para pegar o estado realmente atual