---
title: Codurile ER Sage/Breville: tabelul de service ascuns
description: Codurile ER de la Sage/Breville provin dintr-un tabel de service nepublicat. Cum funcționează ER01–ER18 și de ce numerotarea Oracle diferă.
---

Un espressor Breville care se oprește brusc și afișează ER05 nu va primi explicația din manual. Nu este o omisiune: codurile Breville vin din tabelele interne de service folosite pentru reparații și nepublicate pentru proprietari. Același hardware se vinde în Europa sub marca **Sage** — aparate identice, doar insigna diferă — așa că un cod ER pe un Sage Barista Touch înseamnă exact ce înseamnă pe un Breville. [Secțiunea noastră Breville/Sage](https://ro.codefixcoffee.com/breville/) acoperă gama curentă, iar acest articol îți arată cum e construită numerotarea, ca un cod pe care nu l-ai mai văzut să-ți spună oricum ceva util.

## De ce Breville nu le face publice

Manualul utilizatorului tratează curățarea și decalcificarea, nu diagnosticul. Tabelele complete stau în spatele modului de service al fiecărei mașini: ecrane protejate cu parolă, destinate tehnicienilor, cu contoare de erori stocate și citiri live de senzori. Pentru că sunt unealtă de reparat, nu o funcție pentru consumator, Breville nu le-a emis niciodată într-un document public, iar majoritatea proprietarilor văd, practic, un singur cod: cel care a provocat oprirea. Contrastul cu Miele este frapant, pentru că Miele își tipărește sensul codurilor F în chiar instrucțiunile de utilizare — motiv pentru care [paginile noastre de coduri Miele](https://ro.codefixcoffee.com/miele/) pot cita manualul direct.

## Tabelul Barista Touch: ER01 până la ER18

Barista Touch (BES880) și Barista Touch Impress (BES881) — aceeași familie de plăci de comandă, același tabel — folosesc 18 intrări. Structura se citește ușor odată ce o observi: codurile de senzori vin în **grupuri de câte patru**, un grup per senzor, parcurgând circuit deschis la pornire, circuit deschis în funcționare, scurtcircuit la pornire și scurtcircuit în funcționare.

- **ER01–ER04** — senzorul de temperatură al încălzitorului ThermoJet, în cele patru variante deschis/scurtcircuit. [ER01](https://ro.codefixcoffee.com/breville/barista-touch-bes880/er01/) este intrarea cu circuit deschis la pornire.
- **ER05–ER08** — senzorul de temperatură al cănii de lapte, mica sondă din zona tăvii de scurgere care citește recipientul în timp ce bagheta de abur texturizează laptele. ER05, circuitul deschis la pornire, este cel mai des raportat cod de Barista Touch, iar toate cele patru intrări duc la un singur remediu.
- **ER09–ER12** — senzorul de temperatură în linie (al apei de preparare), după același tipar în patru.
- **ER13 și ER14** — erori de contorizare ale debitmetrului, la pornire și în funcționare: pompa a lucrat, dar mașina nu a putut număra apa care trecea prin ea.
- **ER15** — defect de comunicare între modulele electronice interne; adesea un cablu plat desfăcut sau un conector umezit, nu neapărat o placă moartă.
- **ER16 și ER17** — râșnița: motorul s-a suprasolicitat termic și s-a oprit în protecție, apoi a intrat în depășire de timp fără să-și termine sarcina.
- **ER18** — protecția E-fast, un defect electric sau de siguranță, de exemplu curent de scurgere; este codul care poate cădea și întrerupătorul diferențial al prizei.

## Familia Oracle numerotează altfel

Cumperi un Oracle și aceeași idee primește un tabel mai lung. Oracle (BES980) și Oracle Touch (BES990) împart o listă de 32 de intrări, doar că BES980 le afișează ca „Error 1”–„Error 32”, în timp ce BES990 le prefixează cu ER. Primele șaisprezece urmează logica cvartetelor pe patru senzori: cazanul de abur ocupă 1–4, cazanul de cafea 5–8 ([Error 8](https://ro.codefixcoffee.com/breville/oracle-bes980/error-8/) marchează scurtcircuitul senzorului cazanului de cafea în funcționare), grupul încăzit 9–12, iar bagheta de abur 13–16. Restul tabelului: cazane care nu mai încălzesc (17–19), nivel și umplere la cazanul de abur (20 și 21), probleme de debitmetru (22 și 23), sonde de nivel și supraîncălzire (24–27), un defect de comunicare al plăcii la 28, râșnița la 29 și 30, motorul de tasare la 31 și o scurgere sau o reumplere eșuată la cazanul de abur la 32.

Două tabele mai mici încheie familia: Oracle Jet (BES985) rulează un tabel propriu, E1–E19, iar Dual Boiler (BES920) își păstrează codurile cu două cifre, 00–12, ascunse într-un meniu de autoverificare — așa că un Dual Boiler poate sta pe un defect pe care nu l-ai văzut niciodată pe ecran.

### Sfat practic pentru România

Aparatele Sage luate din distribuția europeană vin cu fișă Schuko și alimentație 230 V, deci se folosesc direct. Unitățile Breville aduse din Marea Britanie au mufă BS 1363 — tensiunea este aceeași, 230 V, dar pentru folosință îndelungată e mai sigură înlocuirea mufei printr-un electrician decât un adaptor permanent; verifică, înainte de cumpărare, dacă un astfel de import mai are garanție valabilă în România, pentru că multe nu au.

## Cum citești singur jurnalul de erori

Fiind date de service, istoricul mașinii se citește tot prin ecranele de service. Traseele au un aer de atelier, dar sunt bine documentate de reparatori — iar dacă ajungi să deschizi carcasa, [ghidurile de dezasamblare iFixit](https://www.ifixit.com) sunt un punct de plecare solid:

- **Barista Touch și Oracle Touch** — oprește aparatul la priză, ține butonul Power din față apăsat în timp ce reintroduci curentul, eliberează când apare logo-ul, tastează parola de service 00000, apoi deschide Error Counter pentru erorile stocate sau Live Debug pentru temperaturi și niveluri în timp real.
- **Barista Touch Impress** — aceeași secvență de butoane, dar parola de service este 02015.
- **Oracle BES980** — cu aparatul în priză, dar oprit, ține 1 CUP, 2 CUP și POWER împreună cel puțin o secundă; după bipul lung, apasă selectorul SELECT ca să deschidă Error Storage și parcurge erorile 1–32 împreună cu contoarele stocate.

Tratează aceste ecrane ca fiind doar-citire: notează ce e stocat, lasă setările în pace și golește jurnalul abia după o reparație, ca să observi dacă vreun cod revine.

## Ce costă, de regulă, reparațiile

Chiar și contra unui tabel nepublicat, economia este previzibilă. Ansamblurile de senzori de temperatură pleacă de la circa 25 € și urcă la 95 € în funcție de senzor — cele pentru bagheta de abur și pentru cana de lapte sunt scumpele — trusele de o-ring-uri costă 10–20 €, iar un kit de reparare pentru senzorul de lapte ia 30–50 € față de 80–95 € cât costă ansamblul original. Ofertele producătorului în afara garanției pentru defecte interne se mișcă de obicei între 300 și 500 €, deci remedierea la nivel de senzor, la un service independent, iese aproape mereu mai bine. Pentru întreținerea de rutină, [asistența oficială Sage Appliances](https://www.sageappliances.co.uk) rămâne sursa de referință — deși nici acolo nu vei găsi tabelele de coduri, fiindcă acelea există doar în service.
