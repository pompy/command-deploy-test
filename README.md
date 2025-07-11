# command-deploy-test
This is a testing project

1) Create a new file .github/workflows/deploy.yml with the following YAML content:

2) Add  package.json "homepage": "https://<your-username>.github.io/<your-repo-name>/"

3) Initial commands
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main

4) After push Go to your repository on GitHub and navigate to the Actions tab.
See https://<your-username>.github.io/<your-repo-name>/ see deployed site
