# Dog Bite Incident Dataset (NYC Open Data)

This repository contains a dataset of dog bite incidents from the DOHMH NYC Open Dataset https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data/rsgh-akpg/about_data, compiled for analysis in Microsoft Excel. 

The data includes 30,000 records with details such as species, breed, location of incidents.

---

## 📁 Files

- `DOHMH_Dog_Bite_Data_20250726.csv` – Main dataset file with 30,000 dog bite records.

---

## 🧾 Dataset Description

Each row in the CSV represents a reported dog bite incident. The columns include:          

| Column Name        | Description |
|--------------------|-------------|
| `UniqueID`         | Unique dog bite case identifier|
| `DateOfBite`       | Date Bitten |
| `Species`          | Animal Type(Dog) |
| `Breed`            | Breed Type |
| `Age`              | Dog's Age at time of bite. Number with 'M' indicate months |
| `gender`           | Sex of Dog M=Male, F=Female, U=Unknown|
| `SpayNeuter`       | Surgical removal of dog's reproductive organs. True (reported to DOHMH as Spayed or Neutered), False (Unknown or Not Spayed or Neutered |
| `Borough`          |  Dog bite Borough. Other' indicates that the bite took place outside New York City |
| `Zipcode`          | Dog bite Zipcode. Blank ZipCode indicates that information was not available |


---

## 📊 How to Use

You can open `DOHMH_Dog_Bite_Data_20250726.csv` directly in Microsoft Excel for:
- Sorting and filtering
- Creating PivotTables (e.g., bite counts by breed or region)
- Visualizing trends (e.g., charts of incidents over time)

---

## 🔍 Example Analysis Ideas

- Most frequent breeds involved in bites
- Locations with the highest bite rates
- Age groups of dogs that bites occur

---

## ✅ License / Source

If applicable, explain where the data came from or what license applies:
> This dataset is from public source NYC Open Data, and is provided for educational use only.

---

## 🙋‍♂️ Contributions / Issues

Feel free to open an issue or pull request if you'd like to contribute or fix errors in the data or analysis.
