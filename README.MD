create env

```bash
conda create wineq python=3.7 -y
```
to activate environment
```bash
conda activate wineq
```
To create requirements.txt file
```bash
ni requirements.txt
````
to install libraries from requirements.txt
```bash
pip install requirements.txt
```
To create READ.md file
```bash
ni requirements.md
````
Download the data from
```bash
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5?usp=sharing
```
```bash
git init
```
```bash
pip install dvc
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add. && git commit -m "Updating readme.md"
```
```bash
git remote add origin https://github.com/harishpl02/dvc-wineq.git 
```
```bash
git branch -M main
```
```bash
git push origin main
```