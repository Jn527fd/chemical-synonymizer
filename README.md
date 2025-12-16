The data used was downloaded from:
  https://zenodo.org/records/17775114
  https://ftp.ebi.ac.uk/pub/databases/chebi/flat_files/

Python version: 3.12.9 (https://www.python.org/downloads/)

To install the dependencies run:
  - pip install -r requirements.txt

NOTE:
  - Only TF-IDF and edit distance were ran locally on laptop 
  - The rest of the notebooks were ran on google colab using either a A100 or T4 through the use
    of a student account to accomplish this you have to upload the data each time specifically testData.csv and finalData.csv, and mount the drive to save the models as they are trained in case of a crash or being disconnected from resources