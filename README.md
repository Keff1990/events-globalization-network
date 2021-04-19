# events-globalization-network

Please ensure conda is installed. https://docs.conda.io/en/latest/miniconda.html

Install the environment via `conda env create -f environment.yml`.

Open the `CCS_Gdelt Data Study.ipynb` notebook using `jupyter notebook` to view the analysis.

### File Structure:
.  
├── Data                        # Compiled Data for the project  
│   ├── Raw                     # Files obtained from an external source  
│   └── Processed               # Saved files from the notebook  
├── Figures                     # Saved Figures from the notebook  
├── Others                      # Reference files  
├── CCS_Gdelt Data Study.ipynb  # iPython notebook containing code and analysis  
├── enviroment.yml              # yml file to install the enviroment  
├── LICENSE  
└── README.md  

## External Data Sources:
### GDELT
GDELT data is retrieved via Google BigQuery.  
NOTE: Author needs to review if this is the most updated query: https://console.cloud.google.com/bigquery?sq=30942656811:1519ebd5912a4cc4af00bff955739a2b  
NOTE: The query above is outdated and highly inefficient. Review revising the source table to lessen the queried data.  
