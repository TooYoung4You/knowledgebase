## Wie kann ich meinen Server verwalten?

Um mit der Verwaltung deines Servers zu beginnen musst du dich zuerst in unserem **Webinterface** anmelden. Dort kannst du dann deinen Server auswählen und mit der Verwaltung beginnen.

Das Webinterface findest Du, wie im nachfolgenden Screenshot gezeigt unter Meine Server, Gameserver. 
Dort kannst du dann deinen Server auswählen und mit dich mit dem Button "Ins Webinterface einloggen" anmelden.

![Webinterface](../../.gitbook/assets/gamecp-login.png)

{% hint style="info" %}
Bitte beachte die Anweisungen zur Anmeldung, welche du unter dem Button "Ins Webinterface einloggen" findest.
{% endhint %}


<details>
<summary>Welten</summary>
  ### Wie kann ich die Welt meines ARK-Servers anpassen?

In ARK : Survival Evolved gibt es diverse Karten die man Spielen kann. Neben den 12 Karten die vom Spiel selber mitgeliefert werden, gibt es auch noch verschiedne Karten die man durch Mods hinzufügen kann.
Man sollte jedoch zwingend beachten, dass es Karten gibt, die man von den erstellern **zuätzlich, kostenpflichtig** erwerben muss und Karten, die man sich kostenlos herunterladen kann. 
Unteranderen gibt es folgende Karten:

TheIsland(Kostenlos, Vorinstalliert, Story)
TheCenter(Kostenlos)
Ragnarok(Kostenlos)
ScorchedEarth_P(Kostenpflichtig, Story)
Aberration_P(Kostenpflichtig, Story)
Extinction(Kostenpflichtig, Story)
Valguero_P(Kostenpflichtig, Story)
Genesis(Kostenpflichtig, Story)
CrystalIsles[Kostenlos]
Gen2(Kostenpflichtig, Story)
Fjordur(Kostenlos)
Um deinen Server auf eine bestimmte Karten einzustellen, musst du als erstes wie oben beschrieben in Webinterface. Nachdem du angemeldet bist, musst du den Server auswählen, den du bearbeiten willst. Jetzt musst du dein Karte auswählen. Dies geschieht unter dem Reiter **"Startup"**(Siehe Grafik)
![StartseiteWebinterface](https://github.com/user-attachments/assets/6ecefd75-734a-4215-9cc0-0b1b2da2c1e4)
(Hier kann man übrigens auch wie oben erklärt, das Admin Passwort, den Server-Namen, die Maximale Spieleranzahl und die zusätzlichen Startargumente verändern.)
Dort suchst du dann nach dem Eingabe Feld **"Server Map"** und schreibst den Namen von einer der oben gennanten Maps in das Feld. Sofort wird der eintrag gespeichert und beim Hochfahren wird nun diese Map gespielt
Neben diesen offiziellen Welten gibt es auch eine Vielzahl an Mod-Welten, die du auf deinem Server nutzen kannst.
Diese findest unteranderem im [Steam Workshop](https://steamcommunity.com/app/346110/workshop/).
Zum nutzen dieser musst du die Mod-IDs in der [serverconfig.ini](https://ark.gamepedia.com/Server_Configuration) eintragen.
</details>
<details>
<summary>Server Konfigurationen</summary>
Umd deinen Server konfigurieren, also z.B. die Multiplikatoren beim Rohstoff-Abbau zu verändern, mussst die die UserGameSettings.ini oder die Game.ini Datei verändern. Hierbei bezieht sich die Game.ini auf fortgeschrittene Einstellungn und die UserGameSettings.ini eher auf die Grundeinstellungen. <br>
  Um diese zu finden, drückst du oben auf den Reiter Files, und dann folgst du diesem Pfad: /ShooterGame/Saved/Config/LinuxServer/
Um alle Werte zu finden die du verändern kannst nutze den Eintrag im [ARK-Wiki](https://ark.gamepedia.com/Server_Configuration). Hier findest du viele Einstellungen, jedoch widerrum auch nicht alle. Daher, solltest du nach besonders spezifischen Einstellungen online suchen. Hier gibt es oft Hilfe von Ark-Nutzern auf [Reddit](https://Reddit.com) oder [SurviveTheArk](https://survivetheark.com/)<br>
Übrigens kann man hier auch viele Einträge für die zusätzlichen Startargumente finden.<br>

</details>
<details>
<summary>RAM</summary>
<strong>Wie viel RAM brauche ich?</strong>
Wie viel Ram du brauchst, hängt von verschiedenen Faktoren ab, zuerst einmal musst du wissen, wie viele Spieler spielen werden, welche Map gespielt wird, welche Mods installiert sind und wie lange ihr spielen wollt. <br>
Daher heir einmal eine Liste w wie viel RAM jede Map ungefähr verbraucht. Diese Werte sind **ohne** Spieler und ohne jegliche Veränderungen an der Map(gezähmte Dinos, gebaute Strukturen, usw.) gemessen: <br>
TheIsland: 3.5-4.5GB <br>
TheCenter: 3-4GB <br>
Ragnarok: 4-5GB <br>
SorchedEarth_P: 3-4GB <br>
Abberation_P: 3-4GB <br>
Extinction: 3-4GB <br> 
Valguero_P: 3-4GB <br>
Genesis (Part 1): 5-6GB <br>
CrystalIsles: 5.5-6.5GB <br>
Genesis (Part 2): 10-12.5GB <br>
Lost Island: 5.5-7GB <br> 
Fjordur: 4-5GB <br>
</details>
<detail>
<Summary>PORT & IP</Summary>
<strong>Wo find eich meine IP und welchen Port soll ich wählen?</strong>
Deine IP findest du eigentlich überall. Als alltererste findest du sie auf unserer Website unter [Meine Server](https://mc-host24.de/myservers), wenn du dich im Webinterface befindest kannst du sie unter Console, StartUp, und Network finden.
Der Port wiederrum ist etwas komplizierter. Der Port steht mit einem : getrennt hinter der IP überall wo du auch die IP findest. Jedoch haben Nutzer auch schon erfahrungen damit gemacht, das dieser Port trotzdem nicht funkioniert hat. Wenn dem so ist, gehe Im Webinterface auf **"Network"** und wähle dort einen anderen Port aus, indem du neben dem Gewünschten Port auf **"Make Primary"** clickst. <br>
![PORT](https://github.com/user-attachments/assets/0508ff26-6449-40c0-a9dd-01c5961015c1)
Falls der Port immernoch nicht funkioniert, muss du einfach einen Port auswählen und trotzdem die anderen Ports ausprobieren, dies kann auf einen Anzeigefehler der Website zurüclzuführen sein. <br>
Im Bild oben zum Beispiel war der Port 20186 ausgewählt, aber dem Server beitreten konnte man nur mit dem Port 20187. 
</detail>
