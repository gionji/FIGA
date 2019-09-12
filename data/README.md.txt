# Descrizione paths

I file sono campionati a 10 Hz attraverso l'app android torque

Vengolo loggati i seguenti parametri

* Engine RPM
* Engine Load
* Speed (ODB)
* Throttle Position(mainfold)
* Kilometers per litre(instant)
* Mass air flow rate - inutile, sulla civic non lo legge

i file cvs hanno la prima riga con le intestazioni ma vanno rimossi tutti gli spazi e mantenute tutte le parentesi

## formato nomi

I nomi dei file sono cosi composti

[nomeVeicolo]-YYMMDD_[luogoPartenza]-([luogo])-[luogoFine]

i luoghi intermedi si inseriscono solo se servono per identificare il percoso