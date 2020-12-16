1. Letölti a https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide oldalról a legfrissebb COVID-19 adatokat XML formátumban.
2. Betölti az XML fájlban lévő adatokat egy CovidRecord osztályból álló listába. 1/C
3. Szűrni lehet a CovidRecord-okból álló listát év, hónap, nap, kontinens és ország szerint 2/A
4. Egy dataGridView-ban megjelennek a releváns CovidRecord-ok
5. Ezeket ki lehet exportálni egy CSV fájlba 3/A
6. A dataGridView automatikusan görgeti magát lefele, ha bepipáljuk az AutoScroll CheckBox-ot 4/D

Megjegyzések: A beadandóm elkészítését a VersionControl repositoryban végeztem, és csak a végleges változatott vittem át a IRF_Project repo-ba, ezért van ilyen kevés commit. Ha meg akarja tekinteni a projekt alakulásának lépéseit, akkor a feketegabor/VersionContol repoban lévő "beadandó" projektben keresse a commitokat.
