# my_first_steps
modulo 2 - git - alpha edtech

---
## 1
Após criado a sua conta no GitHub, crie um repositório remoto público chamado “my_first_steps” e cole o link aqui;
```bash
https://github.com/gab1005/my_first_steps.git
ou clique <a href="https://github.com/gab1005/my_first_steps.git">aqui</a>
```

---
## 2
Crie um diretório em sua máquina e o vincule ao seu repositório remoto “my_first_steps” utilizando os comandos git necessários para a realização desta tarefa. 
```bash
Em uma pasta chamada tarefa11 abri o git bash e digitei:
"$ git clone https://github.com/gab1005/my_first_steps.git"
Foi baixado a pasta my_firts_steps, depois usei "git remote -v" para me retornar a origin:
"$ git remote -v"
origin  https://github.com/gab1005/my_first_steps.git (fetch)
origin  https://github.com/gab1005/my_first_steps.git (push)
```

---
## 3
Dentro do diretório em sua máquina, crie um arquivo chamado “ola_mundo.txt”, adicione algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa. 
```bash
git add . 
git commit -m "adicionando olar_mundo.txt a origin"
git push

```

---
## 4
Se não existir em seu diretório, adicione ao seu diretório um arquivo com o nome de “.gitignore”. Em seguida, crie um arquivo chamado “serei_ignorado.txt” e adicione algum texto dentro dele. Adicione a instrução ao arquivo “.gitignore” para que as alterações realizadas no arquivo “serei_ignorado.txt” não seja controlado pelo git. 

```bash
# Ignorar o arquivo "serei_ignorado.txt" - alpha edtech
serei_ignorado.txt
```

---
## 5
Dentro do seu diretório local, crie um arquivo chamado “README.md” e edite-o contendo todas as respostas aos enunciados das questões anteriores. Adicione-o ao seu repositório remoto utilizando os comandos git necessários para a realização desta tarefa.
```bash
Editei o README.md com as respostas, após fiz um commit e push padrão,
depois usei:
$ git add .
$ git commit -m ""colocar respostas no README.md"
$ git push
```