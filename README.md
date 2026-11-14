# Innsynsdokumenter

565 oppdiktede øvingsdokumenter fra [Paragrafkarusellen](https://spill.magnehg.no), et spill for å øve på offentleglova.
Hvert dokument finnes i to utgaver: som ren PDF og i dårlig kvalitet, slik dokumenter ofte ser ut når de kommer inn
til et arkiv.

| Mappe | Innhold |
|---|---|
| [`pdf/`](pdf/) | Alle dokumentene som A4-PDF med søkbar tekst og vektorgrafikk, én fil per dokument. |
| [`skannet/`](skannet/) | De samme dokumentene skannet, fotografert, kopiert på kopimaskin og fakset (PDF, JPG, PNG og TIF). En fjerdedel av brevene er håndskrevet med varierende tydelighet, og en del har for lav kontrast. |
| [`samlet/`](samlet/) | Hver utgave slått sammen til én PDF, i nummerrekkefølge og med ett bokmerke per dokument. |
| [`zip/`](zip/) | Hver utgave som zip-fil med README og lisens, til nedlasting. |

## Last ned

### Én utgave som zip

Klikk på lenken, så starter nedlastingen:

- [paragrafkarusellen-dokumenter-pdf.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/paragrafkarusellen-dokumenter-pdf.zip) (16 MB): alle dokumentene som PDF
- [paragrafkarusellen-dokumenter-skannet.zip](https://github.com/magnehg/innsynsdokumenter/raw/main/zip/paragrafkarusellen-dokumenter-skannet.zip) (40 MB): alle dokumentene i dårlig kvalitet

Hver zip har enkeltdokumentene, `oversikt.csv`, `README.md` og `LICENSE.txt`.

### Alt som én zip

Trykk på den grønne knappen **Code** øverst på [forsiden av repoet](https://github.com/magnehg/innsynsdokumenter)
og velg **Download ZIP**, eller bruk
[denne lenken](https://github.com/magnehg/innsynsdokumenter/archive/refs/heads/main.zip). Da får du begge utgavene,
de samlede PDF-ene og zip-filene i én fil (ca. 190 MB).

### Alt i én PDF

- [Samlet PDF](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/paragrafkarusellen-dokumenter-pdf-samlet.pdf) (18 MB)
- [Samlet skannet PDF](https://github.com/magnehg/innsynsdokumenter/raw/main/samlet/paragrafkarusellen-dokumenter-skannet-samlet.pdf) (55 MB)

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

## Innhold

- **001–500:** brev, notater, interne dokumenter og e-poster.
- **501–565:** SMS-tråder skrevet på 50 norske dialekter, multietnolekt og ti andre språkformer (svorsk, dansk-norsk,
  samiske og kvenske innslag og norsk som andrespråk).

`oversikt.csv` i `pdf/` og `skannet/` viser nummer, filnavn, tittel og avsender. I `skannet/` viser den også om
dokumentet er håndskrevet, om kontrasten er lav, hvordan det er tatt opp, oppløsningen og antall sider.

## Lisens

© 2026 Magne Haagen Grøtting (<https://magnehg.net>).

Dokumentene er lisensiert under **Creative Commons Navngivelse-DelPåSammeVilkår 4.0 Internasjonal (CC BY-SA 4.0)**.
Hele lisensteksten står i `LICENSE` og på <https://creativecommons.org/licenses/by-sa/4.0/legalcode.no>
(sammendrag: <https://creativecommons.org/licenses/by-sa/4.0/deed.no>).

Du kan kopiere, dele, endre og bruke dokumentene til hva som helst, også kommersielt, så lenge du

- **navngir:** oppgir kilden og lisensen og sier fra om du har endret noe, og
- **deler på samme vilkår:** gir ut det du har laget av dokumentene under CC BY-SA 4.0 eller en forenlig lisens.

Foreslått navngivelse:

> Dokumenter fra Paragrafkarusellen av Magne Haagen Grøtting (https://magnehg.net), lisensiert under CC BY-SA 4.0
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
under the same licence.
