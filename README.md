# ❤️‍🔥 PARSHIP

### Codes
- [Reviews Crawling with BeautifulSoup](https://github.com/risa1796/Parship/blob/main/BeautifulSoup_Trustpilot_Parship.ipynb)
![Unknown](https://user-images.githubusercontent.com/70292353/218563479-9b78ef68-5e2c-4233-8a4e-38d60e6a2d98.png)
       - Web Crawling, Wordcloud, data visualization of customer reviews on monthly basis using stacked bar 
       
       
#### - Klassifizierung von Kunden in vier Klassen (churn, potentielle churn, potentielle aktiv, aktiv)
     - random Daten erstellen


----

### Ideen zu KI-Projekten

- **Klassifikation von Fake-Profilen [Binäres Klassifikation]**
    - Parameter: Durchschnittlicher Zeitverbrauch für Persönlichkeitstest, Anzahl von Profilfotos, Durchschnittliche Anzahl von Nachrichten, Inhalt von Nachrichten (z.B Hyper-Link, E-Mail Adresse), Profilangaben wie Beruf, Alter, Verifizierung, usw.
    - Merkmal vom Klassifikationsproblem: Ungleichmäßige Daten
- **Zeitprognose von drei verschiedenen Premium-Abos (6, 12, 24 Monate Laufzeit)**
- **Analyse: Nutzer mit welchen Persönlichkeiten (Ergebnis vom Persönlichkeitstest) tendiert mehr zum Abschließen eines Premium-Abos?**
- **Welches Profilbild-Kombi wirkt am attraktivsten? (Computer Vision + EDA)**
    - 1/4 Head shot (’Close-up’)
    - Body shot
    - Gesichtsausdrücke (‘Smile or Not’ Verhältnis)
- **Sentimentanalyse von Kundenbewertungen**
- **Analyse: Welche Faktoren führt zum Premium-Abo?**
    - Durchschnittliche Anzahl von Wörtern im ersten Nachricht
    - Nutzung von Emojis
    - Schnelles Reaktion von potentiellen Partnern
    - Anzahl von bekommenen Likes
    - Durchschnittliche Zeitdauer beim Chatten
    - ….
- **Prognose**: **Im welchen Zeitpunkt wird Premium-Abo am meistens abgeschlossen? oder welche Faktoren führen oft zum Premium-Abo ??? **
    - Wenn es laut EDA z.B 7. und 8. Tag nach dem ersten Login ist:
    
      1. Man sammelt Nutzungsdaten von den ersten 6 Tagen von Premium-Mitgliedern (durch. Online-Dauer, Anzahl von Likes, schnelles Reaktion, usw.)
    
      2. Man analysiert ob es ein bestimmtes Muster existiert. 
    
      3. Mit den Daten entwickelt man ein Prognose-Modell (wird zum Premium-Mitglied or nicht)
    
   - Passende Marketing-Kampagne einsetzen für Kunden, die eher unwahrscheinlich sind, ein Abo abzuschließen. 
- **Clusteringanalyse nach Ergebnissen aus Persönlichkeitstest**
- **Customer Care Nachfrage-Prognose & Abo-Kündigung-Prognose**
   - Daten zum üben: [Customer Subscription Data](https://www.kaggle.com/datasets/gsagar12/dspp1?select=customer_product.csv)
   - Kategorien beim Kundenservice: 
     Mein Profil, Fragenbogen&Ergebnis, Matches&Kontaktaufnahme, Login&Technik, Sicherheit&Seriösität, Angebot&Bestellung, Zahlung&Vertag
- **A/B Testing mit Unschärfe (40%, 60%, 80%, usw...)**
-------

#### ✏️ Informationen über das Dating-App 

- Circa 30 Minuten Persönlichkeitstest 
- Like-Funktion für fast jeden Beitrag 
- Smiley senden Funktion
- Eisbrecher (Eins von zwei Bildern auswählen für 5 Mal) Das Ergebnis bekommt man erst, wenn beide das Eis gebrochen haben. 
- Die erste persönliche Nachricht von einem Premium-Mitglied kannst du als Basis-Mitglied einmalig lesen und beantworten, sofern das Premium-Mitglied den Kontakt begonnen hat.
- Auf Basis vom Persönlichkietstest bekommt man Liste (nach unten scrollen) von potentiellen Partnern 
- Matchingpunkte Funktion, Diskussion in Forum : https://community.parship.de/forum/thema/wie-viele-matching-punkte-sollten-es-sein.7654/
- Als Basis-Nutzer kann man nur verschwommenen Bilder von potentiellen Partnern ansehen. (Meiner Ansicht nach wäre es schön, wenn man nur das erste Bild ohne Verschwommeneffekt sehen könnte, aber dann erst nach dem zweiten Bild verschwommen lassen. Man wird dann MEHR NEUGIERIG, was letztendlich zum Premium-Abo führen könnte!)

  Dazu ein Beitrag von einem Nutzern im Forum: 
               
      Der Parship-Test erfasst ja "nur" psychologische Aspekte. Zum Verlieben gehört ja auch der Körper (Aussehen, Geruch, Haptik usw) und viele weitere Eigenschaften (zB erotische Präferenzen), die in den Matching-Points gar nicht abgebildet werden.
  
- Beim Testen des Apps habe ich selbst gemerkt, dass manche Nutzer mir Nachrichten mit E-Mail Adresse oder Instagram ID geschickt haben, um trotz des Basis-Abos weiter ins Gespräch zu kommen. 
- Kundenbewertungen über das App: Die Anzahl von 1-Stern Bewertungen ist fast genauso hoch wie die 5-Stern Bewertungen, was ist aber beim ersten Blick sehr überraschend finde. Es liegt hauptsächlich auf die hohen Kosten und unflexiblen Laufdauer des Premium-Abos.
- Wer ist die Zielgruppe? -> Premium-Abo EDA -> Auf Basis vom EDA Marketing-Strategien entwickeln, um die Zielgruppe gezielt anzusprechen.
-  Erstnachrichten haben bei uns eine Mindestlänge und kopierte Inhalte können nicht verschickt werden.
### Matching-Ergebnis Hauptkategorien als Tabelle

| Grundzüge der Persönlichkeit | Strebungen und Tendenzen| Alltagsgestaltung | Kommunikationsstil | 
| ------ | -- | -- | -- | 
| Aus welchem Winkel betrachtest du die Welt? | Wie betrachtest du die Welt?| So individuell ist dein Verhalten| Die Botschaften deiner Erziehung
| Dein Einklang von Passion und Gewissen | Auf welche Weise verarbeitest du Erlebnisse? |Schätzt du Routine oder liebst du improvisation?| Wie deine kindlichen Verhaltenswweisen dich bis heute prägen | 
| Eure Paar-Dynamik | Wie gehst du auf Menschen zu?| Deine eigenne vier Wände | So vereinst du deine Kommunikationsstile | 
| Dein richtiges Maß an Nähe | Kompromisse und klare Grenzen in deiner Partnerschaft|Dein Unternehmensdrang und das Nichtstun | 
| Wie empathisch bist du? | Wie praktisch gehst du's an? | | 
