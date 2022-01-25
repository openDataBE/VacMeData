# Vaccination SARS-CoV-2 data (Canton of Bern) reported by the "Gesundheits-, Sozial- und Integrationsdirektion (GSI) des Kantons Bern".

## Aim

The aim of this repository is to provide open government datasets for Vaccination SARS-CoV-2 related data (Canton Bern) reported by the "Gesundheits-, Sozial- und Integrationsdirektion (GSI) des Kantons Bern". Since January 2021 most cantons report vaccination data.

If you have any questions, please don't hestitate to contact us: <br>

- SARS-CoV-2 Hotline Canton Bern: +41 31 636 87 87 <br>
- [info@gsi.be.ch](mailto:info@info.be.ch) <br>

## List of open government datasets¹ and non-published datasets in this repository

**Federal Statistical Office**

- [Swiss official commune register¹](https://www.bfs.admin.ch/bfs/de/home/grundlagen/agvch.html) <br>
- [Bundesamt für Statistik (BFS), Statistik der Bevölkerung und der Haushalte¹](https://www.pxweb.bfs.admin.ch/sq/ef59b1fb-ec37-4481-bea9-1ea3238da2b3) <br>

**Canton Bern**

- [Vaccination Data - GSI] (not accessible)

## Table: 1. Vaccinations key figures

**General description** <br>
The table (vaccination_key_figures.csv) shows newly reported vaccinations.

**Data** <br>

Description: The values in this table show the current state of the reported vaccination numbers. <br>
Spatial unit: Canton of Bern <br>
Format: csv <br>
Stability of datasource: Basically very stable - dependent on Vaccination Data GSI.<br>
Update periodicy: This csv file is updated every 15 minutes.<br>

**Metadata**

| Field Name                          | Description                                               | Format              | Example                   | Source               |
| ----------------------------------- | --------------------------------------------------------- | ------------------- | ------------------------- | -------------------- |
| **dateStats**                       | Last vaccination sync date                                | YYYY-MM-DD HH:MM:ss | 2021-05-18T14:35:00+01:00 | Calculated           |
| **dateSlots**                       | Sync date free vaccination appointments                   | YYYY-MM-DD HH:MM:ss | 2021-05-18T14:35:00+01:00 | Calculated           |
| **totalVaccinationsLastWeek**       | Total vaccinated last week                                | Number              | 21247                     | Vaccination Data GSI |
| **totalVaccinationsSecondLastWeek** | Total vaccinated last two weeks                           | Number              | 67903                     | Vaccination Data GSI |
| **freeSlots**                       | Total free vaccination appointments for first vaccination | Number              | 415                       | Vaccination Data GSI |
| **totalYesterdayFirstVaccinated**   | Total yesterday first vaccinated                          | Number              | 440                       | Vaccination Data GSI |
| **totalCertificationAgreement**     | Total certificate requested for vaccinated                | Number              | 881277                    | Vaccination Data GSI |
| **freeSlotsBooster**                | Total free vaccination appointments for booster           | Number              | 87652                     | Vaccination Data GSI |
| **baseImmunized**                   | Total individuals with base immunization                  | Number              | 732020                    | Vaccination Data GSI |
| **boosterReleased**                 | Individuals currently released for booster vaccination    | Number              | 225372                    | Vaccination Data GSI |
| **personBoostered**                 | Total boosted individuals                                 | Number              | 404156                    | Vaccination Data GSI |

## Chart: 2. Vaccinations by district (Verwaltungskreis)

**General description** <br>
The chart shows vaccination data per district in the canton of Bern.

**Data** <br>

Description: The values in this table show the current state of the reported vaccination numbers per district.
Spatial unit: Region in the canton of Bern <br>
Format: csv <br>
Stability of datasource: Basically very stable - dependent on Vaccination Data GSI.<br>
Update periodicy: This csv file is updated every 15 minutes.<br>

**Metadata**

| Field Name           | Description                        | Format              | Example                   | Source                                                           |
| -------------------- | ---------------------------------- | ------------------- | ------------------------- | ---------------------------------------------------------------- |
| **date**             | Last vaccination sync date         | YYYY-MM-DD HH:MM:ss | 2021-05-18T14:35:00+01:00 | Calculated                                                       |
| **bfsNumber**        | BFS Number per district            | Number              | 247                       | Swiss official commune register¹                                 |
| **district**         | Region                             | Text                | Thun                      | Swiss official commune register¹                                 |
| **isBasicImmunized** | Total with base immunization       | Number              | 231913                    | Vaccination Data GSI                                             |
| **booster**          | Total boosted individuals          | Number              | 123786                    | Vaccination Data GSI                                             |
| **population**       | Number of inhabitants per district | Number              | 107029                    | Regionalportraets 2020: Kennzahlen aller Gemeinden¹ (calculated) |

## Chart: 3. Vaccinations by demographics

**General description** <br>
The chart shows vaccination data per demographics in the canton of Bern.

**Data** <br>

Description: The values in this table show the current state of the reported vaccination numbers per demographics.
Age range: Possible values

- A0019, for individuals younger or equal than 19 years old
- A2039, for individuals younger or equal than 39 years old
- A4059, for individuals younger or equal than 59 years old
- A6079, for individuals younger or equal than 79 years old
- A80Plus, for individuals older or equal than 80 years old

Format: csv <br>
Stability of datasource: Basically very stable - dependent on Vaccination Data GSI.<br>
Update periodicy: This csv file is updated every 15 minutes.<br>

| Field Name           | Description                  | Format              | Example                   | Source               |
| -------------------- | ---------------------------- | ------------------- | ------------------------- | -------------------- |
| **date**             | Last vaccination sync date   | YYYY-MM-DD HH:MM:ss | 2021-05-18T14:35:00+01:00 | Calculated           |
| **ageRange**         | Range of ageRange            | Text                | A4059                     | Vaccination Data GSI |
| **isBasicImmunized** | Total with base immunization | Number              | 231913                    | Vaccination Data GSI |
| **booster**          | Total boosted individuals    | Number              | 123786                    | Vaccination Data GSI |
