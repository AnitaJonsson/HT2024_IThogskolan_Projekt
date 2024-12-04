# HT2024_IThogskolan_Projekt
Inlämningsprojekt IT-Högskolan

SYFTE
Förutse framtida antal invånare i Sveriges kommuner.

För kommunerna i Sverige finns ett konstant behov av att övervaka och förutse anatalet kommuninvånare. Dels för kommunens intäkter (skatteintäkter) är beroende av hur antalet invånare men även för att välfärdstjänsterna som kommunerna förväntas tillhandahålla (skola, barnomsorg, vatten mm) behöver anpassas beroende på antalet invånare.

TILLVÄGAGÅNGSSÄTT
Jag tänkter med regressionsanalys förutse framtida antal invånare. Etikett (det önskade utfallet) är folkmängd 2023 och jag kommer att använda folkmängd 2018 att träna på.

Exempel på variabler:
Medelålder
Antal personer per hushåll,Antal hushåll
Antal invånare fem år tidigare
Antal invånare över 65
Nybyggande, huspriser, bostadsindex
Födda
Döda
Inflyttade
Utflyttade

Om det finns utrymme hoppas jag även kunna göra en klassificering av kommunerna som jag sedan anger som variabel i regressionen.
Exempel på variabler för en klassificering:
Ökaning resp minskning historisk av antal invånare.
Antal invånare
Nybyggande, huspriser, bostadsindex
Befolkningstätet

DATA
SCB tillhandahåller en stor del data. Datan är oftast komplett, inga null-värden, och samma enheter och konsekventa koder för kommmunerna. Viss data finns bara på tex länsnivå och där behöver jag finna ett sätt att koppla kommun till län. Det finns noteringeringa att enheter (geografiska enheter) har förändrats från ett år till ett annat och där behöver jag granska om det har stor påverkan och eventuellt kanske ta bort dessa ur urvalet.

20241204 - Kommentar
Har skapat två modeller och en klassificerings-modell i Jupitur. Har lagt till alla csv-file som behös eller skapas av modellerna. För mer detaljer runt projektet läs Projektbeksrivning.jpunb.
