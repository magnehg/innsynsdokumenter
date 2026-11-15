# Fasit

> **Advarsel:** Denne mappen inneholder svarene. Skal du øve på dokumentene, bør du ikke åpne `fasit.xml` først.

`fasit.xml` er et forslag til fasit for alle de 765 dokumentene i repoet: hva som er offentlig, hva som bør sladdes
eller unntas, hvilken hjemmel som gjelder, og hvilke opplysninger som er sensitive.

## Fasiten er et forslag

- **`kilde="spillet"` (500 dokumenter, nr. 001–500):** fasiten fra Paragrafkarusellen.
- **`kilde="forslag"` (265 dokumenter):** utkast laget med KI for SMS-ene (501–565), innbyggerbrevene (566–615) og
  de fem øvingsheftene. Ingen jurist har kvalitetssikret dem. Tvil er skrevet i `<kommentar>` på det enkelte
  dokumentet.

Innsynsvurderinger er skjønn. Ofte er flere svar forsvarlige, og svaret kan avhenge av når kravet kommer, for eksempel
før eller etter at en leverandør er valgt. Bruk fasiten som et utgangspunkt, ikke som en autoritativ kilde.
Leddhenvisningene bør sjekkes mot lovteksten. Meld gjerne fra om feil under
[Issues](https://github.com/magnehg/innsynsdokumenter/issues).

## Struktur

```xml
<fasit>
  <hjemler>…</hjemler>          <!-- kodene som brukes: O (§ 3), 13, 14, 15, 18, 20–26 og «annet» -->
  <kategorier>…</kategorier>
  <samling id="paragrafkarusellen | hefte-a | hefte-b | hefte-c | hefte-d | hefte-p">
    <dokument nr="014">
      <tittel>…</tittel>
      <filer><fil utgave="pdf">pdf/014-….pdf</fil><fil utgave="skannet">skannet/014-….pdf</fil></filer>
      <vurdering resultat="offentlig | delvis | unntas" omfang="ingen | deler | hele" kilde="spillet | forslag">
        <hjemmel kode="13" type="plikt | kan">§ 13 jf. forvaltningsloven § 13 første ledd nr. 1</hjemmel>
        <alternativ kode="…"/>   <!-- andre forsvarlige hjemler -->
        <felle kode="…"/>        <!-- nærliggende, men feil (bare fra spillet) -->
        <begrunnelse>…</begrunnelse>
      </vurdering>
      <sensitivt>
        <opplysning kategori="helse" hjemmel="13" sokbar="ja | nei">ordrett tekst fra dokumentet</opplysning>
        <kommentar>…</kommentar>
      </sensitivt>
    </dokument>
  </samling>
</fasit>
```

- **`merinnsyn="vurderes"`** står på vurderinger med en «kan»-hjemmel (offentleglova § 11).
- **`sokbar="nei"`** betyr at opplysningen ikke kan finnes ved å søke på ord som «sykmeldt» eller «gjeld». Den
  fremgår bare av sammenhengen, av dialekten eller av hvordan noe er sagt.
- **`fremgaar="sammenheng"`** på `<sensitivt>` betyr at ingen av opplysningene i dokumentet er søkbare.
- **`type="bilde"`** og **`type="tabellcelle"`** gjelder et fotografi eller én celle i en tabell.
- **`treff="omtrentlig"`** betyr at teksten går over flere tabellceller, og **`ordrett="avskrift-fra-bilde"`** at
  dokumentet er skannet eller håndskrevet, slik at utdragene er skrevet av fra bildet.

Utdragene er ellers kontrollert mot teksten i PDF-utgaven. I den skannede utgaven må de finnes med tekstgjenkjenning.

Lisens: CC BY-SA 4.0, se [README](../README.md) i rota.
