# proyecto-github
git clone https://github.com/adridmnguezz/proyecto-github
cd proyecto-github
git add index.html
git commit -m "Agregado titulo"
git add README.md
git commit -m "Actualizado el README.md"
git push origin main
git log -oneline
git add log_com.txt
git commit -m "Guardado hash"
git branch estilos
git checkout estilos
git add style.css
git commit -m "Añadido style.css"
git add index.html
git commit -m "Enlazado style.css en index.html"
git checkout main
git merge estilos
git add README.md 
git commit -m "Pasos 8-13"
git push origin main
git reset -soft HEAD~1
git add log_com.txt
git commit -m “explicación de reset en log_com.txt”
git checkout ef1dbe9
git checkout main
git add README.md
git commit -m “Pasos 15-18”
git push origin main
