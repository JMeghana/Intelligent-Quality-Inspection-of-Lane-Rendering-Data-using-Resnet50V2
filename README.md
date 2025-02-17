# Intelligent Quality Inspection of Lane Rendering Data using Resnet50V2 - Huawei Hackathon  <!-- /- Go Team **AbsoluteNoobs**🏆🏆--> 

## Initial Setup : 

### Create your own env:
```bash
bash init_setup.sh

source activate ./conda_env
```
### Create dev branch
```
git checkout dev
```

## Commit your changes to git
```bash
# Check for broken requirements first..
pip check
# If there are no broken requirements, export requirements.txt
pip list --format=freeze > requirements.txt

# Check Branch..
git branch -a

# Commit to git.
git add .
git commit -m "<Commit Message>"
git branch
git push origin main
```

## Create your own Git Repo:
```bash 
rm -rf .git

git init

git add .

git commit -m "First Commit"

git branch -M main

git remote add origin <Your New Repository>

git push -u origin main

```
