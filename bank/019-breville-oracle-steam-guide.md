---
title: Breville/Sage Oracle: abur și coduri ER — ce verifici mai întâi
description: Defecțiuni de abur la Breville/Sage Oracle: ce spun codurile de abur, rutina de purjare de încercat prima și când vinovatul e calcarul.
---

Circuitul de abur este cel mai aglomerat loc dintr-un Breville Oracle: un cazan de abur din inox, o baghetă cu texturare automată, sonde de nivel și o pompă de umplere, toate la temperatură zi de zi. Tot aici se nasc o mare parte din codurile aparatului. Familia Oracle rulează un tabel de service cu 32 de intrări pe care Breville nu îl publică, iar în Marea Britanie același hardware poartă insigna **Sage** — codurile sunt identice. Înainte să tragi concluzia că s-a ars o piesă, treci mai întâi prin verificările ieftine: majoritatea opririlor pe partea de abur sunt un vârf de baghetă înfundat, o purjare care nu s-a făcut sau calcar pe o sondă. Structura completă a tabelului o parcurgem în [secțiunea Breville/Sage](https://ro.codefixcoffee.com/breville/).

## Unde stau codurile de abur în tabelul Oracle

Oracle (BES980) și Oracle Touch (BES990) împart același tabel; BES980 afișează „Error 1”–„Error 32”, iar BES990 prefixează ER. Intrările legate de abur se adună în cinci zone:

- **Error 1–4** — senzorul de temperatură al cazanului de abur, în tot ciclul său: circuit deschis la pornire, semnal pierdut în funcționare și scurtcircuit în ambele situații. Un singur senzor, patru moduri de a-l raporta.
- **Error 13–16** — același cvartet pentru senzorul de temperatură al baghetei de abur, sonda care oprește texturarea când laptele atinge temperatura potrivită. Trăiește în cel mai umed loc din aparat.
- **Error 18** — cazanul de abur nu se încălzește normal.
- **Error 20 și 21** — nivelul apei din cazanul de abur sau probleme la pompa de umplere, plus o citire a sondei de nivel care nu se potrivește cu așteptarea plăcii.
- **Error 26** — cazanul de abur s-a supraîncălzit peste țintă; **Error 32** — scurgere la cazanul de abur sau eșec al reumplerii.

Nu tot ce se întâmplă lângă baghetă ține de abur: codurile 5–8 aparțin senzorului cazanului de cafea, [Error 8](https://ro.codefixcoffee.com/breville/oracle-bes980/error-8/) fiind intrarea cu scurtcircuit în funcționare. Jurnalul stocat te ajută să desparți familiile — pe BES980, ține 1 CUP, 2 CUP și POWER simultan, cu aparatul oprit, ca să deschizi Error Storage și să parcurgi toate cele 32 de coduri împreună cu numărătorile lor.

## Verificarea numărul unu: rutina de purjare

Abur slab sau care țâșnește în rafale, ori un cod venit exact după o băutură cu lapte, arată de obicei spre vârful baghetei, nu spre cazan:

1. Deconectează aparatul și lasă bagheta să se răcească.
2. Deșurubează vârful de abur și lasă-l la înmuiat în apă fierbinte cu puțin decalcificant; curăță fiecare orificiu cu acul de pe unealta de curățare.
3. Rulează purjarea — cam zece secunde de abur în tava de scurgere, întâi cu vârful scos, apoi cu el montat.
4. De acum înainte, purjează bagheta după fiecare sesiune de lapte: laptele uscat în vârf declanșează majoritatea acestor opriri.

Dacă aparatul monitorizează presiunea aburului, cum face Oracle Jet prin codul E16, un vârf crustat poate sări codul înainte să observi măcar că aburul a slăbit.

## Duritatea apei, calcarul și sondele de nivel

Unde apa este dură, calcarul își scrie singur codurile de eroare. Sondele de nivel ale cazanului de abur stau permanent în apă fierbinte, iar stratul calcaros le izolează, așa încât placa citește „fără apă” chiar și cu cazanul plin — acesta este traseul clasic spre Error 20 sau 21 și spre eșecul de reumplere de la Error 32. Depuneri se acumulează și pe traseul baghetei și la admisia pompei de umplere. O decalcificare completă, cu ciclul cazanului de abur inclus, este cel mai ieftin diagnostic pe care îl poți rula și șterge singură o parte surprinzător de mare din aceste coduri.

Aceeași poveste o confirmă și fratele din gamă: Dual Boiler își ține codurile 00–12 ascunse într-un meniu de autoverificare, iar [codul 00](https://ro.codefixcoffee.com/breville/dual-boiler-bes920/00/) — senzorul cazanului de abur nedetectat — stă în fruntea unui tabel ale cărui intrări de nivel și de umplere reacționează identic la apa dură.

## Când decalcifici și când demontezi

Întâi decalcificarea, apoi șurubelnița — dar cu limitele bine stabilite:

- **Decalcifică primul** la codurile de nivel, sondă și reumplere (20, 21, 32), la abur slab fără niciun cod și la orice aparat cu peste trei luni de la ultimul ciclu. Costul: o sticlă de decalcificant.
- **Decalcificarea nu rezolvă** un cod de senzor care revine imediat pe un aparat proaspăt decalcificat și cald — fie o intrare din 1–4 pe partea de abur, fie [Error 8](https://ro.codefixcoffee.com/breville/oracle-bes980/error-8/) pe partea de cafea. Un cod care supraviețuiește decalcificării arată spre senzor, spre cablul lui sau spre un conector.
- **Oprește-te și verifică garniturile** dacă Error 26 se repetă: o garnitură o-ring a sondei de abur care pierde lasă aburul să încălzească cablajul senzorului și mimează un cazan care o ia razna. O-ring-urile noi pentru sondă sunt ieftine; o placă triac care nu mai întrerupe încălzitorul, nu.
- **Error 18** pe un aparat care nu mai face deloc abur ține de obicei de partea de încălzire — siguranță termică, rezistență de încălzire sau placă — nu de calcar, deci tratează-l ca reparație, nu ca curățenie.

### Sfat practic pentru România

Duritatea apei diferă mult de la o zonă la alta a țării, iar majoritatea furnizorilor publică buletinele anuale de calitate a apei — câteva minute de căutare îți spun în ce categorie ești. La apă mediu-dură sau dură, scurtează intervalul dintre decalcificări față de recomandarea generică din manual sau folosește apă filtrată la cazanul de abur. Rutina de purjare a baghetei rămâne obligatorie indiferent de apa din rețea.

## Cât costă piesele

Ansamblurile originale de senzori de temperatură pleacă de la 25 € și urcă până la 95 €, în funcție de senzor; baghetele complete de abur, cu senzor cu tot, se situează în jurul a 60–95 €; un kit de sondă cu o-ring-uri costă cam 85 €, iar o pompă de umplere 30–60 €. Față de aceste cifre, ofertele producătorului în afara garanției pentru defecte interne pornesc de regulă de la 300 € și ajung la 500 €, deci aritmetica aproape mereu câștigă: întâi sticla de decalcificant, apoi remedierea la nivel de senzor. Pentru îngrijirea curentă a baghetei și a cănii de lapte, [ghidurile oficiale Sage](https://www.sageappliances.co.uk) sunt referința potrivită.
