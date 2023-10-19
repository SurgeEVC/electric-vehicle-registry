
# Electronic Vehicle Registry

This repository provides comprehensive data on electronic vehicles (EVs) in the form of structured JSON files. It is designed to be a collaborative platform, where users can contribute to enrich the data with newer models, additional details, and corrections to existing data.

## Top Level Directory Structure
Data is organized chronologically, which makes it easy to find EV models by their release year. As years progress, new top-level folders can easily by added without modifying previous data. Users can easily compare the evolution of a particular model over the years or see what was available in a specific year. 

```
.
|-- 2021
|   |-- Tesla
|   |-- Chevrolet
|   `-- ...
|-- 2022
|   `-- ...
`-- 2023
.
```

This chronological arrangement allows users to:

- Compare the evolution of a particular EV model over the years.
- Check the available EVs in a specific year.


## Basic Format for JSON entries
Each EV's data is stored in a JSON file, named based on the following convention:

- Basic Format: ` [year]-[make]-[model]-[variant].json`
- Example Name: `2023-tesla-model-s-long-range-plus.json`

Do not use abbreviations of makes, models, variants; do not remove vowels or shorten nomenclature.
Use lowercase for filenames.



## Usage

These JSON files can serve various purposes:

- Building EV comparison tools.
- Integrating into automotive platforms or applications.
- Educational and research purposes.




