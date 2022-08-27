<h1> Anleitung zum Erstellen eines GitHub Accounts inklusive VisualstudioCode integration</h1>
# Anleitung zum Erstellen eines GitHub Accounts inklusive VisualstudioCode integration<p>
## Anleitung zum Erstellen eines GitHub Accounts inklusive VisualstudioCode integration<p>
### Anleitung zum Erstellen eines GitHub Accounts inklusive VisualstudioCode integration<p>
#### Anleitung zum Erstellen eines GitHub Accounts inklusive VisualstudioCode integration<p>
##### Anleitung zum Erstellen eines GitHub Accounts inklusive VisualstudioCode integration<p>
<p>
1. Github Account erstellen
<p>
<p>
2. git config --global user.email "email_address"
<p>
<p>
SSH - Key erstellen : 
<p>
<br>
Strg + r -> cmd # Optional geht auch die Powershell
<p>
sh-keygen ausfuehren ( Passwort festlegen )
<p> cd .ssh/
<p> more id_rsa.pub
<br>
<p> Die Ausgabe muss dann im Github unter Username - > Setting -> SSH & GPG Keys eingetragen werden
<p> git commit -m "testing" #Das "testing" kann individuel umbenannt werden.
<p> git branch -M main
<p> git remote add origin git@github.com/yourusername/project.git
<p> git push -u origin main
 <p>
<p>
<p>Bei veraenderungen:
<p>git add . # . bedeutet alles , es kann auch nur die eine Daten ausgewaehlt werden.
<p>git commit
<p>git push
<p>testing