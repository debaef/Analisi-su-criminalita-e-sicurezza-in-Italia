## File Overview

Questo notebook sviluppa un’analisi quantitativa sulla **criminalità e sicurezza in Italia**, integrando più fonti ufficiali per costruire dataset coerenti e utilizzabili a fini analitici e previsionali.

Nel dettaglio:
- importiamo e puliamo i dataset su criminalità, popolazione residente totale e popolazione straniera
- normalizziamo le strutture dati (unpivot, aggregazioni per territorio e anno)
- escludiamo territori e indicatori non comparabili per garantire consistenza statistica
- costruiamo dataset finali a livello territoriale con shape ottimale per l’analisi
- calcoliamo trend storici e tassi di crescita (CAGR) su periodi selezionati
- generiamo **proiezioni 2024–2030** su:
  - numero detenuti italiani e stranieri
  - percezione del rischio di criminalità delle famiglie
- confrontiamo le stime con i dati reali 2019–2023 per verifica di coerenza
- unifichiamo dati storici e predittivi in dataset pronti per analisi comparative ed export

Il notebook è pensato come **base operativa** per analisi avanzate e supporto decisionale, con output già strutturati per reporting, visualizzazione e modelli futuri.
