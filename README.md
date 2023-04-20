## End to End MAchine Learning Project
Deploying studentperformance indicator project in Azure Environment using CI-CD pipeline


## Run from terminal:

docker build -t testdockercicd.azurecr.io/studentperformanceazure:latest .

docker login testdockercicd.azurecr.io

docker push testdockercicd.azurecr.io/studentperformanceazure:latest
