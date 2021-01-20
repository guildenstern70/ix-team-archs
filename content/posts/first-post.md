---
title: "Considerazioni di fine 2020"
author: "Alessio Saltarin"
date: 2020-12-30T16:49:56+01:00
draft: false
---
Archs,
condivido con voi le impressioni che ho avuto quest’anno sulle tecnologie, sperando di farvi venire qualche curiosità, 
in ottica 2021. Tutto quanto segue è farina del mio sacco e può essere un errore o un abbaglio.
In grande evidenza: l’anno prossimo e i prossimi a venire saranno sotto l’egida del *Cloud Native*.

Cloud Native vuol dire: che si compila in immagine Docker. Perciò saranno in grande rilievo i framework che 
offrono questa modalità. Tra tutti quello che mi piace di più è Quarkus, che tra l’altro compila in nativo 
Linux su Docker usando GraalVM. SpringBoot rimarrà comunque la scelta più matura e più esente da sorprese.
Come piattaforme Cloud, oltre ovviamente all’onnipresente Kubernetes, mi piace molto l’IBM Cloud Code Engine, 
forse l’erede naturale di Cloud Foundry: uscirà dalla beta nel 1Q 2021. 

OpenShift, secondo me, può avere un futuro di rilievo solamente se IBM saprà imporlo come impose a suo tempo Websphere.
Sarà ancora un anno JavaScript - vanilla oppure transpilato da TypeScript. Faremo molti client stateless usando il JAMStack. Lo stato verrà mantenuto da layer di API scritte sui framework Cloud Native di cui sopra, OpenAPI compliant e orchestrate con GraphQL. Ovviamente useremo React e ancillari: Next, Nuxt e Gatsby su tutti. Angular mi sembra un po’ in ombra, ma sarà comunque una scelta vincente, con Vue.js anche. Quest’anno probabilmente abbondeneremo JQuery (come ha fatto Boostrap) per sostituirlo con Vanilla JavaScript e Babel.
Dal punto di vista delle UI, l’uscita di Bootstrap 5 lo mette un gradino sopra gli altri ancora una volta. 
Sempre ottimo anche Semantic UI. Un po’ in declino, ma valido, Foundation. Mi piace molto anche Pure.css. Oppure CSS e basta.

E voi? Che ne pensate? Mi sono dimenticato qualcosa? Auguri di buon tech 2021.

