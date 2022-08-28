# Rabitabank-Project

1. Create envrionment:
  $ python -m venv env


2. Activate environment:
  $ Set-ExecutionPolicy Unrestricted -Scope Process (on Windows)
  $ .\env\Scripts\Activate
    
    
3. Install packages in requirements.txt:
  $ pip install -r requirements.txt
  
 
 4. Create the database or enable migrations:
  $ flask db init
  
  
 5. Generate inital migration:
  $ flask db migrate
  
  
 6. Apply migrations to database:
  $ flask db upgrade
  
