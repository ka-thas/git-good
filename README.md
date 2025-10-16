![Git Good banner](assets/git-good-banner-2.png)

<!-- 
# Git Good

> Sted: Java og Logo (Se beskrivelse)
>
> Dato: Onsdag 12. mars
>
> Tid: 16:15 - 18:00

Samarbeidsarrangement med:

- FUI - Fagutvalget ved Intitutt for Informatikk
- Mikro - Linjeforeningen for Robotikk og Intelligent Systemer
- Progsys - Linjeforeningen for Programmering og Systemarkitektur
 -->

## Innhold

- [Innhold](#innhold)
- [Beskrivelse (samme som på Peoply og FB)](#beskrivelse-samme-som-på-peoply-og-fb)
- [Ekstra info](#ekstra-info)
  - [Prøv dette før workshopen](#prøv-dette-før-workshopen)

[Her finner dere opplegget som ble gjennomgått](https://github.com/ka-thas/git-good/blob/main/rookie-opplegg.md)

## Beskrivelse (samme som på Peoply og FB)

Velkommen til Git Good!

Har du lyst til å få innføring i verdens mest brukte versjonskontrollsystem, og gjøre deg klar til arbeidslivet?

Bli med for å få hands-on erfaring i Git og plattformen GitHub.

- Ka Thas skal holde workshop for nybegynnere der man får hjelp med oppsett, lage repo, clone, samarbeid, tips og triks, og best practices. Møt opp på `seminarrom Logo`.

## Ekstra info

Kommandoene dere skal lære:

```bash
git add .
git commit -m "melding"
git push
git pull

git clone <URL>

git status
git log

git branch
git merge
```

### Prøv dette før workshopen

Det er ikke farlig om du ikke får det til

Last ned git - dette kan du google deg frem til

> [!TIP]
>
> OBS! Windows-brukere
>
> Når du installerer git må du huske å velge alternativ 2 når du blir spurt følgende:
>
> **Adjust PATH Environment**
>
> - `Git Bash only` (Minimal, does not modify system PATH)
> - `Git from the command line and 3rd-party software` (Recommended, allows usage in PowerShell & CMD)
> - `Git and Unix tools from the command line` (Adds Unix tools, may cause conflicts)

For å sjekke om du allerede har git eller om nedlasting var vellykket kjør kommandoen
`git --version` i terminalen

```bash
$git --version
>git version 2.39.5 (Apple Git-154)
```

Du kan nå teste git ved å lage en ny mappe og opprette et repo

```bash
$mkdir test-git
$cd test-git
$git init

$echo tester git  >> README.md

$git add .
$git commit -m "initial commit"
```
