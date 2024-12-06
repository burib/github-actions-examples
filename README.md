# github-actions-examples

 - [PR workflow](.github/workflows/pr_workflow.yml) ( on PR opened, closed, merged )
 - [Manul Approval Flow](.github/workflows/manual_approval_workflow.yml) ( on manually invoked )

### FAQ:

##### How to create a github workflow where a step needs manual approval ?

step 1. Go to your repo settings / environment ( https://github.com/OWNER/REPO/settings/environments )  
step 2. click on 'create new environment' ( https://github.com/OWNER/REPO/settings/environments/new )  
step 3. type in anything you want to call your environment to, like production or 'this-environment-needs-manual-approval-before-it-runs'
<img width="1016" alt="image" src="https://github.com/user-attachments/assets/e2777f39-86f4-467e-a236-d89d442d01c0">
step 4. once the environment is created, click on it and adjust the settings to match your needs.  
Like 'require approval from'
 <img width="1214" alt="image" src="https://github.com/user-attachments/assets/1abbd191-73e4-4ede-8b6b-4f93040d4a40">
step 5. make sure the created environments name is matching your environment: in the job step.
<img width="555" alt="image" src="https://github.com/user-attachments/assets/735d73a7-ed33-400f-971f-0dca11acab69">  
https://github.com/burib/github-actions-examples/blob/main/.github/workflows/manual_approval_workflow.yml#L19  

step 6. enjoy
<img width="1082" alt="image" src="https://github.com/user-attachments/assets/e27e4e58-fc4e-4d37-b638-cbda5c5cf27c">  
<img width="1079" alt="image" src="https://github.com/user-attachments/assets/824c1e4b-ed86-4ef9-a546-2057b4e05181">  
<img width="1078" alt="image" src="https://github.com/user-attachments/assets/ac9309ab-c508-4b44-8cc0-7a459245e467">  
<img width="1029" alt="image" src="https://github.com/user-attachments/assets/8bb69723-208b-4aa0-bb31-be612d06c9e1">  








