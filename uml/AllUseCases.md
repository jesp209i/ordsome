# Use cases

| Prio | UC Code | UC titel | Beskrivelse |
|---|---|---|---|
| 1. | UC-A1 | Anmodning om oversættelse | “Turisten” ser en tekst som han ikke forstår. Han bruger en klient til at sende teksten. Efter noget tid får turisten svar. |
| 1. | UC-B1 | Besvar oversættelsesanmodning | “Oversætteren” modtager en tekst. Oversætteren indskriver en ny oversat tekst (og gemmer/sender). |
| 2. | UC-A4 | Luk og godkend Oversættelse | “Turisten” har modtaget et svar han er glad for. Dette angives på svares og systemet lukker anmodningen. (Anmodningen sendes ikke ikke længere til oversættere) |
| 3. | UC-A5 | Luk oversættelse, uden godkend | “Turisten” skal ikke bruge anmodningen alligevel, og angiver at han vil lukke anmodningen. (Anmodningen sendes ikke længere til oversættere - og ingen godkendt oversættelse) |
| 4. | UC-AB1 | Bruger omdannes til oversætter | En bruges angiver hvilket/hvilke sprog hvor han kan hjælpe med at oversætte. |
| 5. | UC-C2 | Anmodning videresendes til korrekte oversættere | “Oversættelsesservicen” modtager en anmodning (eks.: polsk => dansk). Anmodningen sendes kun videre til oversættere med disse kompetencer |
| 6. | UC-B3 | Afvisning af oversættelsesanmodning | “Oversætteren” modtager en anmodning han ikke vil gennemføre. Han afviser anmodningen og den vises ikke længere til oversætteren. (anmodningen lever dog videre i “systemet”) |
| 7. | UC-A2 | Anmodning om oversættelse via foto | “Turisten” taget et billede af noget tekst han ikke forstår, med sit device. Afsluttes som UC-A1. |
| 8. | UC-A3 | Tilføj kontekst til anmodning | “Turisten” tilføjer “tags” til sin anmodning, for at gøre baggrunden for oversættelsen tydeligere. |
| 9. | UC-C1 | Genbrug af svar | “Oversættelsesservicen” genkender en ny anmodning som ligner en gammel anmodning, og sender det/de tidligere godkendte svar. |
| 10. | UC-B2 | Anmod om mere info til oversættelse | “Oversætteren” mangler kontekst til den tekst der skal oversættes, og beder systemet om dette. Efter noget tid får oversætteren svar - eller - mulighed for at kommunikere med turisten etableres. |

| Code Type | Beskrivelse |
|---|---|
| A | Relateret til en bruger der anmoder en oversættelse |
| B | Relateret til en bruger der besvarer en anmodning |
| C | Relateret til systemet |
| AB | Relateret til både brugertype A og B |
