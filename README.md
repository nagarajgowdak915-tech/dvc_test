# dvc_test

cd dvc_test 

dvc init 

python main.py

dvc remote add -d myremote s3

dvc add data/

dvc commit dvc push