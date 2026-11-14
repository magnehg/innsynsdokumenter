# Innsynsdokumenter

Oppdiktede dokumenter til å øve på innsynsbehandling etter offentleglova: 565 dokumenter fra
[Paragrafkarusellen](https://spill.magnehg.no), et spill for å øve på offentleglova, og 150 dokumenter fra fem
øvingshefter. Dokumentene fra Paragrafkarusellen finnes i to utgaver: som ren PDF og i dårlig kvalitet, slik dokumenter ofte ser ut når de kommer inn
til et arkiv.

| Mappe | Innhold |
|---|---|
| [`pdf/`](pdf/) | Alle dokumentene som A4-PDF med søkbar tekst og vektorgrafikk, én fil per dokument. |
| [`skannet/`](skannet/) | De samme dokumentene skannet, fotografert, kopiert på kopimaskin og fakset (PDF, JPG, PNG og TIF). En fjerdedel av brevene er håndskrevet med varierende tydelighet, og en del har for lav kontrast. |
| [`samlet/`](samlet/) | Hver utgave slått sammen til én PDF, i nummerrekkefølge og med ett bokmerke per dokument, og de fem øvingsheftene som hele PDF-er. |
| [`hefter/`](hefter/) | De 150 dokumentene fra fem øvingshefter, én mappe per hefte og kommune og én PDF per dokument. |
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
under the same licence.
