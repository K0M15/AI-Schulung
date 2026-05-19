Handle als Senior Game Developer, der sich auf Retro-First-Person-Shooter im Stil von DOOM (1993) spezialisiert hat.

Deine Aufgabe: Erstelle ein komplettes, spielbares Mini-Game in einer einzigen HTML-Datei (inklusive CSS und JavaScript).

Das Spiel-Szenario:
Wir befinden uns in einer düsteren, pixeligen 3D-Labyrinth-Umgebung. Der Spieler steuert die Figur in der Ego-Perspektive.

WICHTIG – Charaktere & Gegenstände:
In diesem Spiel jagen wir keine Dämonen. Passe die Gegner und Items wie folgt an:

Die "Bösen" (Gegner): Statt Monstern muss der Spieler auf Mäuse, Colibakterien, Auditoren schießen.

Die "Guten" (Sammelobjekte): Der Spieler muss Milchkannen, Joghurtbecher und Butter sammeln, um Punkte zu erhalten.

Spielmechanik:

Steuerung: Bewegung mit WASD, Drehen mit der Maus (oder Pfeiltasten), Schießen mit der Leertaste oder Linksklick.

HUD (Anzeige): Zeige die Gesundheit (Health), die Munition und den Punktestand (Score) am unteren Bildschirmrand an.

Gameplay: Die [BÖSEN CHARAKTERE] spawnen zufällig im Labyrinth. Wenn sie den Spieler berühren, verliert er Gesundheit. Wenn der [BÖSE CHARAKTER] getroffen wird, verschwindet er und hinterlässt vielleicht einen [GUTEN GEGENSTAND].

Visueller Stil:

Nutze Pseud-3D (Raycasting) oder ein sehr einfaches 3D-Framework (wie Three.js per CDN eingebunden), falls notwendig, aber priorisiere den Pixel-Art-Look von 1993.

Generiere sprites für die Charaktere und Items, aber sorge dafür, dass man sie unterscheiden kann.

Ziel:
Das Spiel soll in 5-10 Minuten implementierbar sein und nach dem Speichern der Datei sofort im Browser laufen. Der Code muss sauber und kommentiert sein.
