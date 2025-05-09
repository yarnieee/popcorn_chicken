# popcorn_chicken

how to run:

## 1. download the dataset
Please download the dataset from https://www.kaggle.com/datasets/birdy654/cifake-real-and-ai-generated-synthetic-images?resource=download
and place the dataset in the same folder as the .ipynb file.

If you choose to **not** extract the zip file, pls rename the zip file to "**cifake.zip**" and uncomment the cell directly under *Load Dataset* in the .ipynb file by highlighting the entire cell and clicking (*ctrl + /*)


## 2. download requirements

```.
!pip install -r requirements.txt
```
In the case that torchcam does not automatically download, pls run
```
!pip install torchcam
```

## 3. Running the .ipynb file
Before clicking "run all", pls double check that the dataset- 

if extracted, both test and train folders should be in the same folder as the .ipynb file

otherwise, the zip file (cifake.zip) should be in the same folder as the .ipynb file

## 4. profit YAY!
