# Innrapportering helseregister

KLADD! UNDER UTARBEIDELSE! Være med på utviklingen? [Ta kontakt!](https://hl7norway.github.io/best-practice/docs/contact.html)

## Plan

Utvikle områdeprofiler og best practice for innrapporering til helseregistere. Fokus på muligheter og overgangsarkitekturer. Behov for å støtte både strukturert, ikke strukturert og delvis strukturert informasjon.

## Behov og krav

- Følge [prinsipper](https://hl7norway.github.io/best-practice/docs/no-national-profiles-principles.html) og [metode for utvikling av områdeprofiler](https://hl7norway.github.io/best-practice/docs/no-domain-metode/innledning.html), samt "[Den gode implementasjonsguide](https://hl7norway.github.io/best-practice/docs/dgi/)" (under utvikling). Dette er nødvendig for at områdeprofilene kan bli [normert nasjonalt av Direktoratet for e-helse](https://ehelse.no/standarder)
- Benytte eksisterende/kommende områdeprofiler og/eller basisprofiler for Patient, Encounter, visse typer Observations. Etablere beste praksis for bruk av nasjonale basis- og områdeprofiler på registerområdet. 
- Profiler og best practice for FHIR Questionnaire og QuestionnaireResponse
  - Questionnaire: Bruk av identifikator for variabel fra metadataregisteret og lokal variabel-identifikator (det enkelte register)
- Etablere god praksis for å kombinere bruk av strukturerte elementer (i form av FHIR ressurser/ profiler) og ustruktuerte elementer (i form av FHIR Questionnaire) 
- Beskrive hvordan profilene kan benyttes med flere arkitekturer, som dokumenter (bundle/composition), portaler, SMART on FHIR etc.
  - REST API i EPJ/fagsystem krever HelseAPI-profiler, f.eks. i bruk med SMART on FHIR. 

## Avhengigheter

Trolig et stort behov for områdeprofiler for f.eks. Procedure, Encounter og en rekke Observations m.m. som ikke naturlig vil ligge under denne implementasjonsguiden. Utkast til disse kan dog med fordel gjøres i dette prosjektet. 

## Aktuelle integrasjonsprosjekter med lignende anvendelse

- Innrapportering Dødsårsaksregisteret _FHI/Skatteetaten/FREG_ (API + portal?)
- All "skjema-basert" innrapportering til helseregistere
- Førerkortfornyelse _Helsedirektoratet/Statens vegvesen_ (SMART on FHIR-app)
- Integrasjon Helseplattformen og kvalitetsregistere _Helse Midt-Norge RHF_

## Brainstorm

NB!: Bundle/composition er brukt under, men områdeprofilene skal være uavhengig av samhandlingsform (som REST API, dokument, messaging etc.)

![lysbilde](images/Lysbilde6.PNG)
![lysbilde](images/Lysbilde7.PNG)
![lysbilde](images/Lysbilde8.PNG)


## Kontaktpersoner

- Linn Brandt - [linnbrandt](https://github.com/linnbrandt)
- Espen Stranger Seland - [rockphotog](https://github.com/rockphotog)
