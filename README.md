# Multi-Relation-QA-over-KG
Run all commands from the directory containing this README file. Make sure python 3.5 or above is installed.


## Installing Libraries
Use [pip](https://pip.pypa.io/en/stable/) as a package manager to install the required libraries.

**If you only wish to see the model results:**

Execute ``` 
pip install matplotlib
```
---

**If you wish to train the model:**


Execute ```
pip install -r requirements.txt
```
----
## Visualizing the model results

Execute ```
python plot.py
```

Training and Validation results are displayed in separate plots.

----
## Training the model

### Download the dataset
A pre-trained embedding is used to embed the entities and relations used in our knowledge graph.
Due to the size of the datasets, these are not submitted, but they are required to run the model.

To download the dataset, follow the steps below.

1. Follow this [link](http://139.129.163.161/index/toolkits#pretrained-embeddings)
2. Download the Freebase dataset. (Submit the license agreement as required)
3. Unzip the file.
4. Save the freebase folder into the datasets subfolder i.e. (/datasets/freebase/)

### Train the model

Execute ``` 
python experiment.py
```
