# VIRTUAL-ENVIRONMENT- https://www.youtube.com/watch?v=APOPm01BVrk
#COMMANDS
  #change directory
  cd 
  #modules install
  pip list 
  #List out all de files
  dir
  #Paths to the current python command
  where python
  #Clear all
  cls
  
  
#STEPS
  #create virtual environment. name = virutal environment name. VENV = Module. create a folder named "name"
  python -m venv name
  # Activate viertual environment. (name)
  name\Scripts\activate.bat
  # Install libreries
  pip intall library_name
  # Export packages. give us the packages in the correct form to create a txt file
  pip freeze
  # deactivate environment
  deactivate
  #delete environment. /s is for delete all the tree. it also can be deleted deliting all the folders
  rmdir  name /s
  
  # Install packages from a txt file
  pip install -r text_file_name.txt


#TIPS
create virtual environment inside the project folder
do not put project files into the virtual environmente folder
