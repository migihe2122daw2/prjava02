
  1- CREAR BRANCA:
  
    git checkout -b branca00
    
  5- TORNAR A LA BRANCA main:
  
    git checkout main
    git status
    git log
    
  6- VISUALITZAR CONTIGUT:
  
    No es veu l'ultima linea perque els canvis s'han realitzat a la branca00, per tant no afecta a la branca main.
    
  7- TORNAR A LA BRANCA branca00:
  
    git checkout branca00
    code .\Prjava02.java
    
    Si es pot veure l'ulyima linea perque estem  la branca on s'havia modificat abans.
    
  10b- FUSIONAR BRANQUES:
    
    git merge branca00
    
  12- BRANCA MAIN:
  
    git push
    
    Només s'ha actulitzat la branca main perque es a la que li hem fet el push
    
  14a- PUSH A LA BRANCA branca01:
  
    git push --set-upstream origin branca01
    
  14c - A QUANTS COMMITS DE DISTANCIA ESTA LA BRANCA MAIN
  
    A 1 commit
    
    
