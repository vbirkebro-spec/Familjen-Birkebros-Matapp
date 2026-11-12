# Matappen – överenskomna krav 12 november 2026, efter kl. 21

Detta är beslutad produktlogik för Familjen Birkebros matresa. Implementera i befintliga appen utan att ta bort befintliga recept eller användardata.

## Veckoplan
- Tre vardagsstorkok: söndag Viktor 8 portioner, söndag Linda 8 portioner, torsdag Linda 8 portioner.
- Fredagsmiddag planeras separat som helgmat. Lunch fredag, lördag och söndag ska täckas av planerade rätter; torsdagsrätten är normalt avsedd för torsdag kväll och dessa luncher. Tillåt användaren att justera.
- Två vuxna äter 1 vuxenportion var; Wilma och Gabriel 0,5 vardera. Familjemiddag = 3 vuxenportioner.
- Recepten beräknas alltid på 8 vuxenportioner per storkok; håll koll på återstående portioner och rekommendera infrysning vid längre förvaring.
- Föreslå veckomeny automatiskt ur vardagsrecepten; kunna slumpa om och manuellt ändra rätter, tid och ansvarig.
- Kalenderknapp 'Skicka till våra kalendrar' ska först efter aktivt tryck skapa Google Kalender-händelse med rätt, ansvarig, tid och båda deltagarna. Skicka ingenting automatiskt. Kalenderadresser är kända i samtalet men ska inte hårdkodas publikt. Kräver säker Google OAuth/backend; ICS-export är befintlig reservlösning.

## Recept
- Sju mottagna vardagsrecept (originalbilder fram/baksida ska bevaras där rättigheter och lagring medger):
1. Krämig prosciuttopasta med portobello och basilika
2. Pannstekt halloumi med varm kikärtssallad och citrondressing
3. Asiatiska blandfärstacos med pak choi och sriracha
4. Krispig BBQ-kyckling med kålsallad och aioli
5. Pasta med krispig prosciutto och balsamicotomater
6. Bräserad ciderkyckling med äpple och timjan (kategori vardag/helg ännu inte bekräftad)
7. Ugnspannkaka med keso och skinka
- Alla ska skalas från original till 8 portioner, med korrekta ingredienser, steg och foton. Verifiera bildavläsning innan publicering av exakta mängder.
- Ugnspannkaka: IGNORERA handskrivna anteckningar. Tryckt grundrecept 4 portioner: 200 g skinka, 8 ägg; 8 portioner: 400 g skinka, 16 ägg, 3 dl matgrädde, 500 g keso, 300 g riven ost; sylt och morötter till servering.
- Skilj vardagsrecept från helg- och bjudrecept; Linda ska kunna påverka utformning senare.

## Inköpslista och kvitton
- 14 kvitton från Willys Ekholmen, 22 juli–7 november 2026, utgör underlag för produktkatalog, köpintervall, mängder och ungefärliga priser. Underlaget måste först transkriberas/verifieras; anta inte att kvittodatum är förbrukningsdatum.
- Förslag på återköp ska vara redigerbara och kombineras med ingredienser för veckans meny.
- Standardvaror på varje inköpslista: 4 × 1,5 l ekologisk mjölk, 2 × 15 ägg, 2 förpackningar grekisk yoghurt naturell 0 %.
- Inköpslistan ska sammanföra dubbletter, vara lätt att bocka av och helst grupperas efter butikskategori.

## Viktigt
- Nuvarande publicerade app har webbläsarlokal lagring, inte delad familjesynk. Lös säker delning separat.
- Detta dokument är en kravsammanställning, inte bevis på att alla funktioner är implementerade eller publicerade.
