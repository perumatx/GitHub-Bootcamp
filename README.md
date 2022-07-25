# GitHub-Bootcamp

## Get Started (Davron)

1. Clone the Project

- [**Git Guide**](/git.md)

        git clone https://github.com/davronaliyev/GitHub-Bootcamp.git
        
2. Create new Branch

        git checkout -b yourName

3. Fix the Code

        - Open index.html
        - Then update baseImage.png to your task.png
                src="src/img/baseImage.png">
                src="src/img/task1.png"> 

4. Commit and Push your changes

        git add .
        git commit -m "Task 1 fix"
        git push

5. Create Pull request (from your branch to main branch)


## GitHub Workflows aka Actions (Kumarapillai, Govindaraj)

1.  Actions <br /> 
       actions are event driven ( push, commit, etc) [Events that trigger workflows](https://docs.github.com/en/actions/reference/events-that-trigger-workflows)<br />
       Picture
      ![alt text](https://docs.github.com/assets/cb-25535/images/help/images/overview-actions-simple.png "workflow")
2. Creating your first workflow <br />
      workflows are written in yaml. usually stored in ```./github/workflows``` directory 
      ```yaml
         name: GitHub Actions Demo
             on: [push]
               jobs:
                 job 1:
                   runs-on: on-prem
                     steps:
                       'do something' 
    ```
    
3. Let's Break down <br />

  ````name : GitHub Actions Demo```` Optional - The name of the workflow as it will appear in the Actions tab of the GitHub repository.
 ***            
  ````on: [push]```` Specifies the trigger for this workflow. This example uses the push event, so a workflow run is triggered every time someone pushes a change to the repository or merges a pull request. This is triggered by a push to every branch
 ***
  ````jobs:```` Groups together all the jobs runs in the workflow
 ***
  ````job1```` Job name
 ***
  ````runs-on: on-prem```` Configures the job to run on the on-prem Linux runner. we can also configure to run on multi-platform and dind runners
 ***
  ````steps```` Groups together all the steps that run in the job  
## Advance Workflows & Continuous Integration (Perumal, thiYag)

1.
2.
3.

## Lab 

1.
2.
3.


## Extra Lab 

- https://lab.github.com/githubtraining/github-actions:-continuous-integration

