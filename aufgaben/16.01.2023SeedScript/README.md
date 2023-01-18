Erstelle ein Seed-Skript für deine Galerie-App. Berücksichtige dabei folgende Bedingungen:
- Das Seed-Skript soll Fotos mit Daten aus dem Modul faker erzeugen
- Das Skript soll über "npm run seed" aufrufbar sein
- Standardmäßig sollen 20 Einträge erzeugt werden
- Über einen Parameter (process.argv) soll eine andere Anzahl erzeugt werden können
- Die Collection soll vor dem Befüllen geleert werden
- Über einen weiteren Parameter soll das Leeren verhindert werden können


Erweitere dein Photo-Model um SubDocuments, in denen das eingesetzte Equipment und die Einstellungen gespeichert werden.
- Das Equipment soll ein Array sein.
- Jedes Teil soll eine Bezeichnung und optional einen Herstellernamen erhalten.
- Die Einstellungen sollen ein Objekt sein.
- Folgende Einstellungen sollen angegeben werden: Brennweite (focal length), Belichtungszeit (exposure), Blende (aperture), Empfindlichkeit (iso), Weißabgleich (white balance).
Versuche die Einstellungen so gut wie möglich zu validieren.


Füge deiner Galerie-App ein Album-Model hinzu.
Richte eine Referenz zwischen Photo und Album ein. Überlege dir, wo du die Referenz speicherst.
Erweitere auch dein Seed-Script, damit du Alben automatisch generieren kannst.