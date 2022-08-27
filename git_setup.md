## Anleitung zum Erstellen eines GitHub Accounts inklusive VisualstudioCode integration
In Visual Studio Code installiere Pakete:
- Git Graph
- Git History
- Git Project Manger
- GitHub Pull Request an Issues

Github Account erstellen

 git config --global user.email "email_address"

SSH - Key erstellen : 

windowskey + r -> cmd # Optional geht auch die Powershell

sh-keygen ausfuehren ( Passwort festlegen )

 cd .ssh/

 more id_rsa.pub

 Die Ausgabe muss dann im Github unter Username - > Setting -> SSH & GPG Keys eingetragen werden

 Ab hier kann wieder alles im VSC gemacht werden. Das Terminal wird ueber  strg + shift + ö geoeffnet

 git commit -m "testing" # Das "testing" kann individuel umbenannt werden.

 git branch -M main

 git remote add origin git@github.com/yourusername/yourproject.git

 git push -u origin main

Bei veraenderungen:

git add . # . bedeutet alles , es kann auch nur die eine Daten ausgewaehlt werden.

git commit # aenderungen bestaetigen

git push # laed alle andereungen hoch.
 

