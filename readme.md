#Respuestas practica GIT

*�Qu� comando utilizaste en el paso 11? �Por qu�?
>> **R/.** git reset --hard HEAD~1
>>reset, indica que voy a deshacer el commit. --hard, es 
>>para que se pierda lo del workingcopy. HEAD~1, es para que sea al commit anterior

*�Qu� comando o comandos utilizaste en el paso 12? �Por qu�?
>> **R/.** git reflog
>>     a67836e HEAD@{0}: reset: moving to HEAD~1
>>     ab3f055 HEAD@{1}: commit: A�adir cambios al repositorio
>>     a67836e HEAD@{2}: checkout: moving from master to styled
>>     a67836e HEAD@{3}: commit (initial): Mover git-nuestro.md al repositorio
>>
>>     git reset --hard ab3f055
>> Le estoy indicando a git que vaya al hash del commit que deshice que es el que quiero rehacer

*El merge del paso 13, �Caus� alg�n conflicto? �Por qu�?
>> **R/.** No
>>   

*El merge del paso 19, �Caus� alg�n conflicto? �Por qu�?
> **R/.** Si
>>

*El merge del paso 21, �Caus� alg�n conflicto? �Por qu�?
>> **R/.** No
>> git realiz� un fast forward y resolvi� las diferencias automaticamente

*�Qu� comando o comandos utilizaste en el paso 25?
>> **R/.** git log --graph --pretty=oneline

*El merge del paso 26, �Podr�a ser fast forward? �Por qu�?
>> **R/.** Si 
>> Porque moverse hasta el commit de title se puede tipo lista (en secuencia) hasta llegar a ese commit

*�Qu� comando o comandos utilizaste en el paso 27?
>> **R/.**  git reset HEAD~1

*�Qu� comando o comandos utilizaste en el paso 28?
>> **R/.** git checkout git-nuestro.md

*�Qu� comando o comandos utilizaste en el paso 29?
>> **R/.** git branch -D title

*�Qu� comando o comandos utilizaste en el paso 30?
>> **R/.**  git reflog
>>			git checkout e4b45e6		

*�Qu� comando o comandos usaste en el paso 32?
>> **R/.** git reflog
>>		   git checkout a67836e

*�Qu� comando o comandos usaste en el punto 33?
>> **R/.** git reflog
>>		   git checkout c467ffe
