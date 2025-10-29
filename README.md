# Domentontação de teste Git

## Inicializar um deposito

```bash
git init
git remote add origin SSH_REPO
```

## Rescrever um commit (boa maneiras)

```
Titulo de commit

Descrição do sonno commit com as informações de evolução de projet
```

## Enviar um commit em depot a distancia

```bash
git add .
git commit -m "Um comentario"
git push origin main
```

## Criação de um branch

```bash
git checkout -b nome
```

para melhor pratica, vamos integrar a noção de revue de codigo. por isso, vamos criar um branch, fazer a modificação, enviar no depot distante, depois criar um pull request para depir um revue de codigo.