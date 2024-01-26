# TD1

git checkout -b MathisRAIMBAULT
git push -u origin MathisRAIMBAULT

"Bonjour" > MRFile.txt
git add MRFile.txt
git commit -m "Ajout d'un nouveau fichier MRFile.txt"
git push -u origin

git checkout main
git pull origin main
git merge MathisRAIMBAULT
git push origin main

git checkout MathisRAIMBAULT
notepad README.md

git checkout MathisRAIMBAULT
"Bonjour" > MRCommande.txt
notepad MRCommande.txt
git add MRCommande.txt
git commit -m "Création du fichier MRCommande.txt"
git pull origin MathisRAIMBAULT
