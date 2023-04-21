$ git clone https://github.com/szabopeter92/git-vizsga.git
$ cd git-vizsga
$ git init
$ git add .
$ touch .gitignore
$ touch README.md
$ echo '*.txt' >> .gitignore
$ echo '*.doc' >> .gitignore
$ echo '*.docx' >> .gitignore
$ echo '*.pdf' >> .gitignore
$ notepad README.md
$ git branch console
$ git checkout console
$ echo 'addEventListener("load", function(){' >> app.js 
$ echo 'console.log("Az oldal sikeresen betöltődött!");' >> app.js 
$ echo '})' >> app.js 
$ git commit -m "console szöveg hozzáadása betöltődéskor"
$ sed 's/rgb(71, 71, 71)/rgb(00, 00, 55)/' style.css -i
$ git commit -m "háttérszín megváltoztatása"
$ git remote add origin https://github.com/kissdavid21/DavidKiss_Webler_Vizsga.git
$ git remote remove origin
$ git remote -v
$ git remote add origin https://github.com/kissdavid21/DavidKiss_Webler_Vizsga.git
$ git push -u origin main
$ git push -u origin console