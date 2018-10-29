## Elfu Vienības uzturētie resursu saraksti

Šo sarakstu uzdevums ir informēt un padarīt plašākai publikai viegli pieejamu informāciju (un klasifikāciju) attiecībā uz identificētiem resursiem Internetā, kuros tiek izplatītas viltus ziņas, Kremļa naratīvi, naidu kurinoši teksti vai maldinoša informācija (dezorientēšana un veselā saprāta pārmākšana ar mistiku, sazvērestības teorijām, ezotēriku u.tml.).
Sarakstos pieejami arī tādi resursi, kuri šobrīd vairs nav pieejami.


### Klasifikācija
* VZ - viltus ziņas
* KN - Kremļa naratīvi
* NK - naida kurināšana
* M - miglošana (dezorientēšana un veselā saprāta pārmākšana ar mistiku, sazvērestības teorijām, ezotēriku u.tml.)


### Pieejamie saraksti
* __sites.csv__ - vietņu saraksts, kurā iekļautas tādas mājaslapas, kurās visa pieejamā informācija ir uzskatāma par apšaubāmu; šajā sarakstā iekļauto domēnvārdu apakšdomēni arī uzskatāmi par maldinošiem (skat. klasifikāciju)
* __facebook.csv__, __draugiem-lv.csv__, __twitter.csv__  - Attiecīgajā sociālajā tīklā vidē eksistējoši profili, grupas vai lapas, kurās novēroti sistemātiski centieni radīt vai uzturēt informāciju, kas atbilst augstākminētajai klasifikācijai
* __articles.csv__ - saraksts, kurā apkopti atsevišķi raksti - gadījumos, kad konkrētā vietne (vēl) nav iekļauta `sites.csv` sarakstā vai arī gadījumos, kad plaši pazīstamā vietnē ir publicēti atsevišķi apšaubāmi raksti


#### Turpmākie plāni
1. Pilnveidot sarakstus
2. Izveidot Interneta vietni, kurā būtu pieejama plašāka informācija par sarakstos iekļautajām lapām (wiki analogs)
3. Izveidot Interneta pārluku spraudņus, kas spētu lietotājus brīdināt, kad tiek atvērts kāds no sarakstos iekļautajiem resursiem (līdzīgi [bs-detector](https://github.com/bs-detector/bs-detector))


#### Tehniska atkāpe
1. Saraksti tiks uzturēti kā CSV faili, kuros ir iespējams viegli izmantot daudzās vidēs/programmās.
2. Pirmo divu kolonu nosaukumi mainīti netiks, bet atlikušo divu kolonu (R1,R2) mērķis tiks precizēts; šobrīd nav paredzēts, ka kolonu skaits failos varētu mainīties.
3. Gadījumos, kad sarakstā ir pieejamas vietnes vai raksti, "https://", "http://" un "www." netiek URL kolonnā iekļauts apzināti. Šiem sarakstiem var pievienot arī apakšdomēnus - kamēr vien nav gūts apstiprinājums, ka domēnvārds kopumā ir apšaubāms.
4. Gadījumos, kad sarakstā apkopoti sociālo tīklu profili, sociālā tīkla domēnvārds netiek iekļauts un sarakstā iekļautā relatīvā adrese ir sasniedzama, tai sākumā pievienojot sociālā tīkla domēnvārdu. Piemēram, ja sarakstā ir iekļauts "SivēnsSivēnamDraugs", tad konkrētais profils/lapa/grupa Facebook sociālajā tīklā ir pieejams https://www.facebook.com/SivēnsSivēnamDraugs
