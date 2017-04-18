# Error-occurrence-when-I-input-the-code-conda-env-create--f-filename1

Using Anaconda API: https://api.anaconda.org 

An unexpected error has occurred. 

Current conda install:                 
platform : linux-64           
conda version : 4.3.16        
conda is private : False       
conda-env version : 4.3.16     
conda-build version : not installed          
python version : 3.6.0.final.0        
requests version : 2.12.4        

root environment : /home/zhaxj/softs/miniconda3  (writable)     
default environment : /home/zhaxj/softs/miniconda3       
envs directories : /home/zhaxj/softs/miniconda3/envs      
/home/zhaxj/.conda/envs           
package cache : /home/zhaxj/softs/miniconda3/pkgs                    
/home/zhaxj/.conda/pkgs           
channel URLs : https://repo.continuum.io/pkgs/free/linux-64                
https://repo.continuum.io/pkgs/free/noarch              
https://repo.continuum.io/pkgs/r/linux-64                   
https://repo.continuum.io/pkgs/r/noarch                     
https://repo.continuum.io/pkgs/pro/linux-64                    
https://repo.continuum.io/pkgs/pro/noarch         
config file : None          
offline mode : False          
user-agent : conda/4.3.16 requests/2.12.4 CPython/3.6.0 Linux/4.8.0-46-generic debian/stretch/sid glibc/2.23           
UID:GID : 1000:1000  


`$ /home/zhaxj/softs/miniconda3/bin/conda-env create -f isce_2017.yml`      
Traceback (most recent call last):      

File "/home/zhaxj/softs/miniconda3/lib/python3.6/site-packages/conda/exceptions.py", line 626, in conda_exception_handler        
return_value = func(*args, **kwargs)      
File "/home/zhaxj/softs/miniconda3/lib/python3.6/site-packages/conda_env/cli/main_create.py", line 78, in execute      
directory=os.getcwd())       
File "/home/zhaxj/softs/miniconda3/lib/python3.6/site-packages/conda_env/specs/__init__.py", line 23, in detect       
raise SpecNotFound(build_message(specs))    
conda_env.exceptions.SpecNotFound: Runtime error: Can't process without a name    
Conda Env Exception: isce_2017.yml file not found   

There is no requirements.txt
