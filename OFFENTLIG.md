# Retningslinjer for åpen kildekode i Statens pensjonskasse

## Formål

Retningslinjen skal sikre at publisering og forvaltning av åpen kildekode skjer på en trygg, strukturert og bærekraftig måte, i tråd med virksomhetens verdier og sikkerhetskrav.

## Hvorfor åpen kildekode?

Åpen kildekode har mange fordeler, for eksempel:

- **Høyere kvalitet** – eksterne tilbakemeldinger og feilrapportering forbedrer koden og dokumentasjon.
- **Bedre samarbeid og innovasjon** – flere utviklere kan bidra med forbedringer og nye ideer.
- **Økt transparens og tillit** – gir innsyn i hvordan systemene fungerer.
- **Styrket sikkerhet** – flere kan oppdage og fikse sårbarheter.
- **Etisk og juridisk ansvar** – offentlig sektor kan vise åpenhet og ansvarlighet.
- **Sparing av ressurser** – gjenbruk av eksisterende løsninger i stedet for å bygge fra bunnen av.
- **Konkurransefortrinn** – forbedrer omdømmet og tiltrekker talentfulle utviklere.

## Krav til åpne repoer

### Før publisering

All kode må gjennom en dokumentert sikkerhetssjekk før den gjøres offentlig.
Koden skal ikke inneholde sensitiv informasjon eller interne systemdetaljer. Dette inkluderer også kodehistorikken, alle tidligere commits, som kan være synlig.
Ansvarlig team og kontaktperson må være definert.

### Etter publisering – forvaltning og oppfølging

Hvert team må ha ansvar for videre vedlikehold og sårbarhetsoppfølging.
Det må være krav til hvor raskt sårbarheter skal håndteres – maks 10 virkedager.
Sikkerhetssenteret skal kunne følge opp team som ikke håndterer svakheter som rapporteres.

### Lisens

Alle åpne repositorier skal inkludere en LICENSE-fil med MIT-lisensen. Dette gir brukere og bidragsytere tydelig oversikt over rettigheter og forpliktelser.

### README

Alle repositorier må ha en forklarende README-fil som beskriver hensikten med repositoriet.

## Etiske regler

Vi benytter [etiske regler](https://github.com/statens-pensjonskasse/.github/CODE_OF_CONDUCT.md) basert på [Contributor Covenant](https://www.contributor-covenant.org/) for å sikre et inkluderende, respektfullt og konstruktivt bidragsmiljø. Reglene gjelder både interne og eksterne bidragsytere.

## Sikkerhet

### Ved mottak av sårbarhetsrapport

Eksterne må ha en tydelig kanal for å rapportere sikkerhetsfunn se [SIKKERHET](https://github.com/statens-pensjonskasse/.github/SECURITY.md).

## Hvordan komme i gang?

All informasjon du trenger for å komme i gang finner du i vår interne [utvikler håndbok](https://handbok.utv.spk.no/plattform/github/).

## Referanser

Kilde som brukes til inspirasjon:

- [NAV offentlig](https://github.com/navikt/offentlig)
- [DigDir overordnede arkitekturprinsipper ](https://www.digdir.no/digital-samhandling/overordnede-arkitekturprinsipper/1065)
- [Altinn](https://github.com/Altinn/.github/blob/main/profile/README.md)
- [Offentleglova](https://lovdata.no/dokument/NL/lov/2006-05-19-16)
- [Contributor covenant](https://www.contributor-covenant.org/)
