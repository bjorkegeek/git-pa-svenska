# Git på svenska

## Om detta dokument

Detta dokument bygger på github-användaren *bjorne*s
version. *bjorkegeek* har omarbetat dokumentet enligt följande:

  * Plockat bort vissa infantilismer, såsom att översätta egennamnet
    *git* med "jävel".

  * Ändrat fokus från hur vi talar *med* git, till hur vi talar *om* git.
    I linje med detta har git- och skalalias plockats bort.      

  * Något begrepp har lagts till eller ändrats.

## Introduktion

Det dagliga språket för de olika kommandona i `git` är på svenska ett
enda stort svengelskakalas. Jag finner mig själv ofta sägandes _"Kan
du pusha branchen?"_ eller _"Jag pullar!"_, vilket känns pinsamt.

Detta dokument ämnar etablera en ren svensk jargong som kan användas
på arbetsplatsen för att med fördel undvika pressade situationer med
kollegor.

## Förslag

Nedan följer tabeller över verb och substantiv relaterade till git,
deras nuvarande bruk samt förslag på hur vi tillsammans kan bättra
oss.

| Verb        | Nuvarande bruk | Förslag       |
|-------------|----------------|---------------|
| pull        | pulla          | rycka         |
| push        | pusha          | trycka        |
| fetch       | fetcha         | hämta         |
| branch      | brancha        | förgrena      |
| commit      | commita        | lämna över    |
| rebase      | rebasa         | ympa          |
| merge       | merga          | sammanfoga    |
| stash       | stasha         | gömma         |
| tag         | tagga          | märka         |
| cherry-pick | cherry-picka   | plocka russin |
| amend       | amenda         | rätta till    |
| checkout    | checka ut      | kolla         |
| add         | adda           | lägg till     |

| Substantiv   | Nuvarande bruk | Förslag     |
|--------------|----------------|-------------|
| repository   | repo           | förråd      |
| branch       | branch         | gren        |
| commit       | commit         | överlämning |
| pull request | pull request   | ryckbegäran |
| stash        | stash          | gömma       |
| tag          | tagg           | märke       |
| master       | master         | ledar(e)    |

## Exempel

    - Kan du rycka grenen jag just ympade och trycka till github?

    - Jag förgrenade alldeles nyss och lämnade över ändringarna från
      min gömma där.

    - Skicka en ryckbegäran när du är färdig med sammanfogningen!

    - Låt oss plocka russin från ledar-grenen.

## Bash-alias

    gitt kolla --ny funktion/braskit
    $EDITOR minfil.py
    gitt lägg-till minfil.py
    gitt överlämpa --meddelande 'lade till bra skit'
    gitt kolla mästare
    gitt ryck härkomst/mästare
    gitt ympa funktion/braskit
    gitt tryck härkomst/mästare
    
