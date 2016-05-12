# Collections Online manifest

Dette er et oplæg til struktureringen af et open-source projekt - en slags konsortium.

Collections Online er work-in-progress, således er indholdet i dette dokument - og navnet er således også en arbejdstitel.

Collections Online etablerer fælles funktionalitet for at tilgængeliggøre arkiver og museers digitale billeder på internettet, samtidig med at muliggøre funktionel fleksibilitet og individuel branding for at den enkelte organisation.

Collections Online er ikke én fælles online platform hvor en række arkiver og museers blot “hælder data ind”, men tværtimod et teknisk grundlag som den enkelte organisation selv kan benytte og udvikle.

## Baggrunden

Siden maj 2014 har Nationalmuseet sammen med forskellige udviklerteams (herunder Headnet, Socialsquare og museets egen IT udviklingsafdeling) udviklet på en frontend til tilgængeliggørelse af museets billedmateriale. Resultatet er et genbrugeligt fundament som kan benyttes til tilgængeliggørelse af billeder fra et digitalt asset management system.

Det giver på nuværende tidspunkt mening at benytte det fælles grundlag, hvis I som museum eller arkiv:
* Ønsker ikke at “starte fra scratch” når jeres billeder skal tilgængeliggøres.
* Ønsker at benytte offentlige midler på en måde der gavner flest muligt.
* Ønsker at undgå vendor lock-in og ønsker en “flottere kode” under motorhjelmen.
* Benytter Cumulus DAMS: På nuværende tidspunkt er systemet indrettet til at forbinde til Cumulus DAMS - det kan dog tilpasses til at trække billeder fra andre lignende systemer.

Retningslinjer for bidrage:
* Når der tilføjes til den fælles kode til “kernen” må der ikke brydes med bagud kompatibilitet, med mindre det godkendes på tværs af de aktive bidragsydere og semantisk versionering benyttes.
* De aktive bidragsydere har ansvar for at give adgang til nye udviklere ved museer eller arkiver.

Collections Online lever på https://github.com/collections-online
