# Bevezetés
**Egyetemi kurzusaim során tanult készségeim gyakorlása, illetve tovább fejlesztése céljából készítettem az alábbi projekteket.**
# [Power BI Projekt](https://github.com/rfanni324/power-bi-project)
### Az adatokól: 
Az adatokat egyetemi tanárom adta. Az adatbázis tisztítást excel power pivot-ban végeztem. Itt számoltam a KPI-okat és egyeb adatokat is, de volt amivel ki kellett egészítenem Power BI-ban.
![](./assets/gso_bi.jpg)
# Data Analysis Projektek
### *Jupyter Notebook használatával*
## [Újrahasznosítható energia](https://github.com/rfanni324/energy-p1)
### Az adatokól: 
- az adatok [kaggle-ről](https://www.kaggle.com/datasets/anishvijay/global-renewable-energy-and-indicators-dataset/data) vannak
- 56 oszlop és 2500 sor
1. **Cél megahatározása:**
- Fraanciaország és Németország összehasonlítása szél és nap energiához kapcsolódó adatok alapján
2. **Adatok tisztítása és előkészítése:**
- adat típusok ellenőrzése
- adatbázis leszűkítése
- felesleges oszlopok törlése
- duplikált és null értékrk ellenörzése/eltávolítása
- indexek visszaállítása
- oszlopok átnevezése
3. **Adatok feltárása és elemzése:**
- vizualizációk készítése: diagramok, grafikonok
- leíró statisztikák: max, min, átlag
![](./assets/g_f_wind_solar.jpg)
## [Fizetések](https://github.com/rfanni324/salaries-p2)
### Az adatokól: 
- az adatokat egyetemi tanárom adta.
- 13 oszlop 148654 sor
- oszlopok: Id(int64), EmployeeName(object), JobTitle(object), BasePay(float64), OvertimePay(float64), OtherPay(float64), Benefits(float64), TotalPay(float64), TotalPayBenefits(float64), Year(int64), Notes(float64), Agency(object), Status(float64)
### Munkamenet:
1. **Cél megahatározása:**
*2013 és 2014 -ben:*
- legmagasabb és legalacsonyabb össz fizetéssek rendelkező dolgozók meghatározása
- legmagasabb össz fizetéssel, alapérrel, túlóra kompenzációval rendelkező munkakörök meghatározása
- dolgozók legmagasabb összeadott fizetése, alapére és túlóra kompenzációja munkakörök szerint
2. **Adatok tisztítása és előkészítése:**
- adat típusok ellenőrzése
- adatbázis leszűkítése
- felesleges oszlopok törlése
- duplikált és null értékrk ellenörzése/eltávolítása
- indexek visszaállítása
- oszlopok átnevezése
3. **Adatok feltárása és elemzése:**
- leíró statisztikák: max, min, átlag
- vizualizációk készítése: diagramok, grafikonok

![](./assets/sales_query1.jpg)

![](./assets/sales_query2.jpg)
