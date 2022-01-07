# CheatSheet
A cheat sheet for computer science!

**Linux guide**

Through terminal 

ssh mnguyen001@ssh.csbsju.edu 
hostname -> a machine
exit  ->to exit 
ssh hpc0

hostname
top -> how many resource use 


ssh -J  ssh.csbsju.edu  hpc0 (proxy jump)

Create python virtual environment
python3 -m venv env
ls

On Verizon

ssh hpc0

_How to activate python virtual env_
source env/   -> activate python
source env/bin/activate.csh
pip install TensorFlow 
pip install —upgrade pip
pip install —upgrade setup tools
pip install opencv-python

pip install TensorFlow

_Transfer data_

cp [filename] [filename2]
scp [filename] mnguyen001@ssh.csbsju.edu:Desktop/folder name
scp -r [name of the folder] [name of the place]
scp -r work mnguyen001@ssh.csbsju.edu.edu:anna/work
rsync -avz 

Ex: rsync -avz system ssh.csbsju.edu: anna/system
Z: compress before copy
Send them:
And un compress them
A: the whole folder
v: show the copy 

View tensor board:
tensorboard —logdir=logs/


**Github**

Git init
Git remote add origin [link]


_Note:_
In src folder:
java -Xlint:unchecked controller/ThreadClass.java
java controller/ThreadClass 1024

_Add branch_
git branch #to list all the branch
git branch <branch_name> # to add branch 
git checkout <branch_name> #to switch to branch 

_Pull from another branch_
git pull origin <branch-name>

Git diff my branch master — myfile.cs

_How to fork after accidentally clone_
https://admcpr.com/what-the-fork/ 
	
_How to remove git upstream_
git remote rm upstream 
	
	
**Rails**

Add a new fieldname to existing data table:
rails generate migration add_fieldname_to_tablename fieldname:string
Destroy controller
Rails destroy controller controllerName 


**C++**
- Solved the filesystem error with the c_cpp_properties_json
AWS:
- Ruby on Rails:
	Edit AWS credentials: EDITOR=vim rails credentials:edit

Quaternion
python -m pip install --upgrade --force-reinstall numpy-quaternion 


**For iDock every time (in Ubuntu)**

export PATH=$PATH:/home/mythanhthaonguyen/idock/bin/Linux
In the folder contain (debug.conf file)
idock -- config debug.conf 

  

