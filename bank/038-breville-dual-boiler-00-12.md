---
title: Breville Dual Boiler BES920, ghidul codurilor 00–12
description: Dual Boiler BES920 își ascunde defectele în codurile 00–12 dintr-un meniu de autotest. Vezi ce înseamnă fiecare familie, cum citești jurnalul și ce repari.
---

La majoritatea aparatelor Breville defectele se anunță pe ecranul obișnuit: Barista Touch afișează coduri ER, Oracle scrie „Error", Oracle Jet folosește numere de tip E. **Dual Boiler BES920** o face altfel. Tabelul lui de defecte este un set de coduri cu două cifre, **de la 00 la 12**, ținute într-un meniu de autotest ascuns, nu pe afișajul de zi cu zi. Nu le vezi urmărind panoul frontal într-o zi normală — trebuie să știi combinația de butoane.

Numerotarea merită înțeleasă, pentru că tabelul este unul ordonat: blocul în care stă un cod îți spune natura defectului, iar în interiorul blocului codul numește piesa care semnalează problema.

## Citirea jurnalului de erori

Jurnalul se deschide din meniul de autotest:

1. Oprește aparatul de la priză.
2. Ține apăsat **EXIT** și **MANUAL** în timp ce redai alimentarea; apare meniul de autotest.
3. Apasă **MENU** până la poziția 3, jurnalul de erori. Poziția 4 arată starea nivelului din cazane, raportată ca LLL (scăzut) sau HHH (ridicat).
4. În jurnal, **MENU** parcurge codurile 00–12, fiecare cu un contor memorat.
5. La „ErSt", ține **MANUAL** apăsat până auzi bipul, ca să ștergi codurile memorate; contorul de cafele nu se resetează.

Contoarele contează la fel de mult ca și codurile. Un defect cu contorul 1, înregistrat anul trecut, e istorie; un defect al cărui contor crește săptămână de săptămână e o problemă vie, în formare.

## Ce acoperă familia 00

Codurile **00–05** formează blocul senzorilor de temperatură, aranjați în trei perechi. În fiecare pereche, numărul mai mic înseamnă că senzorul **nu este detectat** — placa îl citește ca circuit deschis — iar numărul mai mare înseamnă că senzorul citește ca **scurt-circuit**:

- **00 și 01** — senzorul de temperatură al cazanului de abur, nedetectat și apoi în scurt.
- **02 și 03** — senzorul de temperatură al cazanului de cafea, nedetectat și apoi în scurt.
- **04 și 05** — senzorul de temperatură al grupului încălzit, nedetectat și apoi în scurt.

BES920 are două cazane din oțel inoxidabil plus un grup încălzit electric, deci cei trei senzori acoperă cele trei zone încălzite ale aparatului. Pagina [codului 00](https://ro.codefixcoffee.com/breville/dual-boiler-bes920/00/) tratează senzorul cazanului de abur, dar sfatul practic se transferă tuturor celor șase: refă conexiunea și inspectează mufa sondei NTC înainte să cumperi piese și caută urme de umezeală, pentru că apa care pune punte peste un conector poate citi și ca circuit deschis, și ca scurt, în funcție de cum așază. Un ansamblu de sondă NTC original costă cam 25–90 €, după zona din care face parte; kiturile de garnituri o-ring, 10–20 €, sunt deseori adevăratul vinovat.

## Zona de abur versus zona de preparare

Restul tabelului se împarte pe aceeași linie hardware ca și perechile de senzori:

- **Cazanul de abur:** 06 (problemă cu pompa în timpul pornirii), 07 (nivel de apă sau pompă) și 11 (supraîncălzire detectată).
- **Cazanul de cafea — zona de preparare:** 08 (problemă de pompă sau de debit), 09 (defect de nivel de apă) și 10 (supraîncălzire detectată).
- **Grupul:** 12 (supraîncălzire detectată).

### Codurile care merg mână-n mână

Aceste defecte se condiționează reciproc, de aceea citirea întregului jurnal bate citirea unui singur cod. Codul 08 înseamnă că pompa a rulat, dar debitmetrul nu a văzut nimic trecând — cel mai des piatră pe paleta debitmetrului sau o pompă care zumzăie fără să mute apa, iar decalcificarea este prima mutare în ambele situații. Codul 11, supraîncălzirea cazanului de abur, urmează de obicei unui cazan care nu se mai alimentează cu apă — verifică dacă 07 sau 08 are și el contor — pentru că rezistența de încălzire continuă să încălzească un cazan aproape gol; a doua cauză este garnitura scursă a sondei de nivel. Înainte de orice comandă de piese, citește poziția 4 din meniul de autotest: un nivel care contrazice ce auzi când aparatul se umple îți arată pe ce parte se află defectul cu adevărat.

Codul 12, supraîncălzirea grupului, este capătul rar al tabelului și singurul la care recurența contează extrem de mult — o supraîncălzire care revine iar și iar indică o placă de alimentare care ține rezistența blocată pe pornit, nu o derivă de senzor. Pagina [codului 12](https://ro.codefixcoffee.com/breville/dual-boiler-bes920/12/) parcurge subiectul în detaliu.

## Cât costă piesele

- Soluție de decalcificare pentru codurile de debit și de nivel: aproximativ 10 €, și rezolvă o parte reală dintre ele.
- Pompa de umplere: 30–60 €.
- Sonda de nivel a cazanului de abur cu kit o-ring: aproximativ 85 €; kiturile de o-ring singure, 10–20 €.
- Siguranța termică: 10–20 € — dar află întâi de ce s-a ars.
- Triac sau placa de alimentare: 80–150 €.

O ofertă de service Breville în afara garanției pentru defecte interne pornește de regulă de la 300–500 € în sus, deci o pompă sau un senzor merită schimbate singure; o placă nouă pe un aparat vechi merită întâi o ofertă scrisă. Apa și tensiunea de rețea împart vârful cazanului, așa că scoate fișa înainte să atingi sondele; ghiduri practice de depanare găsești și pe [iFixit](https://www.ifixit.com). În Marea Britanie aparatul se vinde sub marca Sage, la [Sage Appliances](https://www.sageappliances.co.uk), iar cititorii cu această siglă pot folosi [secțiunea Breville](https://ro.codefixcoffee.com/breville/) — ideile de diagnostic coincid, numerotarea nu.

### Pentru utilizatorii din România

Breville nu are distribuție oficială și rețea de service în România, iar Dual Boiler ajunge la noi de obicei prin import din Marea Britanie sau din Statele Unite. Vestea bună este că modelele britanice lucrează la 230 V, exact ca rețeaua românească, deci ai nevoie doar de un adaptor la priză sau de un ștecher schimbat, nu de transformator. Păstrează dovada achiziției și corespondența cu vânzătorul: garanția se tratează prin magazinul de la care ai cumpărat, iar intervențiile în țară se fac de regulă într-un atelier independent de reparat espressoare.
