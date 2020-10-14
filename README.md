# Innrapportering helseregister

KLADD! UNDER UTARBEIDELSE!

## Plan

Utvikle områdeprofiler og best practice for innrapporering til helseregistere. Fokus på muligheter og overgangsarkitekturer. Behov for å støtte både strukturert, ikke strukturert og delvis strukturert informasjon.

## Behov og krav
- Benytte eksisterende/kommende områdeprofiler og/eller basisprofiler for Patient, Encounter, visse typer Observations.
  - Trolig utvidelse av HelseAPI, med inspirasjon av f.eks. FHIR IPA, IPS, Argonaut/US Core.  
- Profiler og best practice for Questionnaire og QuestionnaireResponse
  - Questionnaire: Bruk av identifikator for variabel fra metadataregisteret og lokal variabel-identifikator (det enkelte register) 
- Beskrive hvordan profilene kan benyttes med flere arkitekturer, som dokumenter (bundle/composition), portaler, SMART on FHIR etc.
  - REST API i EPJ/fagsystem krever HelseAPI-profiler, f.eks. i bruk med SMART on FHIR. 

## Kontaktpersoner

- linnbrandt
- rockphotog
