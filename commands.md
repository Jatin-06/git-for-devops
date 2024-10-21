# Git Commands

## 1. Initialize a Git Repository
mkdir git-for-devops  
cd git-for-devops/  
git init  

## 2. Create and Modify Files
vi abc.txt  
ls  
rm abc.txt  
touch nibba.txt nibba.txt  
touch nibbi.txt  

## 3. Check the Status of the Working Directory
git status  

## 4. Stage Files for Commit
git add .  
git rm --cached abc.txt  

## 5. Commit Changes
git commit -m "jatin"  
git commit -m "jatin1"  

## 6. Restore Files
git restore abc.txt  
git restore --stage abc.txt  

## 7. Configure Git User Information
git config --global user.name "jatin06"  
git config --global user.email "justin.gawad@gmail.com"  

## 8. View Commit History
git log  
git log --oneline  

## 9. Work with Branches
git branch  
git checkout -b dev  
git checkout master  
git checkout dev  

## 10. Additional Commands
ls -a  
ls -l abc.txt  

## 11. Review Files and Commits
ls  
git status  
