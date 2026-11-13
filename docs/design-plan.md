# Fled the Cat – Game Design Document

## 1. Projektübersicht

**Projektname:** Fled the Cat  
**Genre:** Survival Puzzle auf Zeit  
**Zielgruppe:** Casual Gamer, Tierliebhaber, Allergiker und Fans von Cute-/Meme-Kultur  
**USK-Ziel:** USK 6 (angestrebt)

### 1.1 Spielkonzept

Der Spieler übernimmt die Rolle eines Katzenallergikers, der versucht, in einem Haushalt voller Katzen zu überleben, gesuchte Dinge zu finden und us der Wohnung herauszukommen.

Die Katzen sind dabei die Gegner. Durch ihre Nähe und den Kontakt mit Katzenhaaren wird die Allergie des Spielers zunehmend ausgelöst. Die daraus entstehenden Symptome gefährden seine Gesundheit und setzen ihn unter Zeitdruck.

Das Spiel kombiniert humorvolle Situationen mit Survival- und Puzzle-Elementen. Der Spieler muss Gegenstände finden, Hindernisse überwinden und möglichst schnell den Ausgang erreichen.

## 2. Unique Selling Points (USP)

- **Allergie-Awareness mit Humor:** Eine überspitzte und humorvolle Darstellung des Alltags eines Katzenallergikers.
- **Meme-Potenzial:** Absurde Situationen, witzige Animationen und übertriebene Reaktionen auf Katzen.
- **Cute Art Style:** Niedliche Katzen und eine cartoonartige Spielwelt stehen im Kontrast zur lebensbedrohlichen Situation des Spielers.
- **Challenge und Wettbewerb:** Highscores und Bestenlisten motivieren dazu, bessere Fluchtzeiten und Ergebnisse zu erreichen.

## 3. Spielerfahrung und Perspektive

Der Spieler erlebt die Spielwelt aus der Perspektive eines Katzenallergikers.

Das Szenario spielt in einer WG, Wohnung oder einem Haus, in dem sich mehrere Katzen aufhalten. Die Umgebung ist eine überspitzte, cartoonartige Darstellung eines realistischen Haushalts.

Die Spielerfahrung soll:
- Humorvoll und unterhaltsam sein.
- Durch Zeitdruck und begrenzte Gesundheit herausfordernd bleiben.
- Durch versteckte Gegenstände und alternative Routen zum Erkunden motivieren.
- Durch Scoreboards einen Wiederspielwert bieten.

**Perspektive:** Noch nicht final festgelegt. Third-Person ist eine mögliche Option.

## 4. Visueller und akustischer Stil

- Niedlicher, cartoonartiger Grafikstil.
- Flüssige Animationen und Bewegungen.
- Keine übermäßig detaillierte oder realistische Grafik.
- Kontrast zwischen niedlicher Spielwelt und chaotischer Survival-Situation.
- Verwendung der Kelly Assets.
- Humorvolle Soundeffekte und passende Musik.

## 5. Spielwelt und Fiktion

**Setting:** WG, Wohnung oder Haus.

Die Spielwelt enthält:
- Katzen als zentrale Gegner.
- Typische Haushaltsgegenstände und Möbel.
- Versteckte und sammelbare Gegenstände.
- Verschiedene Räume und mögliche Fluchtrouten.
- Easter Eggs und versteckte Katzenreferenzen.

Die Umgebung soll sowohl als Spielfläche als auch als Puzzle dienen.

## 6. Core Gameplay Loop

Der grundlegende Spielablauf:

1. Der Spieler startet in einem Haushalt voller Katzen.
2. Er erkundet die Umgebung und sucht nach benötigten Gegenständen.
3. Katzen und deren Nähe lösen allergische Reaktionen aus.
4. Die Gesundheit des Spielers nimmt durch die Allergie zunehmend ab.
5. Der Spieler muss Gegenstände einsetzen, Hindernisse überwinden und eine Fluchtroute finden.
6. Ziel ist es, den Ausgang zu erreichen, bevor die Gesundheit vollständig aufgebraucht ist.
7. Bei Tod folgt eine humorvolle Krankenhaus-/EpiPen-Animation.
8. Anschließend startet ein neuer Run.

**Wichtige Designentscheidung:** Es gibt zunächst keine Checkpoints. Jeder Run beginnt von vorne.

## 7. Zielsetzung und Progression

### 7.1 Kurzfristige Ziele

- Am Leben bleiben und allergische Reaktionen vermeiden.
- Katzen möglichst ausweichen.
- Collectibles und benötigte Gegenstände finden.
- Eine möglichst effiziente Route wählen.
- Subziele erfüllen, um den Fluchtweg freizuschalten.

Beispiel: Der Spieler muss einen verlorenen Schlüssel finden, um eine Tür öffnen zu können. Der Spieler platziert Katzenfutter, um Katzen abzulenken und Zeit zu gewinnen.

### 7.2 Langfristiges Ziel

Das übergeordnete Ziel ist es, den Ausgang zu erreichen und aus dem Haushalt zu entkommen.

### 7.3 Wiederspielwert

- Highscores und Bestenlisten.
- Verbesserung der persönlichen Bestzeit.
- Unterschiedliche Routen und mögliche Lösungswege.
- Optionale Collectibles und Easter Eggs.

## 8. Spielsysteme und Mechaniken

### 8.1 Bewegung

- Steuerung über WASD.
- Schnelle und flüssige Bewegung.
- Physikbasierte Interaktionen und humorvolle Bewegungsabläufe.

### 8.2 Interaktion

- Gegenstände werden durch Darüberlaufen automatisch aufgehoben.
- Gegenstände können über Tastendrücke eingesetzt werden.
- Weitere Interaktionen mit der Umgebung sind möglich.

### 8.3 Gesundheit und Allergie

Die Gesundheit des Spielers wird durch die Katzenallergie beeinflusst.

Mögliche Mechaniken:
- Nähe zu Katzen reduziert die Gesundheit.
- Katzenhaare und andere allergieauslösende Objekte können zusätzliche Gefahren darstellen.
- Die Stärke der allergischen Reaktion kann abhängig von Entfernung und Aufenthaltsdauer variieren.
- Bei vollständig aufgebrauchter Gesundheit stirbt der Spieler und der Run endet.

Die konkrete Umsetzung und Balance der Allergiemechanik ist noch festzulegen.

### 8.4 Gegenstände und Collectibles

Gegenstände erfüllen unterschiedliche Funktionen:
- Schlüssel und Quest-Items zum Freischalten von Wegen.
- Hilfsmittel zur Bewältigung von Gefahrensituationen.
- Optionale Collectibles für zusätzliche Punkte.

## 9. Technologie und Entwicklungsumgebung

**Game Engine:** Godot

**Entwicklungswerkzeuge:**
- Visual Studio Code
- Git / GitHub (sofern verwendet)

**Entwicklungsplattformen:**
- macOS
- Ubuntu
- Arch Linux

## 10. Ideen und mögliche Erweiterungen

Folgende Features sind denkbare Erweiterungen, gehören aber nicht zwingend zum initialen Spielumfang:

- Third-Person-Perspektive.
- Multiplayer-Modus.
- Weitere Level und Haushalte.
- Unterschiedliche Katzen mit eigenen Verhaltensweisen.
- Zusätzliche Allergiesymptome und Items.
- Easter Eggs und versteckte Katzenreferenzen.
- Erweiterte Bestenlisten und Statistiken.

## 11. Ungelöste Fragen

Offene Designentscheidungen und technische Fragen werden hier gesammelt. Sobald eine Frage geklärt ist, wird sie in den Abschnitt „Gelöste Fragen“ verschoben und dort mit einer kurzen Erläuterung dokumentiert.

- Wie genau funktioniert die Allergiemechanik (Reichweite, Schaden, Intensität)?
- Welche unterschiedlichen Verhaltensweisen haben die Katzen?
- Wie viele Katzen und Räume umfasst ein Level?
- Welche Gegenstände sind für die Flucht notwendig?
- Wie wird das Scoreboard berechnet?
- Welche Perspektive wird final verwendet?
- Wie stark soll die Physikkomponente ausgeprägt sein?

## 12. Gelöste Fragen

Bisher getroffene Designentscheidungen:

- **Gegnerkonzept:** Katzen sind die Gegner. Ihre Nähe löst allergische Reaktionen aus und reduziert die Gesundheit des Spielers.
- **Checkpoints:** Im initialen Konzept sind keine Checkpoints vorgesehen. Jeder Run beginnt nach einem Game Over von vorne.

## 13. Aktueller Entwicklungsstatus

Derzeit befindet sich das Projekt in der Konzeptions- und Planungsphase.

Die grundlegende Spielidee, das Genre und die zentralen Gameplay-Elemente sind definiert. Die konkrete Umsetzung der Spielmechaniken, insbesondere der Allergie- und Gegnermechanik, muss noch ausgearbeitet und prototypisch getestet werden.

Der nächste Schritt ist die Entwicklung eines spielbaren Prototyps mit grundlegender Bewegung, Katzen als Gegnern und einer ersten Version des Gesundheitssystems.

## 14. Known Bugs

Aktuell sind keine bekannten Bugs dokumentiert.