# Practical Task - CI/CD
A simple CI/CD pipeline using GitHub Actions
## Steps

1. Forked a public repository to create a personal working copy.  
2. Cloned the forked repository to my local machine.  
3. Created a GitHub Actions workflow that:  
   1. Checks the `requirements.txt` file and installs the required dependencies.  
   2. Once the install job succeeds, runs the test job which looks for the `tests` folder then runs `test_basic.py` and `test_advanced.py`.  
   3. Once the test job succeeds, runs the mock deploy job.  

The workflow triggers automatically whenever there is a push to the `master` branch.
