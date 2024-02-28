## Python Environment
conda create -n your_env_name python=3.9
Create the environment from the environment.yml file
conda env create -f environment.yml
Check if environment is create d
conda env list
link [https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#activating-an-environment] 


## Others
- Track progress in for loop \
- pip install progress\
  from progress.bar import Bar\
  with Bar('Processing Good...',max=len(df)) as bar:\
      for i in range(len(df)):\
          # your code\
          bar.next()
