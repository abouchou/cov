# 🧪 EpicystiR: Seroprevalence of Human Cysticercosis in Rural Areas of Southeastern Côte d'Ivoire

## 📘 Project Description

**EpicystiR** is a research project focused on the **seroprevalence of human cysticercosis** in rural areas of **Dabou** and **Agboville** districts in Côte d’Ivoire.  
Data were collected through **population-based cross-sectional surveys**.

---

## 📁 Repository Content

### 🗃️ Data Files

- `EpicystiR_Dabou.csv`: Data collected in the Dabou district.
- `EpicystiR_Agboville.csv`: Data collected in the Agboville district.
- `EpicystiR_Total.csv`: Combined data from both districts.
- `EpicystiR_Env.csv`: Environmental observations around surveyed households.

### 📜 Analysis Scripts

- `EpicystyR_Dabou_Code analyse.do`: Analysis of Dabou data.
- `EpicystyR_Agboville_Code analyse.do`: Analysis of Agboville data.
- `EpicystiR_Total_Env_code analyse.do`: Combined data and environmental analysis.

---

## 📖 Data Dictionaries

### 🧾 Dabou & Agboville

| Variable Name  | Description                                 |
|----------------|---------------------------------------------|
| `id`           | Participant identifier                      |
| `dte`          | Survey date                                 |
| `village`      | Village                                     |
| `grap`         | Cluster                                     |
| `spref/zone`   | Area of residence                           |
| `sexe`         | Sex                                          |
| `age`          | Age                                         |
| `age_cat`      | Age group                                   |
| `ancien`       | Time living in village                      |
| `etude`        | Level of education                          |
| `instruit`     | Literacy                                    |
| `muslim`       | Muslim religion                             |
| `cephal`       | Frequent headaches                          |
| `crisepi`      | Awareness of epileptic seizures             |
| `epifam`       | Epilepsy in the family                      |
| `vers`         | History of intestinal worms                 |
| `depara`       | Antiparasitic treatment history             |
| `tenia`        | Knowledge about tapeworm                    |
| `cmodet`       | Knowledge of tapeworm transmission          |
| `cyst`         | Awareness of cysticercosis                  |
| `lmain`        | Handwashing habit                           |
| `pleinair`     | Open defecation                             |
| `typ_eau`      | Tap water consumption                       |
| `pluie`        | Rainwater consumption                       |
| `lavcrudi`     | Washing raw vegetables                      |
| `cporc`        | Pork consumption                            |
| `prelev`       | Blood sample collected                      |
| `elisa`        | ELISA test result                           |
| `wb`           | Western Blot result                         |
| `cysti`        | Serological result for cysticercosis        |
| `pds`          | Sampling weight                             |
| `t_grap`       | Cluster size                                |
| `t_vilag`      | Village population                          |

### 🧾 EpicystiR_Total

| Variable Name  | Description                                 |
|----------------|---------------------------------------------|
| `id`           | Participant identifier                      |
| `dte`          | Survey date                                 |
| `departement`  | District                                    |
| `zone2`        | Area of residence                           |
| `age`          | Age                                         |
| `age_cat`      | Age group                                   |
| `sexe`         | Sex                                          |
| `instruit`     | Literacy                                    |
| `etude`        | Level of education                          |
| `muslim`       | Muslim religion                             |
| `ancien`       | Time living in village                      |
| `lmain`        | Handwashing habit                           |
| `lavcrudi`     | Washing raw vegetables                      |
| `typ_eau`      | Tap water consumption                       |
| `pluie`        | Rainwater consumption                       |
| `cporc`        | Pork consumption                            |
| `pleinair`     | Open defecation                             |
| `cysti`        | Serological result for cysticercosis        |

### 🧾 EpicystiR_Env (Environmental Data)

| Variable Name  | Description                                 |
|----------------|---------------------------------------------|
| `idf`          | Household identifier                        |
| `dte`          | Survey date                                 |
| `departement`  | District                                    |
| `vilag`        | Village                                     |
| `resident`     | Number of household members                 |
| `potable`      | Drinking water access                       |
| `main`         | Presence of handwashing facility            |
| `latrine`      | Presence of household latrines              |
| `ordures`      | Wild garbage disposal nearby                |
| `porcheri`     | Presence of pig farming nearby              |

---

## 🧰 Instructions for Use

This project is intended for public health researchers, students, and data analysts. You don’t need programming experience to use the data.

### 🔸 How to Access the Files

You can download the data and scripts directly from the GitHub repository:

1. Go to the project page on GitHub: [https://github.com/samk253/EpicystiR](https://github.com/samk253/EpicystiR)
2. Click on the green **“Code”** button and choose **“Download ZIP”**.
3. Extract the ZIP file to your computer.

### 🔸 How to View and Analyze the Data

- The `.csv` files can be opened with **Excel**, **LibreOffice Calc**, or any statistical software like **R**, **Stata**, or **SPSS**.
- The `.do` files are **Stata scripts**. You can open them with Stata or any text editor.

---
