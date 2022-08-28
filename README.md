# Rabitabank-Project

1. Create envrionment:\n
  $ python -m venv env


2. Activate environment:\n
  $ Set-ExecutionPolicy Unrestricted -Scope Process (on Windows)
  $ .\env\Scripts\Activate
    
    
3. Install packages in requirements.txt:\n
  $ pip install -r requirements.txt
  
 
 4. Create the database or enable migrations:\n
  $ flask db init
  
  
 5. Generate inital migration:\n
  $ flask db migrate
  
  
 6. Apply migrations to database:\n
  $ flask db upgrade
  
