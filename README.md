💸 GeldStroom - Personal Finance & Wealth Manager
Welkom bij GeldStroom! Dit is een op maat gemaakte, cloud-gesynchroniseerde web-app voor het beheren van gezamenlijke financiën. De app combineert dagelijks budgetteren met lange-termijn vermogensopbouw (FIRE) en vastgoed-tracking.

🚀 Kernfuncties
☁️ Live Cloud Sync: Gebouwd met Firebase. Invoer op het ene toestel is direct zichtbaar op het andere toestel. Volledig offline-ondersteund.

🎯 Zero-Based Dagbudget ("Safe-to-Spend"): Berekent exact wat er vandaag veilig uitgegeven mag worden, op basis van de resterende dagen in de maand en de reeds betaalde vaste lasten.

🛡️ Sinking Fund Systeem: Reserveer met één druk op de knop maandelijks een vast bedrag voor grote, jaarlijkse kosten.

💎 Vermogensbeheer (Net Worth & FIRE): Volg de actuele waarde van beleggingen, pensioensparen, groepsverzekeringen en vastgoed (inclusief hypotheek-afbouw).

📈 Pay-Yourself-First Analyse: De app berekent de maandelijkse 'Savings Rate' puur op basis van geld dat proactief is veiliggesteld (naar sparen of beleggen), niet op basis van toevallig overschot.

🧠 Hoe werkt de app in de praktijk?
De app is ontworpen rondom een vaste, maandelijkse flow:

1. De Maand Starten
De financiële maandcyclus is losgekoppeld van de kalendermaand.

De Trigger: De cyclus start en reset zodra er een inkomst wordt toegevoegd met de categorie "Loon M." (Loon Matthias).

Alle andere inkomsten (zoals Loon K. of Kindergeld) worden gewoon bij het budget opgeteld zonder de maand te resetten.

2. Het Dagelijks Gebruik (Safe-to-Spend)
Kijk niet naar je Bank Saldo om te bepalen of je iets kunt kopen, maar naar het Safe-to-Spend bedrag op het dashboard.

De Formule: (Alle Inkomsten deze cyclus - Totale Vaste Lasten - Sinking Fund Reservering - Reeds uitgegeven Variabel) / Resterende dagen van de kalendermaand.

Geef je vandaag meer uit dan je budget? Geen probleem. De app trekt het bedrag de volgende dag automatisch strak over de resterende dagen om te zorgen dat je de maand netjes op nul (of in de plus) eindigt.

3. De Maandelijkse Routine (End-of-Month)
Aan het einde van de maand (of het begin van de nieuwe) doe je een korte check-in:

Afletteren: Ga naar de tab Lijst, check je actuele banksaldo in je bank-app en vul dit in bij "Afletteren". De app maakt indien nodig een correctieboeking zodat alles weer 100% klopt.

Vermogen Updaten: Ga naar de tab Vermogen, vul de nieuwste standen in van beleggingen en de openstaande hypotheekschulden, en klik op "Opslaan & Snapshot Maken".

Analyseer: Bekijk je Savings Rate en de trendgrafiek in de tab Analyse om te zien of je op koers ligt voor je doelen.

🛠️ Technische Details & Installatie
Deze app is een Serverless Single Page Application (SPA).

Frontend: HTML5, Vanilla JavaScript, en Tailwind CSS (via CDN).

Backend / Database: Firebase Firestore (Realtime Database).

Authenticatie: Firebase Auth (Email/Password).

Hosting: GitHub Pages.

Lokale Setup
Wil je de app zelf klonen en gebruiken?

Maak een eigen Firebase-project aan.

Activeer Firestore en Authentication (Email/Password).

Kopieer je eigen Firebase firebaseConfig object in de <script> tag van het index.html bestand.

Host het bestand via GitHub Pages of open het lokaal in je browser.

🔒 Veiligheid & Privacy (Belangrijk!)
Omdat de broncode (HTML/JS) openbaar op GitHub staat, is veiligheid van het grootste belang:

De code is een lege huls: Er staat geen enkele persoonlijke financiële data in de code op GitHub.

Alle transacties, saldi en vermogenscijfers zitten versleuteld in de Firebase Database.

De database is beveiligd via Firestore Security Rules. Alleen geauthenticeerde gebruikers (ingelogd met het specifieke wachtwoord) kunnen data lezen en schrijven.

Gebouwd om financiële rust te creëren en doelen te bereiken. Happy budgeting!
