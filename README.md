# DSA4213-assignment-3
DSA4213 assignment 3 for text classification using Longformer Bert model, more specifically, classification on long-form political documents/articles by political bias between 'left', 'lean left', 'centre', 'lean right' and 'right'.

The notebooks with output i.e. `FFT.ipynb`, `LoRA.ipynb` and `IA3.ipynb` all show the same following viewing error:
```
Invalid Notebook
There was an error rendering your Notebook: the 'state' key is missing from 'metadata.widgets'. Add 'state' to each, or remove 'metadata.widgets'.
Using nbformat v5.10.4 and nbconvert v7.16.6
```
These notebooks were run on Google CoLab's TA GPU and hence had cells to mount google drive to access the dataset `Political_Bias.csv`. 

To run the notebooks on your local machine, use the `..._unrun.ipynb` versions. Furthermore, the requirements.txt file should be run in the same environment first:
```bash
pip install -r requirements.txt
```
