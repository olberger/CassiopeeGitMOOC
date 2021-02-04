# CassiopeeGitMOOC

Dans notre langage :  
  - Un commit est représenté par un ->  
  - Un merge est représenté par un -- dans la branche depuis laquelle le merge est effectué, et un -> dans la branche vers lequel cela se fait.

Exemple :  
```
origin/branchdistante1  | 1 -> 11 -- 12  
master                  | 1 -> 2 -> 3 -> 5 -> 8 -> 9 -> 10 -- 11 -> 12  
branche1                | 2 -> 4 -> 6 -- 10  
branche2                | 3 -> 7 -- 8
```
