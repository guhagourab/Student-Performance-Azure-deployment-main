## End to End MAchine Learning Project
Deploying studentperformance indicator project in Azure Environment using CI-CD pipeline


## Run from terminal:

docker build -t testdockerkrish.azurecr.io/mltest:latest .

docker login testdockerkrish.azurecr.io

docker push testdockerkrish.azurecr.io/mltest:latest
