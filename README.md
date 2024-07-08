**<h1>The following steps is how to set up a GitHub Action Pipeline</h1>**

**Launch an Ubuntu instance**
![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/4a3a6757-19a8-4317-a0a4-c49934bd1bf2)

**Then create a Github Account**

Create a repository, then create a directory for your project.
Go to the Repository==> Setting===> Action===> Runner===> New self-hosted runner, as shown below:
![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/abcc8829-83e0-4298-a516-5eeb261f4562)

**Go to your github account, log into it, update and follow the provided steps as shown below:**
 ![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/31000578-d1e8-4bb7-ac69-eda28445b7d7)

**Download the binary in your Ubuntu instance:**
![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/92097f56-a8bf-4f1d-9d58-b1d52c32baf4)

**Follow the Runner is configured (as and connected to GitHub. Ensure to use “self-hosted” for label.**
![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/a3d4dd44-fafe-46a1-a851-aa3d0dc3f5e2)

**Runner is started with this command;**

 **./run.sh**
 
![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/1c8507bd-8496-4aa2-9160-a5bac126e2f1)


**Any commits made to the branch stated in your  “repository_name/.github/wokflows/action.yaml’  file in your repository like this…**
![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/718453d0-dd4d-4e7e-8057-043f8d27347f)

![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/75c4254c-caf9-44f4-a188-b79ef8280ed5)

	…trigger the runner to run the job
 ![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/531308c7-89f8-4d64-9ae9-dfc4b05f7a30)
 
 You can check the status of the Runner in your GitHub.
 
![image](https://github.com/labiolly37/devops-projects-2024/assets/102201565/70b24d57-5964-4f49-a8ea-d1309a110264)
