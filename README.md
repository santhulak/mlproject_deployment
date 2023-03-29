# END to END MAchine Learning Projects

<<<<<<< HEAD


## a. setup the github(repository)
    - create conda environment
		- open code folder in vscode
=======
<ol>
<li>1.  - setup the github(repository)
	
  a. create a new environment
	
    -- create conda environment	
    -- open code folder in vscode
	
>>>>>>> d350574b781f4721482af21374837508c44e86dd
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
      
 ## b. project setup (setup.py) - building the application as package
       - create setup.py file
       - create requirements.txt (-e . should be removed)
       - To do that pip install -r requirements.txt ( initiates setup.py)
       -- output of previous step ml_project.egg-info got created.
       - create a folder named 'src'-> __init__.py
    </ol>   
              
<<<<<<< HEAD
# c. Project Structure

-- create a folder named 'src'-> __init__.py
-- create a folder named components under src folder and add __init__.py file
-- create dataingestion.py under components folder(data collection)
-- create datatransformation.py under components folder(data training)
-- create model_trainer.py under components folder(training the model)

-- create a folder named pipeline under src folder and add __init__.py file
-- create train_pipeline.py under pipleine folder(train pipeline)
-- create predict_pipeline.py under pipleine folder(predict pipeline)


-- Under src folder create logger.py , exception.py, utils.py


## d . Exception
=======
  c. requirements.txt
>>>>>>> d350574b781f4721482af21374837508c44e86dd

## e. EDA and Model Training
 * create a folder 'Notebook' -> eda.ipynb and model_training.ipynb
