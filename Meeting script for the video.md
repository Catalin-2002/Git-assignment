## Preliminary steps before creating the video
-	Check if whatever we put in the video is sufficiently covered here:  https://mude.citg.tudelft.nl/book/programming/programs/overview.html --> Chapter 3.1 and 3.2 only.
-	Modify ML repo structure template defined here: https://github.com/Catalin-2002/Git-assignment/blob/main/Assignment.md by including .gitignore and removing the extra model directory.



## Storyboard for a Git & GitLab Tutorial Video:

### Suggestions
- Try first everything without recording.
- Once you know it's working, record scene by scene.

### Scene 1: Project Creation
- Visual: TA logs into TU Delft GitLab, showing navigation through the site.
- Voiceover explains going to "Your profile → Personal projects → Create New Project."

### Scene 2: Repository Structuring
- Visual: Demonstration of setting up the repository structure as per guidelines.
- Voiceover explains the importance of a structured repository for project organization.

### Scene 3: Adding Contributors
- Visual: The project creator adds other team members as contributors.
- Voiceover details the steps to add contributors and their roles.

### Scene 4: Cloning the Repository
- Visual: Each team member cloning the repository to their local machine using Git commands.
- Voiceover explains the cloning process and its necessity for local development.

### Scene 5: Task Allocation
- Visual: Members reviewing a Jupyter Notebook (PyTorch application from the book, check the solution), selecting tasks. 
- If there is two TAs, the work can be split in half before and after the “model” part 

### Scene 6: Task Review
- Visual: Close-ups of the notebook, with members identifying their tasks.

### Scene 7: Branching and Coding
- Visual: Each member creating a new branch and starting coding  stress the importance of branches.
- Members copy paste the content of the notebook into .py files with the right dependencies.

### Scene 8: Push and Merge Request
- Visual: Code pushed to GitLab and merge requests opened.
- Voiceover explains pushing code and opening a merge request for integration.

### Scene 9: Code Review and Merge
- Visual: The project leader reviews and merges the code sequentially.
- Voiceover discusses review principles and merging process into the main branch.

### Scene 10: Cleaning Up
- Visual: Members removing merged branches from their local repositories.

### Scenes 11 & 12: Merge Conflict Creation and Resolution [propose others if you think are better]
- **Merge Conflict 1**: Two members modify the same line in a script file.
- Visual: Show the conflicting changes.
- Voiceover explains how such conflicts occur and demonstrates the resolution.
- **Merge Conflict 2**: One member deletes a file that another member has modified.
- Visual: Show the deletion and modification conflict.
- Voiceover walks through the conflict identification and resolution steps.

### Scenes 13: Creation of final Notebook
- After resolving the conflicts, we create a jupyter notebook in the notebook folder where we import all the routines in the .py files (e.g., from src) and run the training.  

### Scenes 14: Cloning the repo on Google Colab [BLENDI]
- Show students how to clone the final repo on Google Colab (e.g., !git clone … in one of the cells). 
- Mention that if they have the google drive attached to their google colab (like shown in some of the notebooks in our course), they can use git and Colab to run the last version in the repo.  
  
### Scenes 14: Cloning the repo on runpod [BLENDI]
- Show students how to clone the final repo on runpod from the terminal that can be accessed from JupyterLab  show this by sharing a link from the pod, they cannot access runpod account by themselves; just show that they can paste the link and the password they will receive. 
-  Show how to upload data in the folder from JupyterLab.
- Open the notebook and run it! 

