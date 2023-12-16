# Scenes that need to be filmed 

### 1. Repository creation [Catalin]

Show how to create a repository on GitLab and add the contributors to the repository.

### 2. Split the work into tasks [All of us]

Talk with each other about the parts we are taking and look through the Jupyter notbook files to identify what is part goes into each section


### 3. Create the folder structure [Catalin]

- Show how to create the folder structure accordingly and create the empty files and explain what they roughly do in each of the file
- Create a Merge request with the folder structure and open it for review

### 4. Review the project structure [Someone else than Catalin]

- Add a comment on a mistake that was intentionally created in the project structure and ask Catalin to change it
- Catalin will make the fix, push and then update the MR, which will get approved and merged

### 5. Start working [Person before the model]
- Create a branch with the feature
- Shows adding the data locally, pushing it and shows it is pushed right now; then add to .gitignore and show it is removed (a small .gitignore tutorial)
- Create the code and test it
- Create a Merge request with the changes 

### 6. Continue working [Person after the model]
- Create a branch for the feature
- Create the code
- Get the code done previously by the other person and try out the code

### 7. Merging [Both]
-  The MR are reviewed and merged

### 8. Code updates 1 []
- Create a new feature that will mount the dataset from the drive instead of locally 
- Update the model by adding 1 more hidden layer 
- Rename one of the files 


### 9. Update + Solve conflicts [Catalin]

- Fetch the main branch and create a new branch, the other person rename the same file the other person has renamed but with another name
- MR from step 8 is merged
- Person from step 9 shows how to resolve the conflicts caused by the changes
- Make sure the model checkpoints is deleted from the folder and added to the .gitignore (they should be previously pushed 'by mistake' to show how to revert it)


### 10. Cloning the repo on Google Colab [BLENDI]
- Show students how to clone the final repo on Google Colab (e.g., !git clone … in one of the cells). 
- Mention that if they have the google drive attached to their google colab (like shown in some of the notebooks in our course), they can use git and Colab to run the last version in the repo.  
  
### 11. Cloning the repo on runpod [BLENDI]
- Show students how to clone the final repo on runpod from the terminal that can be accessed from JupyterLab  show this by sharing a link from the pod, they cannot access runpod account by themselves; just show that they can paste the link and the password they will receive. 
-  Show how to upload data in the folder from JupyterLab.
- Open the notebook and run it! 



### Notes:
- At every step there should be a check done: does the system still works properly?

