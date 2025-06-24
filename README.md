# GitHub-Action-CI-CD-YAML

GitHub Action and CI/CD Course Project - YAML




 # Step 1: Creating my repository**  

 - starting  by creating a new repository on GitHub. This is where all my project files and workflow configurations will be stored.
  ![1](./img/1.png)  
   


 # Step 2: Clone the repository

 - Next i  clone the repository to my local machine using `git clone`. This allows me to work on my project files locally before pushing changes back to GitHub.
  ![2](./img/2.png)  

  


# Step 3: Creating a workflow 

- I create a workflow file (e.g., `.github/workflows/main.yml`). This YAML file defines the automation steps that GitHub Actions will run, such as installing dependencies, building, and testing my code.
  ![3](./img/3.png)  
  



# Step 4: Adding script to the workflow

- I add steps in my workflow file to automate tasks. Common steps include checking out my code, setting up Node.js, installing dependencies with `npm install`, running build scripts, and executing tests.*
  ![4](./img/4.png)  
  



# Step 5: Open package.json and add script 

- I edit my `package.json` file to ensure it contains the necessary `build` and `test` scripts. These scripts are called by the workflow to build and test my project automatically.

  ![5](./img/5.png)  
  

# Step 6: Facing error

*If there is a problem (such as a missing file or a script error), the workflow will fail. i can view detailed error logs in the GitHub Actions tab to help me troubleshoot and fix the issue.

  ![6](./img/error.png)  
  

# Step 7: Fixing and working 

 - After fixing the errors, i push my changes again. The workflow is now complete successfully, showing green check marks for each step in the Actions tab.
  ![7](./img/6.png)  
 