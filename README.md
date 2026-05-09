# DevInD: A Database and Prediction Tool for Industrial Drug Molecules

**DevInD** (Development of Industrial Drug molecules) is a specialized computational platform designed to provide comprehensive information and predictive models for drug molecules currently used or developed in the pharmaceutical industry.
This resource serves as a centralized repository to assist researchers in understanding the chemical and biological properties of successful industrial drug candidates.

**Web Server:** https://webs.iiitd.edu.in/raghava/denvind/


## Citation
Vivek Dhar Dwivedi, Aditya Arya, Pardeep Yadav, Rajesh Kumar, Vinod Kumar, Gajendra P S Raghava, **DenvInD: dengue virus inhibitors database for clinical and molecular research,**
Briefings in Bioinformatics, Volume 22, Issue 3, May 2021, https://doi.org/10.1093/bib/bbaa098

This dataset can also be found on Zenodo at

## About the Platform

The pharmaceutical industry follows rigorous standards for selecting molecules with optimal pharmacokinetic and pharmacodynamic profiles. DevInD consolidates data on these "industrial-strength" molecules, which often differ significantly
from common chemical libraries or early-stage leads.

* **Data Compilation**: The platform is built upon a manually curated dataset of drug molecules that have reached various stages of industrial development and clinical trials.
* **Focus on Drug-Likeness**: It emphasizes the structural features and molecular descriptors that contribute to a molecule's success in an industrial setting.


## Key Features

### 1. Extensive Chemical Database

* **Curated Molecules**: Contains detailed profiles of molecules, including their chemical structures, target proteins, and therapeutic categories.
* **Pharmacological Data**: Provides information on $IC_{50}$, $EC_{50}$, and other potency measures relevant to industrial drug standards.

### 2. Predictive Modeling

* **Industrial Potency Prediction**: Utilizing machine learning models (such as SVM and Random Forest), the platform allows users to predict the likelihood of a query molecule being an effective industrial drug candidate.
* **Descriptor Analysis**: Computes a wide array of 1D, 2D, and 3D molecular descriptors to characterize the chemical space of the molecules.

### 3. Integrated Web-Bench

* **Search and Browse**: Users can easily query the database by drug name, chemical scaffold, or therapeutic use.
* **Similarity Search**: Tools to find industrial molecules that are structurally similar to a user's query compound.
* **Property Visualization**: Interactive tools to visualize the distribution of physicochemical properties across the industrial drug dataset.


## Applications

* **Drug Repurposing**: Identifying existing industrial molecules that may have therapeutic potential for new disease indications.
* **Lead Prioritization**: Helping researchers prioritize lead compounds by comparing them to the structural profiles of established industrial drugs.
* **Pharmacoinformatics**: Providing a high-quality dataset for training new AI/ML models in the field of drug discovery and development.


## Contact & Authors

**Prof. Gajendra P. S. Raghava** (Corresponding Author)

raghava@iiitd.ac.in

Department of Computational Biology, Indraprastha Institute of Information Technology (IIIT Delhi), New Delhi, India.


## Support

DevInD was developed with support from the **Department of Biotechnology (DBT)** and the **Council of Scientific and Industrial Research (CSIR)**, Government of India. Infrastructure and facilities were provided by **IIIT-Delhi**.
