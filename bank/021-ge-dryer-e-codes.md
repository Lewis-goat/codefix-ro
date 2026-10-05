---
title: Coduri E la uscătoarele GE — termistoare, siguranțe termice și tahogenerator
description: Codurile E1, E3-E6, E4, E8 și E11 la uscătoarele GE — întrerupător de ușă, termistoare, siguranță termică și tahogenerator, cu prețuri și capcane.
---

Dintre marii producători de electrocasnice, GE e unul dintre puținii care nu are o pagină oficială de coduri de eroare pentru uscătoare. Codurile există, placa de comandă le memorează, dar nimeni nu le explică proprietarilor. Vestea bună e că schema se poate învăța: erorile uscătoarelor GE se adună în patru zone mari — circuitul ușii, cele două sonde de temperatură, siguranțele termice de protecție și motorul de antrenare cu tahogeneratorul lui. Fiecare cod e tratat pe larg în [secțiunea de uscătoare GE](https://ro.codefixcoffee.com/ge/dryer/); articolul de față arată cum se leagă familia între ea și unde sunt capcanele în funcție de generație. Pentru manuale și scheme, punctul de plecare rămâne [suportul GE Appliances](https://www.geappliances.com/support/).

## Citește mai întâi codul salvat

Pe uscătoarele GTD și GFD din 2016 încoace poți scoate singur ultima eroare memorată. Cu aparatul oprit, ține apăsite împreună butoanele **Signal** și **Temp** cinci secunde ca să intri în modul de service; cel mai recent defect apare pe afișaj. Pe modelele compatibile SmartHQ, aplicația listează codurile stocate. Dacă vrei doar să golești memoria plăcii, deconectează uscătorul de la priză cinci minute.

## E1: întrerupătorul ușii

[E1](https://ro.codefixcoffee.com/ge/dryer/e1/) înseamnă că placa nu percepe ușa ca închisă. Defectul e mai degrabă mecanic decât electronic: un cârlig uzat, o lamă îndoită sau un microîntrerupător care nu mai face „clic".

- Închide ferm ușa și apasă Start — o ușă prinsă pe jumătate e cauza numărul unu.
- Verifică pe ușă zăvorul (strike-ul): o lamă îndoită sau ruptă ține contactul deschis.
- Deconectează uscătorul, scoate panoul frontal și controlează mufa întrerupătorului de ușă; un buton care nu mai clică la apăsare se înlocuiește, iar piesa costă cam 10-25 €.

## E3 până la E6: termistoarele

Uscătoarele GE măsoară temperatura aerului cu două termistoare — sonda de intrare, pe carcasa rezistenței de încălzire, și cea de ieșire, pe carcasa ventilatorului. [Familia E3-E6](https://ro.codefixcoffee.com/ge/dryer/e3-to-e6/) sare când unul dintre ele raportează circuit deschis sau scurtcircuit. Firele slăbite ori corodate produc tot atâtea erori cât sondele arse, iar un traseu de evacuare blocat poate supraîncălzi un uscător perfect sănătos până la declanșare.

1. Deconectează aparatul 30 de secunde, apoi repornește.
2. Curăță filtrul de scame și verifică să nu fie împănat traseul de evacuare.
3. Deschide carcasa și controlează mufele termistoarelor și harnasamentul, căutând contacte slăbite sau corodate.
4. Măsoară termistorul cu multimetrul: în jur de 10 kΩ la temperatura camerei e valoare bună, deci unul care citește circuit deschis se înlocuiește.

Un termistor nou costă 10-25 €. Un detaliu de reținut: pe unele modele E6 e de fapt cod de restricție a aerului, nu de termistor, așa că confirmă semnificația pentru modelul tău înainte de a comanda piese.

## E4: siguranța termică

[E4](https://ro.codefixcoffee.com/ge/dryer/e4/) e codul „fără căldură": tamburul se învârte, dar rufa rămâne udă, pentru că o siguranță termică (termofuzibilul) s-a întrerupt. Astfel de siguranțe nu cedează fără motiv — scamele și un evacuare blocată lasă rezistența de încălzire să se supraîncălzească. Rezolvă întâi circulația aerului, altfel cedează și siguranța nouă; și niciodată nu o pune în scurtcircuit, fiindcă ea e piesa care oprește o supraîncălzire reală înainte să devină incendiu.

1. Curăță filtrul de scame și tot traseul de evacuare până la exterior.
2. Măsoară siguranța termică și termostatul de limită de pe carcasa rezistenței; înlocuiește oricare dintre ele care citește circuit deschis.
3. Rulează un ciclu scurt cu evacuarea decuplată provizoriu, ca să confirmi revenirea căldurii, apoi reconectează.

Siguranța în sine costă 5-15 €, iar termostatul de limită 10-25 €.

## E8 și E11: tahogeneratorul și motorul

[E8](https://ro.codefixcoffee.com/ge/dryer/e8/) e codul tahogeneratorului pe uscătoarele GE actuale: placa a alimentat motorul, dar semnalul de turație nu s-a mai întors. Firele tahometrului pot fi slăbite, tamburul poate fi blocat — o curea sărită sau un obiect prins în spatele ei — ori tahogeneratorul ori motorul au cedat. Fiindcă tahometrul face corp comun cu motorul, un defect confirmat duce la motor nou: 80-150 €; cureaua costă 15-25 €.

E11 stă alături: motorul nu execută ce cere placa — curea uzată, rolă de tambur blocată, întrerupătorul de pornire al motorului sau motorul însuși. Învârte tamburul cu mâna mai întâi: un mers greu indică rolele sau rulmenții, nu motorul. Un motor care bâzâie fără să pornească, cu cureaua scoasă, cere înlocuire; un set de role costă 20-40 €.

## Diferențele între generații

Trei capcane merită reținute. Prima: același număr nu înseamnă mereu aceeași pană — pe unele modele vechi și pe aparatele combinate, E8 semnalează lampa tamburului sau drenajul, nu tahogeneratorul, deci identifică exact uscătorul înainte de a cumpăra piese. A doua: E6 înseamnă restricție de aer pe unele modele și defect de termistor pe altele. A treia: modul de service Signal și Temp descris mai sus se aplică la GTD/GFD din 2016 încoace; pe modelele mai vechi te raportezi la ce afișează aparatul în chiar momentul defectului. În familie mai intră E7 — o problemă de alimentare, când uscătorul nu mai „vede" ambele linii ale rețelei — și E14, o tastă blocată pe panoul de comandă; niciuna nu ține de căldură.

### Sfat pentru utilizatorii din România

Uscătoarele GE ajung la noi aproape exclusiv prin import din SUA și sunt construite pentru rețeaua de 120 V/60 Hz, deci depind de un transformator corect dimensionat. Un transformator subdimensionat produce căderi de tensiune exact la pornirea motorului — scenariul care poate mima o eroare de alimentare precum E7. Fiindcă service-ul autorizat GE lipsește practic din România, citirea codului direct din modul de service valorează cu atât mai mult înainte de a apela un service local.

## Cât costă reparațiile

Intervențiile la nivel de sondă și întrerupător sunt ieftine: întrerupătoare de ușă 10-25 €, termistoare 10-25 €, siguranțe termice 5-15 €, curele 15-25 €, role de tambur 20-40 €. Piesa grea e motorul de antrenare, la 80-150 € — pe un uscător vechi, suma asta e o decizie de raport cost-beneficiu, nu un da automat. O vizită de diagnostic la domiciliu pornește de la cam 120-250 € plus piesa și se justifică pentru circuitele de motor dacă nu vrei să deschizi carcasa.
