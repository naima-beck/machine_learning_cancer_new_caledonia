# Unsupervised Machine Learning for Cancer Epidemiology Mapping in New Caledonia

This project applies unsupervised learning to analyze cancer epidemiology in New Caledonia. It aims to discover hidden patterns and at-risk population groups using clustering algorithms. The local context presents unique challenges: significant geographical disparities in healthcare access, specific environmental risk factors, and cultural diversity affecting health behaviors. This data-driven mapping seeks to support public health strategy optimization across the Caledonian territory, helping to target prevention and resources more effectively.

## Dataset
This project utilizes the **"Épidémiologie descriptive des cancers en Nouvelle-Calédonie"** (Descriptive Epidemiology of Cancers in New Caledonia) dataset, which was obtained from the official open data portal of New Caledonia: [data.gouv.nc](https://data.gouv.nc/explore/dataset/epidemiologie_cancers_nc/information/?dataChart=eyJxdWVyaWVzIjpbeyJjb25maWciOnsiZGF0YXNldCI6ImVwaWRlbWlvbG9naWVfY2FuY2Vyc19uYyIsIm9wdGlvbnMiOnt9fSwiY2hhcnRzIjpbeyJhbGlnbk1vbnRoIjp0cnVlLCJ0eXBlIjoibGluZSIsImZ1bmMiOiJBVkciLCJ5QXhpcyI6InJhbmciLCJzY2llbnRpZmljRGlzcGxheSI6dHJ1ZSwiY29sb3IiOiIjNjZjMmE1In1dLCJ4QXhpcyI6ImFubmVlIiwibWF4cG9pbnRzIjoiIiwidGltZXNjYWxlIjoieWVhciIsInNvcnQiOiIifV0sImRpc3BsYXlMZWdlbmQiOnRydWUsImFsaWduTW9udGgiOnRydWV9https:%2F%2Fdata.gouv.nc%2Fapi%2Fexplore%2Fv2.1%2Fcatalog%2Fdatasets%2Fepidemiologie_cancers_nc%2Fexports%2Fcsv%3Flang%3Dfr&timezone=Europe%2FBerlin&use_labels=true&delimiter=,)

## Technologies used
- **Langage** : R


## Installation

### Clone the repository

```bash
git clone https://github.com/naima-beck/machine_learning_cancer_new_caledonia.git
cd machine_learning_cancer_new_caledonia
```

### Structure of the projet

```bash
machine_learning_cancer_new_caledonia/
├── data/
   ├── raw/
   └── processed/           
├── LICENSE
├── notebook/
   ├── 1_Cleaning.Rmd
   └── 2_Visualisation.Rmd           
└── README.md
```

## References

- **[content of the projet](./references/nom.pdf)**

## Authors

- [@naima-beck](https://www.github.com/naima-beck)
- [@axellelepoul-ctrl](https://www.github.com/axellelepoul-ctrl)

Cy Tech - Sciences-Po Saint-Germain-En-Laye - [2025/2026]

## License

This project is carried out in an academic setting. The data is provided for educational purposes.
It is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
![License](https://img.shields.io/badge/License-CC%20BY--NC--SA-blue.svg)
