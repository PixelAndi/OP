# OP – Optimeringspartiet

Webbplats för Optimeringspartiet (OP) och plattformsidén **KommunOS**: en förvaltnings-AI som sköter den dagliga kommunala byråkratin, medan folkvalda politiker är den mänskliga säkerhetsspärren.

## Innehåll

Hela sajten finns i en enda fil, `index.html` (HTML, CSS och JavaScript utan externa beroenden, typsnitt eller spårning).

- **Hero med KommunOS live**: mätare och ett flöde av inkommande ”tankebubblor” (går att pausa).
- **Idén**: strategispelet jämfört med dagens kommunpolitik.
- **Så fungerar KommunOS**: de fyra stegen, med en knapp som kör ett vardagsärende genom hela kedjan.
- **Testlabbet** med fyra interaktiva tester:
  1. **Faktalåset**: gissa om påståenden från talarstolen stämmer och se hur Faktalåset granskar dem.
  2. **Säkerhetsspärren**: du är politikern. Godkänn eller stoppa sju AI-förslag, där några bryter mot lag eller skadar människor.
  3. **Budgettycoon**: fördela kommunens budget med reglage och se trivsel, köer och väntetider direkt. Här finns balanskravet och ”Låt KommunOS föreslå”.
  4. **Ärendeloppet**: samma ärende på gamla vägen och med KommunOS, sida vid sida.
- **Partiprogrammet** i sex byggstenar, **frågor och svar** och en avslutande uppmaning.

Poäng, trivselmätaren och antalet klara tester visas i den fasta HUD-raden högst upp. Sidan har ljust och mörkt läge, fungerar på mobil och tar hänsyn till `prefers-reduced-motion`.

> Alla siffror i simuleringarna gäller den påhittade exempelkommunen **Tycköping** och är till för att illustrera idén. Lagrum är förenklat beskrivna.

## Visa sidan

Öppna `index.html` direkt i en webbläsare. Du behöver ingen server eller något byggsteg.

## Publicera med GitHub Pages

1. Gå till **Settings → Pages** i repot.
2. Välj **Deploy from a branch**, grenen `main` och mappen `/ (root)`.
3. Sidan publiceras på `https://<användarnamn>.github.io/OP/`.
