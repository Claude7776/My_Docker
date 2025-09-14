# 🚀 Mon Premier Dockerfile : Hello World !

Ce projet est mon tout premier essai avec **Docker**.  
Il contient un `Dockerfile` simple qui exécute un script affichant **"Hello World !"** dans le terminal.  

---

## 📂 Contenu du projet
- `Dockerfile` → définit l’image Docker et l’instruction à exécuter  
- `README.md` → ce fichier d’explication  

---

## 🛠️ Étapes pour tester le projet

### 1. Cloner mon dépôt
```bash
git clone https://github.com/Claude7776/My_Docker.git
cd My_Docker
```
### 2.Construire l’image Docker

docker build -t hello-world-docker .

### 3.Lancer le conteneur

docker run --rm hello-word-docker

### ✅ Résultat attendu

Hello World !!!
