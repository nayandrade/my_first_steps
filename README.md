1 - Criei meu reposítório público
https://github.com/nayandrade/my_first_steps.git

2 - Criei um diretório chamado "my_first_steps", commitei e dei push, junto ao primeiro arquivo de texto da questão 3
$ mkdir my_first_steps
$ cd my_first_steps 
$ git init
$ git add .
$ git commit -m "primeiro push"
$ git remote add origin https://github.com/nayandrade/my_first_steps.git
$ git branch -M main
$ git push -u origin main

3 - Criei o arquivo de texto e o editei usando o nano
$ touch ola_mundo.txt
$ nano ola_mundo.txt

4 - Criei em meu diretório o arquivo .gitignore, adicionei a ele o arquivo que será ignorado e dei o push
$ touch .gitignore
$ nano .gitignore
serei_ignorado.txt
ctrl+x > y + enter
$ git add .
$ git commit -m "adição do .gitignore"
$ git push


