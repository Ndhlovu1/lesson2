# STEPS TO START RUN DJANGO Project
	
CONDITIONAL-STEPS

## a. Creating a New Project :
		1. Create a Container Folder(mkdir folder_name) 
			[Inside the folder open vscode, code .]
			[ git init ] It creates a local repository to save your file changes
			
		2. Install Django (pipenv install django)
			[You should see the Pipfile and the Pipfile.lock]
		
		3. Activate the virtual environment (pipenv shell)
			
		4. Inside the vscode, press
			[CTRL + P and then type >python interpreter, and select the name of your folder]
			
		5. Make the Migrations 
			1st Command (python manage.py makemigrations) It is responsible for 
			2nd Command (python manage.py migrate)
	
		6. Creating the superuser account (python manage.py createsuperuser)
		
		
## b. Opening an Existing Project
	
		1. Go to the containing folder
		2. Type the cmd (code .) to open vscode
		3. Run the command (pipenv shell)
		4. Press Ctrl + P , then type >select python interpreter and choose the one named after your folder
		5. Find the file named (manage.py) ny running ls on the containing folder then again on the contained folder
		6. Go into the contained Project (cd folder_name) and type ls to find the manage.py file
		7. Run the command (python manage.py runserver)
		8. Open the browser and go to the Localhost:8000
		9. Inside the browser run the command localhost:8000/admin

## c. Git Commands to Remote

		1. `git add . ` - You are adding everything into the staging area

		2. `git commit -m "Project Update"` - adding a message that will appear in the git logs

		**NB : IF IT IS YOUR FIRST TIME WRITING TO GITHUB REPOSITORY DO STEP 3 ELSE SKIP TO STEP 5**

		3. `git branch -M main`

		4. `git remote add origin github_repository_url`

		5. `git push -u origin main git`  `push -u --set-upstream origin main`

		

