Dataracing 2022 - Exportteljesítmény Előrejelzési Verseny
Leírás
A Dataracing 2022 verseny célja, hogy a résztvevők adatokat elemezzenek különféle data science eszközökkel, és gépi tanulási modelleket építsenek a hazai vállalatok exportteljesítményének előrejelzésére. Az adatokat a Magyar Nemzeti Bank (MNB) biztosította. A verseny központi kérdése az, hogy mennyire pontosan lehet előre jelezni az egyes vállalatok következő évi exportból származó bevételét múltbeli adatok alapján.

Feladat
A feladatod, hogy a megadott adathalmaz segítségével gépi tanulási modelleket építs, amelyek előre jelzik az "target_reg" célváltozó (a 2017-es exportérték, ezer forintban) értékét. Az előrejelzéseket a modellek pontosságát a Mean Absolute Error (MAE) metrika segítségével mérjük.

Adathalmaz
Az adathalmaz a 2014-2016 közötti időszakra vonatkozóan tartalmazza több mint 30 ezer hazai vállalat különféle adatát, például:

Székhely
Létszám
Árbevétel
Egyéb statisztikai mutatók
Az adathalmazban előfordulhatnak hiányzó értékek, ezek kezelése a versenyzőre van bízva.

Adatok elérhetősége:

Adatok: train.csv
Célváltozó és Metrika
Célváltozó: target_reg (2017-es exportérték ezer forintban)
Metrika: Mean Absolute Error (MAE)

Adatok Felosztása:

Az adatok felosztása a következő módon történik:
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.4, random_state=42)
A MAE értékét az X_test adatokon mérjük!

Kérdések és Célok
A verseny során a következő kérdésekre keresünk választ:

Mennyire jelezhető előre az egyes cégek üzleti teljesítménye?
Milyen szinten lehet becsülni a múltbeli adatok alapján a várható export értékét?
Milyen elemzési trükkök vethetők be egy ilyen adathalmaz esetén?
Mely algoritmusok a legalkalmasabbak az adott esetben?
