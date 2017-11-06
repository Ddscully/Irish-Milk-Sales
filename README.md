# Irish-Milk-Sales

An analysis of milk sales in the Republic Of Ireland.

Notebooks where developed using the jupyter datascience notebook docker image which can be set up as follows
```
docker run --name dtsci -p 8888:8888 jupyter/datascience-notebook
```

To add fbprophet run the following
```
docker exec dtsci conda install -c conda-forge fbprophet --yes
```
Notebooks and data files can be uploaded via the webpage running on http://localhost:8888 and extened as normal.

A seperate notebook with the R kernal was used to convert the px file to csv file for use with panads.
