# Joint research projects

## Extract data

1. Retrieve list of projects via search mask at [Funding Catalogue](https://foerderportal.bund.de/foekat/jsp/SucheAction.do?actionMode=searchmask) using

- Project sponsor = PT-DESY
- Only Lfd. Project = No

2. Download search result as csv file ("Output as text file")

3. Save the file as "/data/project support_pt-desy.0.extracted.csv".

3. Change the file encoding from "iso-8859-1" to "UTF-8" (no BOM), convert the entries in the "Amount of funding" field from German formatting to integers.


## Use Jupyther Notebook

Open and execute `erum-funding__accelerator-research-related.ipynb` file