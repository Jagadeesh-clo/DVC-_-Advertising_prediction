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
