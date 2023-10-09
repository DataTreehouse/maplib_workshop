# Maplib workshop
To get started with the workshop, install Python. I prefer using miniconda3, and setting up a dedicated environment.
Jupyter notebook can be installed from anaconda prompt using:
```shell
conda install jupyter notebook
```

To run any of the notebooks, you should first install maplib.
```shell
pip install maplib
```

Then, run the command ```jupyter notebook``` from this folder with the environment activated to run the notebooks.

## Offshore leaks notebook
To run the offshore leaks notebook (leaks.ipynb), please download the zipped database from here:
https://offshoreleaks-data.icij.org/offshoreleaks/csv/full-oldb.20230309.zip
Unzip the contained csv-files to "offshoreleaks".
Then, run the write_leaks_parquets.ipynb.
This produces parquet files in the "offshoreleaks" folder. 
Then you can run leaks.ipynb.

## Solar mapping notebook
This notebook has all required datasets bundled.