## 1. Create a GitHub Repository
- Log in to your GitHub account.
- Click on New to create a new repository.
- Name your repository, choose visibility, and click Create repository.
## 2. Clone Your Git Repository to Local
```
git clone https://github.com/ahmadtarigan/Lab.git
```
#### To get the latest updates from the remote repository, use:
```
git pull origin main
```
## 3. Add Your Local Repo to Visual Studio Code
This is to make you eazier to maintain and edit the content
- add folder to workspace
- choose you repository folder
## 3. Push Changes to GitHub
#### Add and commit your changes 
```
git add .
git commit -m "Initial commit"
```
#### Push the changes to the GitHub repository (use the -u option to set the upstream branch):
```
git push -u origin main
```
## 4. Verify Remote Connection
```
git remote -v
```
