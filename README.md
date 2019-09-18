# SAFEST
Formålet med prosjektet er å etablere en kilde til strukturert legemiddelinformasjon som understøtter behovene i sykehus. Informasjonen skal være elektronisk tilgjengelig gjennom et spørregrensesnitt til bruk i kliniske systemer.

## Bakgrunn
Sykehusene i Norge har per i dag ikke tilgang til én felles kilde til strukturert legemiddelinformasjon til bruk i kliniske systemer. Innføringen av elektronisk kurve, elektronisk pasientjournal og Kjernejournal er kommet langt. Legemiddelverket leverer i dag kvalitetssikret strukturert legemiddelinformasjon til bruk i e-resept (FEST). Alle som skal forskrive en e-resept må bruke FEST som grunnlagskilde. Her ligger også en del beslutningsstøtte, som for eksempel interaksjoner og varsler om legemiddelmangel.
 
Sykehusene har flere behov og ønsker til strukturert legemiddelinformasjon enn det FEST for e-resept inneholder. Dette løses delvis i dag ved å komplettere og kompensere for dette regionalt, noe som er ressurskrevende.

Formålet med prosjektet "SAFEST gjennomføring" er å etablere og tilgjengeliggjøre en kilde til strukturert legemiddelinformasjon som understøtter behovene i sykehus. Fire prioriterte behovsområder er omfanget til prosjektet:
Entydige, strukturerte, standardiserte grunnlagsdata om legemidler (for eksempel styrke, form, pakninger osv.).
Virkestoffinformasjon som understøtter virkestoffordinasjon/forordning i elektronisk kurve.
Produktkode på ulike pakningsnivå og endoser som understøtter blant annet lukket legemiddelsløyfe (LLS).
Strukturert innholdsinformasjon i ernæringsprodukter som understøtter blant annet næringsregnskap.
Løsningen skal være fremtidsrettet, i størst grad baseres på internasjonale standarder, og kunne bygges videre på.

Prosjektet jobber langs flere akser i samarbeid med mange aktører, blant annet de regionale helseforetakene (RHF), Direktoratet for e-helse og sykehusapotekene. Nasjonal IKT har opprettet prosjektet ‘SAFEST realisering’ som skal ivareta nødvendig kommunikasjon og forankring i RHF'ene, samt realisere gevinstene.

## Mål utvikling
- Profiler av resources
- Extensions
- Eksempler
- Implementasjonsguider med metafiler

## Publisering
Ferdige profiler publiseres også her: 
(Fremtidig Simplifier-repo)

## Vi benytter Feature branch workflow

![Feature branch workflow]
(https://git.sarepta.ehelse.no/utvikling/FHIR/raw/92dff80b4b825be384908a90a3abfa7d6a8d6a46/Feature-branch-workflow.JPG)

Vi baserer oss på at nye features utvikles i egne feature branches og merges inn i master branch etterhvert som de er klare. Arbeidsflyten er forklart i detalj her:
https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow

## Katalogstruktur

|\\[prosjektnavn]| | |
|---|---|---|
| |\\CodeSystem | CodeSystem definisjoner |
| |\\examples | eksempler |
| |\\REST-kall | Optional |
| |\\StructureDefinition | alle extensions og profiler |
| |\\ValueSet | ValueSet definisjoner |
| |\\ImplementationGuide-definition | Definisjonene for implementationguide |
| |\\ImplementationGuidePublish | Rendring av implementationguide for publisering på web |
| |[prosjektnavn]-[versjon].zip | Pakke med det ferdige resultatet for en versjon |

## Navngivning av filer
Inne i katalogene benytter vi navngivningsregler fra [SIMPLIFIER Best practices] (https://simplifier.net/guide/ProfilingAcademy/Best-practices)

**Filnavn for profiler og extensions:**  
safest-Medication.structuredefinition-profile.xml  
(...) 

**URL'ene i koden:**  
http://ehelse.no/fhir/StructureDefinition/safest-Flag-v05 (evt SLV)

## kontakt

Kommer
