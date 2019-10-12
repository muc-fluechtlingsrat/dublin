# dublin

Analying data from the Dublin Procedure

## Background

Articles:

https://www.bpb.de/nachschlagen/lexika/270360/dublin-verfahren

https://www.proasyl.de/news/der-dublin-irrsinn-nullsummenspiel-mit-gigantischem-buerokratie-aufwand/
https://www.asylumineurope.org/sites/default/files/report-download/aida_de_2018update.pdf

court stops deportation to italy
https://www.dw.com/de/gericht-stoppt-abschiebung-nach-italien/a-16096899-0


## Data Source: Eurostat

`migr_dub`: 
https://ec.europa.eu/eurostat/cache/metadata/de/migr_dub_esms.htm

Incoming Requests:
data periodicity is annual
 Ankommende 'Dublin' Übernahmeersuchen nach ersuchendem Mitgliedstaat (PARTNER), Art des Übernahmeersuchens und Rechtsvorschriften [migr_dubri]

Outgoing Requests:
 Ausgehende 'Dublin' Übernahmeersuchen nach Aufnahmemitgliedstaat (PARTNER), Art des Übernahmeersuchens und Rechtsvorschriften [migr_dubro]
https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=migr_dubro&lang=de

We skip the decisions

Incoming Transfers:
 Ankommende Überstellungen nach ersuchendem Mitgliedstaat (PARTNER), Rechtsvorschriften und zeitlicher Nutzung [migr_dubti]

Outgoing Transfers:
 Ausgehende Überstellungen nach Aufnahmemitgliedstaat (PARTNER), Rechtsvorschriften und zeitlicher Nutzung [migr_dubto]

## Dimensions

We only look at Germany (DE) for now

* per year in 2009, ... , 2018
* per partner country ('IT', 'FR', .. , and 'TOTAL')
* incoming requests, outgoing requests, incoming transfers, outgoing transfers

## Sanity Checks

with proasyl article

## TODO
Read up on Reasons, Art 12, 14 etc (in AIDA pdf)
Discuss with supporters
