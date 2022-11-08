# Game Design I

## Definition
### Was ist Design?
  ![Capture1](https://user-images.githubusercontent.com/62158116/200593278-eab546c1-4562-4c63-a77d-52c84cd5e40b.PNG)
### Was tut ein/e Game Designer/in?
  ![image](https://user-images.githubusercontent.com/62158116/200593513-743742b2-68f7-4bec-b141-fc78f6ff9c60.png)

## Elemente eines Spiels
  ![image](https://user-images.githubusercontent.com/62158116/200593712-ecaa63e0-cb92-46e1-acd2-c6d1c7bcfc07.png)
### Regeln
  - Definieren das Spiel und seine Restriktionen
  - Erschaffen Sinn und Zweck für die Spielwelt
  - Jedes Element ist durch Regeln definiert
  - Regeln müssen forciert werden
#### Arten von Regeln
  - Operational (Wie wird gespielt?)
  - Foundational (Wie funktioniert es?)
  - Implicit (Was wurde nicht bedacht / ist nicht klar definiert?)
  - House Rules (Was machen Spieler draus?)
### Die Spieler*innen
`Spielende sind freiwillige, aktive Teilnehmer an der
Unterhaltungs-Aktivität.`

- Rahmenbedigungen:
  ![image](https://user-images.githubusercontent.com/62158116/200596380-623f9324-a6e8-419e-a968-773ec3d3b220.png)
- Zielgruppen:
  - Fähigkeiten der Spieler beachten
  - Was macht den Spielern Spaß?
  - <figure>
    <img src="https://user-images.githubusercontent.com/62158116/200597137-b36c90ec-770c-4a6b-a913-348100b7b3f9.png"
         alt="Player Types">
    <figcaption>Player Types nach Richard Bartle</figcaption>
</figure>

### Ziele
`Der Zweck der Bemühung des Spielers, das erwünschte Resultat.`
- Sind klar und (gefühlt) erreichbar
- Sind verschachtelt
- Machen Fortschritt deutlich

#### Arten und Eigenschaften
![image](https://user-images.githubusercontent.com/62158116/200598924-f1185dde-c990-43e5-8d38-ca56abb7273c.png)

### Belohnungen
- Motivieren Spieler (Extrinsisch vs. Intrinsisch)
- Stichwort: Skinner Box
  ![image](https://user-images.githubusercontent.com/62158116/200600353-35b2bade-a62e-4300-a526-01d8c1f53d8a.png)
- Abhängig von Zielgruppe
- Sollten **frequent** und **erwartbar** sein (**Reward Fatigue** beachten!)
#### Arten von Belohnungen:
- Fortschritt (XP, Belohnungen, Währung)
- Sozial (Bragging Rights, High Score Listen)
- Inhalte (Neue Game Modes, Neue Levels, etc.)
- Customization (Neue Items, Skins, etc.)
- Feedback (Effekte, On Screen Text, Sound Effekte, etc.)`

### Herausforderungen
- Schaffen Schwierigkeit(sgrad)
- **Sichtbar** und mit **klarer Lösung**
- Müssen **konsitenz** sein

#### Arten von Herausforderungen
- Spatial
- Skill
- Wissen
- Andere Spieler
- Glück

#### Pacing und Flow
- Pacing = Bewegung durch Spiel
  - **Spannung** und **Entspannung**
- Flow = Gefühl der vollen Immersion

![image](https://user-images.githubusercontent.com/62158116/200602882-d3b7d15b-34b4-4fe0-81b9-c890d47c5e44.png)

### Entscheidungen
`Ein Spiel ist eine Reihe interessanter Entscheidungen`
- Machen die **Interaktivität** aus
- Balance zwischen **Impact**, **Komplexität** und **Longevity**

#### Level der Konsequenz
![image](https://user-images.githubusercontent.com/62158116/200603460-1a5a042b-acf2-4a19-96f7-b3697aa28536.png)
#### Do and Don't
![image](https://user-images.githubusercontent.com/62158116/200603599-8989ec94-c94c-4efc-8878-62643c905e8e.png)

### Interaktion
![image](https://user-images.githubusercontent.com/62158116/200604015-5d17b55e-f08b-439d-80ac-a44d2bd2d2d9.png)

## Game Design in der Produktion

### Design Dokumentation
- dient Kommunikation und "Gedächtnis"
- hält Entscheidungen fest
- ist ein lebendiges Dokument (niemals fertig)
- kommt (normalerweise) vor der Produktion
- arbeiter von innen nach aussen
- beinhaltet Informationen zu allen Bereichen

#### Wichtig ist:
- Zielgruppe beachten (wer liest es?)
- Informationshierachie schaffen
- Lesen spaßig machen (nicht nur reiner Text)
- Klare Definitionen setzen
- Regeln und Balancing nicht vermischen
- "Der Prozess ist wichtiger als die Menge"

### Anatomie einer Spielproduktion
![image](https://user-images.githubusercontent.com/62158116/200606707-b6d145ee-bb77-414f-8308-c39e1835f430.png)
- **Alpha** = "feauture-complete"
- **Beta** = "content-complete"
- **Gold** = "Ready-for-release"
#### Pre-Production
![image](https://user-images.githubusercontent.com/62158116/200610199-10553464-b4c7-481f-b42a-67e96496b940.png)
- Vertical Slice = Teil des Spiels in seiner finalen Form
- Prototyp = Test um die Funktionalität eines Features/Systems zu überprüfen
##### Aufbau eines Vision Docs:
![image](https://user-images.githubusercontent.com/62158116/200606545-b0f4a591-4386-4817-82ba-958eec07c23e.png)
#### Production
![image](https://user-images.githubusercontent.com/62158116/200610282-3d974be8-8bab-42b3-9c77-57bb89d5684e.png)
#### Live Support
![image](https://user-images.githubusercontent.com/62158116/200610449-2a5d219c-d296-43fd-9b35-d4e721817f8e.png)

## Game Loops
- Das was Spieler immer und immer wieder tun
- Wichtiges Tool um Produktion zu fokussieren
- Core Gameplay Loops werden in der Regel hunderte male wiederholt →
Polishing wichtig
- Micro -> Macro (kleine Loops können Teil von größeren sein)
### Aufbau
![Loops](https://user-images.githubusercontent.com/62158116/200631393-61710305-9322-4f06-b6d0-fe0a0a04f7f7.png)

- Offgame Aktion (z.B. Ziel ausmachen)
  - passiert ausserhalb des Spiel
  - keine (klar definierten) Regeln
  - der Spieler muss in der Lage sein, die Aktion durchzuführen
- Ingame Aktion (z.B. Schießen)
  - passiert innerhalb des Spiels
  - sollte verständlich uns spaßig sein
- Reactions / Feedback
  - Fortschritt und Belohnung passieren meist hier
  - es muss klar sein, was passiert
  - sorgt oft zu Veränderungen im System (z.B. neues Level)

### Core Gameplay Loop
- Muss geschlossen sein
- Passiert wiederholt (Sekunden- oder Minuten takt)
- Darf nicht zu generisch sein
- Stellt oft auch die "Game Economy" dar

<img width="594" alt="image" src="https://user-images.githubusercontent.com/62158116/200632771-13912734-7d2d-4c49-88b6-6b9af1f57e3c.png">
