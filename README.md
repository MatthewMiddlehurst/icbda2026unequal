# Classifying unequal length time series with HIVE-COTE 2.0
## ICBDA 2026

Repo for the ICBDA 2026 unequal length time series submission.

Data:
    `datasets.py` can be used to process the `.ts` files uploaded by the UCR archive maintainers (https://zenodo.org/records/11198697) into unequal length versions.
    Due the size of the unequal archive it is difficult to upload it while adhering to blind review guidelines. We will make a `.zip` version of the unequal archive available.

Results:
    `.csv` files are provided which give the accuracy  and other scores on the mixed unequal archive.

Code:
    Python code for HC2 and its components are provided in the `algorithm_code` folder. Based on open-source code from the `aeon` toolkit. An example run is shown in `basics.ipynb`.
