
<h1 align='center'>Reverse Shell 🧨</h1>

<p align='center'>
  <b>Star ⭐ if you want more</b><br>
<i>(English READM.md <a href="">here</a>)</i>
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/DictateurMiro/reverse-shell">
  <img src="https://img.shields.io/github/last-commit/DictateurMiro/reverse-shell">
  <img src="https://img.shields.io/github/stars/DictateurMiro/reverse-shell?color=7F9DE0&label=Stars">
  <img src="https://img.shields.io/github/forks/DictateurMiro/reverse-shell?color=7F9DE0&label=Forks">
</p>

---

<h2 align='center'>
Contact :
</h2>

<p align='center'>
<a href="https://t.me/empereurmiro">Telegram</a> 
</p>

---

## 🌙 Features
```sh-session
✔ Automatic connection to the server
✔ Automatic install module for client
✔ Beautiful UI
✔ Download and Upload file
```
---

## ✨ Fonctionnement d'un Reverse Shell
<img src="https://raw.githubusercontent.com/DictateurMiro/reverse-shell/main/images/fonctionnement%20reverse%20shell.png">

---

## 🎥 Video
<img src="https://raw.githubusercontent.com/DictateurMiro/reverse-shell/main/images/demo.gif">

---

## 🚀 Setup

```sh-session
> Download zip file (git clone https://github.com/DictateurMiro/reverse-shell.git)
> Open port 13037 on your vps
> Run server.py
> Send client.pyw (with the ip in the file) to your victim
> Enjoy!
```

---

## 🎉 Upcoming / enhancements

```sh-session
- Working with linux host
```

---

## 🎭 Useful command

```
- echo %cd% ||| Équivalent à 'pwd' sur Unix pour savoir dans quel dossier vous êtes
- cd .. && mkdir reverse ||| '&&' Permet d'exécuter une commande puis une autre, exemple 'cd ..' permet d'aller un dossier en arrière puis de créer un dossier.
- type file.txt ||| Équivalent à 'cat' sur Unix pour voir le contenu d'un fichier texte.
- echo "salut" >> salut.txt ||| Permet d'écrire "salut" dans un fichier qui va être appelé "salut.txt".
- tasklist ||| Permet de voir toutes les proccess en cours avec leur nom et leur PID 
- taskkill /F /PID [PID] ||| Permet de quitter un process via le PID

- upload [Chemin d'accès] ||| Permet d'envoyer un fichier sur le pc de la victime (Exemple: upload C:\Users\Miro\Desktop\token.py)
- download [Chemin d'accès] ||| Permet de récupérer un fichier du pc de la victime (Exemple: download C:\Users\Victime\Documents\motdepasse.txt)
```

---

## 📋 License

This project is licensed under the MIT License
```js
  ・Educational purpose only and all your consequences caused by you actions is your responsibility
  ・Selling this Free Tool is forbidden
  ・If you make a copy of this/or fork it, it must be open-source and have credits linking to this repo
```

---

## 💭 ChangeLog

```diff

v1.3.1 ⋮ 23/10/2023
+ Added (Useful command) in README.md to explain the commands and how to use them

v1.3 ⋮ 21/10/2023
+ Added 'download' command to download file from the client to the server download directory

v1.2 ⋮ 20/10/2023
+ Added 'upload' command to upload in the download directory of the client
- Remove 'keyboard' module on server because it's useless

v1.1 ⋮ 16/10/2023
+ Added a video to demonstrate
```

<p align="center">
  README inspired from xKiian
</p>