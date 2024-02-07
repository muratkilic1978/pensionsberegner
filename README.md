# Implementering af Pensionsberegner i JavaScript

## Trin 1: Anvend use strict
* Skirv use strict øverst i script.js filen

## Trin 2: Definér funktionen 
* Opret funktionen **calculatePension** uden parametre

## Trin 3: Hent elementet for fødselsdato og gem i en variabel
* Find HTML-attributten med id'en 'birthdate' og gem det i en variabel - 'birthdateInput'

## Trin 4: Hent elementet for resultatdiv og gem i en variabel 
* Find HTML-attributten med id'en 'result' og gem det i en variabel 'resultField'

## Trin 5: Lav en ny variabel - retirementAge 
* Opret en ny variabel med navnet - 'retirementAge' og tildel den en tom streng som startværdi


## Trin 6: Lav if-else-if betingelser for at bestemme pensionsalderen
* Med udgangspunkt i nedenstående pensionsoversigts-skema bedes du lave passende if-else-if betingelser til at sammenligne brugerens fødselsdato med de givne datoer og tildele den passende pensionsalder til retirementAge variablen.

### pensionsoversigts-skema 

| Fødselsdato                        | Folkepensionsalder |
|------------------------------------|--------------------|
| 31. december 1953 eller tidligere  | 65 år              |
| 1. januar 1954 – 30. juni 1954     | 65 ½ år            |
| 1. juli 1954 – 31. december 1954   | 66 år              |
| 1. januar 1955 – 30. juni 1955     | 66 ½ år            |
| 1. juli 1955 – 31. december 1962   | 67 år              |
| 1. januar 1963 – 31. december 1966 | 68 år              |
| 1. januar 1967 eller senere        | 69 år              |


## Trin 7: Udskriv tekst ved hjælp af resultField og textContent
Når du har bestemt pensionsalderen bedes du vise teksten - 'Du kan gå på pension ved 67 år', ved at opdatere indholdet i 'resultField' med den beregnede pensionsalder