# Minicase: Databehandling




## Om data:
Data komer ujevnt, og ulike planer fra ulike tidspunkt, kan sendes samtidig. "timeseries.json" består av tidsseriedata,  knyttet til slakteplaner for merder. Data er prognoser, på daglig oppløsning. For hver dag genereres nye prognoser.	Dette gir en rekke med glidende, og overlappende tidsserier. Totalvolumet på data i tidsserien er 3GB per dag.
"actions.json" beskriver handling tatt for en gruppe i en gitt merd. 

## Kravspekk:
Tidsserier skal til enhvertid vise siste plan, slik
Actions skal ha alle data historiske data, også eldre versjoner, men her skal det fremgå tydelig hvilken versjon data tilhører. 
Latenstiden på data, for sluttbruker, skal være på under 20 sekund.
Actions skal danne grunnlaget for en kompleks datamodell, hvor actions utgjør en av dimensjonene. For sluttbruker er det viktig at det alltid finnes en korresponderende rad i faktatabell, med data i dimensjonstabeller.


Gi en vurdering hvordan du ville imøtekommet kravspekkene.

