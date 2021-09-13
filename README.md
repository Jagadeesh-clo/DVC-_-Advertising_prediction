    create env

conda create -n advert python=3.7 -y
#activate env

conda activate advert
#created a req file

#install the req

pip install -r requirements.txt

git init
dvc init 
dvc add data_given/winequality.csv
git add .
git commit -m "first commit"

git remote add origin https://github.com/Jagadeesh-clo/DVC-_-Advertising_prediction.git

"""
git branch -M main


git push origin main

"""

