# Innsynsdokumenter

Oppdiktede dokumenter til å øve på innsynsbehandling etter offentleglova: 615 dokumenter fra
[Paragrafkarusellen](https://spill.magnehg.no), et spill for å øve på offentleglova, og 150 dokumenter fra fem
øvingshefter. Dokumentene fra Paragrafkarusellen finnes i to utgaver: som ren PDF og i dårlig kvalitet, slik dokumenter ofte ser ut når de kommer inn
til et arkiv.

| Mappe | Innhold |
|---|---|
| [`pdf/`](pdf/) | Alle dokumentene som A4-PDF med søkbar tekst og vektorgrafikk, én fil per dokument. |
| [`skannet/`](skannet/) | De samme dokumentene skannet, fotografert, kopiert på kopimaskin og fakset (PDF, JPG, PNG og TIF). En fjerdedel av brevene er håndskrevet med varierende tydelighet, og en del har for lav kontrast. |
| [`samlet/`](samlet/) | Hver utgave slått sammen til én PDF, i nummerrekkefølge og med ett bokmerke per dokument, og de fem øvingsheftene som hele PDF-er. |
| [`hefter/`](hefter/) | De 150 dokumentene fra fem øvingshefter, én mappe per hefte og kommune og én PDF per dokument. |
| [`zip/`](zip/) | Hver utgave og hvert øvingshefte som zip-fil med README og lisens, til nedlasting. |

## Bruk og tilbakemeldinger

Dokumentene er laget for å brukes. Jeg ser gjerne at de brukes til

- trening, finjustering og evaluering av KI-modeller og andre verktøy for innsynsbehandling, sladding og
  dokumentklassifisering
- testing av tekstgjenkjenning (OCR) og tolking av håndskrift, dialekter og dokumenter i dårlig kvalitet
- opplæring og øving i offentleglova, forvaltningsloven og taushetsplikt
- forskning, undervisning og utvikling av arkiv- og saksbehandlingssystemer.

Lisensen (CC BY-SA 4.0) tillater all slik bruk, også kommersiell. Det eneste kravet er at du navngir kilden og
deler bearbeidede versjoner av dokumentene på samme vilkår.

**Trente modeller:** Som rettighetshaver gir jeg i tillegg denne tillatelsen: En KI-modell som er trent, finjustert
eller evaluert på dokumentene, regner jeg ikke som en bearbeidet versjon av dem. Modellen, vektene og det den
produserer kan derfor brukes og gis ut under hvilken som helst lisens, også lukket og kommersielt. Kravet om deling
på samme vilkår gjelder bare når selve dokumentene, eller endrede utgaver av dem, deles videre.

Jeg vil gjerne høre fra deg om du bruker dokumentene, finner feil eller savner dokumenttyper, dialekter eller
vanskelige tilfeller. Opprett en sak under
[Issues](https://github.com/magnehg/innsynsdokumenter/issues), eller ta kontakt via <https://magnehg.net>.

## Innhold fra Paragrafkarusellen

- **001–500:** brev, notater, interne dokumenter og e-poster. (Innhold fra [Paragrafkarusellen](https://spill.magnehg.no))

Tillegg for trening av AI: 
- **501–565:** SMS-tråder skrevet på 50 norske dialekter, multietnolekt og ti andre språkformer (svorsk, dansk-norsk,
  samiske og kvenske innslag og norsk som andrespråk).
- **566–615:** brev og e-poster fra innbyggere som er forvirret, rasende eller overbevist om at lover og regler ikke
  gjelder dem. Det går ikke fram av enkeltord at avsenderen bør skjermes, bare av sammenhengen.

`oversikt.csv` i `pdf/` og `skannet/` viser nummer, filnavn, tittel og avsender. I `skannet/` viser den også om
dokumentet er håndskrevet, om kontrasten er lav, hvordan det er tatt opp, oppløsningen og antall sider.

### Én utgave som zip

Klikk på lenken, så starter nedlastingen:

- [paragrafkarusellen-dokumenter-pdf.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/paragrafkarusellen-dokumenter-pdf.zip) (17 MB): alle dokumentene som PDF
- [paragrafkarusellen-dokumenter-skannet.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/paragrafkarusellen-dokumenter-skannet.zip) (44 MB): alle dokumentene i dårlig kvalitet

Hver zip har enkeltdokumentene, `oversikt.csv`, `README.md` og `LICENSE.txt`.

## Øvingshefter for klasseromsundervisning som enkeltdokumenter
Fem øvingshefter fra ([magnehg.no/](https://www.magnehg.no/ressurser-for-innsyn/)) omdannet til enkeltdokumenter. 
Hvert hefte inneholder 30 dokumenter med innhold som typoisk offentlighetsvurderes i en kommune. 

### Øvingshefter for klasseromsundervisning som enkeltdokumenter
- [ovingshefte-a-ankerfjorden.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/ovingshefte-a-ankerfjorden.zip) (15 MB): hefte A, Ankerfjorden kommune
- [ovingshefte-b-bremyr.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/ovingshefte-b-bremyr.zip) (15 MB): hefte B, Bremyr kommune
- [ovingshefte-c-cicignon.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/ovingshefte-c-cicignon.zip) (15 MB): hefte C, Cicignon kommune
- [ovingshefte-d-djupdalen.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/ovingshefte-d-djupdalen.zip) (15 MB): hefte D, Djupdalen kommune
- [ovingshefte-p-plenumsvik.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/ovingshefte-p-plenumsvik.zip) (5 MB): hefte P, Plenumsvik kommune

Hver zip har de 30 enkeltdokumentene, hele heftet, `oversikt.csv`, `README.md` og `LICENSE.txt`.

### Alt som én zip

Trykk på den grønne knappen **Code** øverst på [forsiden av repoet](https://github.com/magnehg/innsynsdokumenter)
og velg **Download ZIP**, eller bruk
[denne lenken](https://github.com/magnehg/innsynsdokumenter/archive/refs/heads/main.zip). Da får du begge utgavene,
de samlede PDF-ene og zip-filene i én fil (ca. 335 MB).

### Alt i én PDF

- [Samlet PDF](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/paragrafkarusellen-dokumenter-pdf-samlet.pdf) (18 MB)
- [Samlet skannet PDF](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/paragrafkarusellen-dokumenter-skannet-samlet.pdf) (59 MB)

### Fra kommandolinjen

```sh
# én utgave
curl -LO https://github.com/magnehg/innsynsdokumenter/raw/main/zip/paragrafkarusellen-dokumenter-pdf.zip
curl -LO https://github.com/magnehg/innsynsdokumenter/raw/main/zip/paragrafkarusellen-dokumenter-skannet.zip

# hele repoet
git clone --depth 1 https://github.com/magnehg/innsynsdokumenter.git
```

### Ett enkelt dokument

Åpne filen i [`pdf/`](pdf/) eller [`skannet/`](skannet/) og trykk på nedlastingsknappen (pil ned) øverst til høyre.

## Øvingsheftene

Fem øvingshefter med 30 dokumenter hver, fra hver sin oppdiktede kommune. Dokumentene er ordnet etter saken de
gjelder, med innsynskravet først. Hefte P handler om politisk møtebehandling.

| Hefte | Kommune | Enkeltdokumenter | Hele heftet |
|---|---|---|---|
| A | Ankerfjorden kommune | [`hefter/hefte-a-ankerfjorden/`](hefter/hefte-a-ankerfjorden/) | [Ovingshefte_A_innsyn_FIKTIV_v1.1.pdf](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/Ovingshefte_A_innsyn_FIKTIV_v1.1.pdf) |
| B | Bremyr kommune | [`hefter/hefte-b-bremyr/`](hefter/hefte-b-bremyr/) | [Ovingshefte_B_innsyn_FIKTIV_v1.1.pdf](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/Ovingshefte_B_innsyn_FIKTIV_v1.1.pdf) |
| C | Cicignon kommune | [`hefter/hefte-c-cicignon/`](hefter/hefte-c-cicignon/) | [Ovingshefte_C_innsyn_FIKTIV_v1.1.pdf](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/Ovingshefte_C_innsyn_FIKTIV_v1.1.pdf) |
| D | Djupdalen kommune | [`hefter/hefte-d-djupdalen/`](hefter/hefte-d-djupdalen/) | [Ovingshefte_D_innsyn_FIKTIV_v1.1.pdf](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/Ovingshefte_D_innsyn_FIKTIV_v1.1.pdf) |
| P | Plenumsvik kommune | [`hefter/hefte-p-plenumsvik/`](hefter/hefte-p-plenumsvik/) | [Ovingshefte_P_innsyn_FIKTIV_v1.0.pdf](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/Ovingshefte_P_innsyn_FIKTIV_v1.0.pdf) |

Hele heftet har i tillegg forside, omtale av kommunen, oppgaver og dokumentoversikt.


## Lisens

© 2026 Magne Haagen Grøtting (<https://magnehg.net>).

Dokumentene er lisensiert under **Creative Commons Navngivelse-DelPåSammeVilkår 4.0 Internasjonal (CC BY-SA 4.0)**.
Hele lisensteksten står i `LICENSE` og på <https://creativecommons.org/licenses/by-sa/4.0/legalcode.no>
(sammendrag: <https://creativecommons.org/licenses/by-sa/4.0/deed.no>).

Du kan kopiere, dele, endre og bruke dokumentene til hva som helst, også kommersielt, så lenge du

- **navngir:** oppgir kilden og lisensen og sier fra om du har endret noe, og
- **deler på samme vilkår:** gir ut det du har laget av dokumentene under CC BY-SA 4.0 eller en forenlig lisens.

Foreslått navngivelse:

> Dokumenter fra Paragrafkarusellen og øvingsheftene av Magne Haagen Grøtting (https://magnehg.net), lisensiert under CC BY-SA 4.0
> (https://creativecommons.org/licenses/by-sa/4.0/).

## Om innholdet

Dokumentene er laget for å øve på offentleglova. Alle organer, personer, adresser, telefonnumre,
organisasjonsnumre, saksnumre og e-postadresser er **oppdiktet**. Likhet med virkelige personer eller
saker er tilfeldig. Filene inneholder ingen fasit.

Skrifttypene som er brukt (Source Sans 3, IBM Plex Mono, Liberation Sans og håndskriftene fra Google Fonts)
er lisensiert under SIL Open Font License 1.1, som tillater at de bygges inn i dokumenter.
Lisensen for dokumentene gjelder ikke selve skrifttypene.

---

**English summary:** These fictional practice documents from Paragrafkarusellen, © 2026 Magne Haagen Grøtting (https://magnehg.net),
are licensed under CC BY-SA 4.0. See `LICENSE`. Attribute as shown above and share adaptations
under the same licence. As an additional permission from the rights holder, AI models trained, fine-tuned or evaluated on
the documents are not considered adaptations and may be released under any licence.
