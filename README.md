# END to END MAchine Learning Projects


1 - setup the github(repository)
  a. new environment
    -- create conda environment
		- open code folder in vscode
		- create env "conda create -p venv  python==3.8 -y
		- conda activate venv
    -- create Readme.md file.
         --    git init
        --     git add README.md
        -     git commit -m "first commit"
        -     git branch -M main
        -     git remote add origin https://github.com/santhulak/mlproject_deployment.git
        -     git push -u origin main
      - Create .gitignore file in github and choose category python
      - Git pull to pull the files to the local vs code
      - venv is not neccessary to be commited
  b. project setup (setup.py) - building the application as package
       - create setup.py file
       - create requirements.txt (-e . should be removed)
       - To do that pip install -r requirements.txt ( initiates setup.py)
       -- output of previous step ml_project.egg-info got created.
       - create a folder named 'src'-> __init__.py
       
              
  c. requirements.txt
