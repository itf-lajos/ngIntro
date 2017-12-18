# Git kezelés
## Git beállítások
- git remote add origin https://github.com/itf-lajos.git/ngIntro
- git config --global user.email "you@example.com"
- git config --global user.name "Lajos"
## Git-re küldés
- git commit -a -m 'message'
- git push
## Amit a Git-re sosem kell küldeni
- .gitignore fájlban felsorolni
# Bootstrap integráció
- https://github.com/angular/angular-cli/wiki/stories-include-bootstrap
- npm install bootstrap@next --save
- "../node_modules/bootstrap/dist/css/bootstrap.min.css", beillesztése az angular-cli.json styles részébe
- <button class="btn btn-primary">Test Button</button> beillesztése az app.component.html-be
- ng serve újraindítás (angular-cli.json változása miatt)
 

