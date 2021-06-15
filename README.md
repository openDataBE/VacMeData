# Vaccination SARS-CoV-2 data (Canton of Bern) reported by the "Gesundheits-, Sozial- und Integrationsdirektion (GSI) des Kantons Bern".
​
## Aim
​
The aim of this repository is to provide open government datasets for Vaccination SARS-CoV-2 related data (Canton Bern) reported by the "Gesundheits-, Sozial- und Integrationsdirektion (GSI) des Kantons Bern". Since January 2021 most cantons report vaccination data.
​
If you have any questions, please don't hestitate to contact us: <br>
​
- SARS-CoV-2 Hotline Canton Bern: +41 31 636 87 87 <br>
- [info.gsi@be.ch](mailto:info.gsi@be.ch) <br>
​
## List of open government datasets¹ and non-published datasets in this repository
​
**Federal Statistical Office**
​
- [Swiss official commune register¹](https://www.bfs.admin.ch/bfs/de/home/grundlagen/agvch.html) <br>
- [Bundesamt für Statistik (BFS), Statistik der Bevölkerung und der Haushalte¹](https://www.pxweb.bfs.admin.ch/sq/ef59b1fb-ec37-4481-bea9-1ea3238da2b3) <br>
​
**Canton Bern**
​
- [Vaccination Data - GSI] (not accessible)
​
## Table: 1. Vaccinations key figures
​
**General description** <br>
The table (vaccination_key_figures.csv) shows newly reported vaccinations.
​
**Data** <br>
​
Description: The values in this table show the current state of the reported vaccination numbers. <br>
Spatial unit: Canton of Bern <br>
Format: csv <br>
Stability of datasource: Basically very stable - dependent on Vaccination Data GSI.<br>
Update periodicy: This csv file is updated every 15 minutes.<br>
​
**Metadata**
​
| Field Name                          | Description                             | Format              | Example                   | Source               |
| ----------------------------------- | --------------------------------------- | ------------------- | ------------------------- | -------------------- |
| **dateStats**                       | Last vaccination sync date              | YYYY-MM-DD HH:MM:ss | 2021-05-18T14:35:00+01:00 | Calculated           |
| **dateSlots**                       | Sync date free vaccination appointments | YYYY-MM-DD HH:MM:ss | 2021-05-18T14:35:00+01:00 | Calculated           |
| **totalRegistrations**              | Total registered persons                | Number              | 591428                    | Vaccination Data GSI |
| **totalSingleVaccinated**           | Total single vaccinated                 | Number              | 172046                    | Vaccination Data GSI |
| **totalDoubleVaccinated**           | Total double vaccinated                 | Number              | 166562                    | Vaccination Data GSI |
| **totalVaccinationsLastWeek**       | Total vaccinated last week              | Number              | 21247                     | Vaccination Data GSI |
| **totalVaccinationsSecondLastWeek** | Total vaccinated the week before last   | Number              | 67903                     | Vaccination Data GSI |
| **freeSlots**                       | Total free vaccination appointments     | Number              | 415                       | Vaccination Data GSI |

## Chart: 2. Vaccinations by district (Verwaltungskreis)
​
**General description** <br>
The chart shows vaccination data per district in the canton of Bern.
​
**Data** <br>
​
Description: The values in this table show the current state of the reported vaccination numbers per district.
Spatial unit: Region in the canton of Bern <br>
Format: csv <br>
Stability of datasource: Basically very stable - dependent on Vaccination Data GSI.<br>
Update periodicy: This csv file is updated every 15 minutes.<br>
​
**Metadata**
​
| Field Name                | Description                        | Format              | Example                   | Source                                                           |
| ------------------------- | ---------------------------------- | ------------------- | ------------------------- | ---------------------------------------------------------------- |
| **date**                  | Last vaccination sync date         | YYYY-MM-DD HH:MM:ss | 2021-05-18T14:35:00+01:00 | Calculated                                                       |
| **bfsNumber**             | BFS Number per district            | Number              | 247                       | Swiss official commune register¹                                 |
| **district**              | Region                             | Text                | Thun                      | Swiss official commune register¹                                 |
| **totalRegistrations**    | Total registered persons           | Number              | 105486                    | Vaccination Data GSI                                             |
| **totalSingleVaccinated** | Total single vaccinated            | Number              | 70752                     | Vaccination Data GSI                                             |
| **totalDoubleVaccinated** | Total double vaccinated            | Number              | 67427                     | Vaccination Data GSI                                             |
| **population**            | Number of inhabitants per district | Number              | 107029                    | Regionalportraets 2020: Kennzahlen aller Gemeinden¹ (calculated) |
