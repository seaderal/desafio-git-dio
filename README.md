**# desafio git para a DIO** 

primeiro, criei o repositório local na minha máquina.```git init ```

após, renomeei a branch para main, assim não ocorre problemas na hora de conciliar a branch main do repositório remoto com a o local. no meu caso, no meu git bash,
ela é branch master como default. ``` git branch -m main ``` 

fiz a ligação do repositório local com o remoto ``` git remote add origin https://github.com/seaderal/desafio-git-dio.git ```

criei as pastas do meu curso e inseri o arquivo de anotações dentro de cada uma delas. ```git add .```

fiz o primeiro commit ``` git commit -m "arquivo de anotações em todas as pastas" ```

finalizei com ```git push origin main ```
