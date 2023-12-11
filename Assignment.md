# Assignment description 

Now that you have learned the basics of git it is time to apply them to a project. You should sit with your project group, and we will use the Pytorch tutorial application for this assignment.

# Why is this important?

In bigger projects, you need to collaborate and help each other to achieve the goal. They also become complex, so using a Jupyter Notebook for your code will become difficult to maintain. In this example, we would use Python files for the code to make sure you know how to collaborate. 

# Some important mentions before starting

Although you might have read this information, it is important to use some **good practices** when using git so you can understand what each one of you is doing as well as make sure you do not waste your time on some tasks.

- **Meaningful commit messages** are important because through them you tell the other people in your group what you have done through that specific commit name, giving a summary of your work. So, make sure you will provide a concise summary of your update through the commit messages.

- **Constantly pulling/fetching** from the repository allows you to get the latest changes and does not deal with working on obsolete versions that might not be relevant anymore. It is a huge time saver to try to get a habit out of the first step when you start working is to pull the latest changes.

- **Double-Check Your Code After Resolving Merge Conflicts**. Resolving merge conflicts can be tricky and it is important to re-check your code after solving them. This way you ensure that your code is still working as intended after the new changes and that you did not introduce any bug in the system by mistake. For further reference, check the bottom of this for a summary of how to resolve merge conflicts.

- **Branches** allow you to work separately on some task without interfering with each other. In this way, you can iteratively develop your feature and push regularly without interfering with others. Most often when creating a new branch, you should start it from the main since it is the last trusted source that everyone agrees on. Exceptions can happen on a case-by-case basis.

# Example Folder Structure

Below is an overview of the main folders and files in this project:

    project-title/
    │
    │
    ├── data/                   # Directory for all dataset-related stuff
    │   ├── raw/                # Raw, immutable data dump
    │   └── processed/          # Clened, transformed data used for modeling (does not have to be on GitLab)
    │
    ├── models/                 # Trained models
    │
    ├── notebooks/              # Jupyter Notebooks used for prototyping or visualization
    |
    ├── src/                    # Source code files
    │   ├── data/               # Scripts to download, generate, clean preprocess data, feature engineering
    │   ├── models/             # Scripts to train models and predict
    │   └── visualization/      # Visualization scripts e.g. for results interpretation, possibly called by notebooks
    │
    ├── models/                 # Trained 
    │
    ├── requirements.txt        # Required packages and dependencies for reproducibility
    └── README.md               # Project description and instructions


# Task description

You need to port the [Pytorch Application Tutorial](https://interactivetextbooks.citg.tudelft.nl/dsaie/notebooks/0-preliminaries/exercises-clean/Introduction_to_PyTorch_Application.html) to the following folder structure and later on, train it on RunPod.

Divide the work among yourselves, with each person responsible for one task:
- **Person 1**: Data Preprocessing
- **Person 2**: Model Creation
- **Person 3**: Training Loop
- **Person 4**: Normalization
- **Person 5**: Visualization

<p style="font-size:20px;">
    <strong>Follow the instructions for every step carefully. You can only proceed to the next step once everyone in the team has completed the current step.</strong>
</p>

## Steps 

Here are the steps you will need to follow.

1. Someone in the team needs to create a project on [GitLab](https://gitlab.tudelft.nl/) and add all other team members as contributors. You should go to Your profile → Personal projects → Create New Project.

2. Each team member selects a specific task.

3. Review the Jupyter Notebook to determine your specific task and its dependencies.

4. Everyone clones the project repository created before to their local machine.

5. Person 4 adds a template README file to the project and creates a merge request for this addition (and merges when he gets approval from team members).

6. Decide together on the project's structure, dependency management, and how to ensure the code will run in the end.

7. Each member creates the necessary files and writes their code (important note: no merge has happened yet and everyone starts their branch from main/master).

8. You will run the code locally. Ensure the dataset is in your local raw data folder, but excluded from GitLab pushes via `.gitignore`.

9. Each member pushes their code to GitLab and opens a merge request.

10. All members except Person 4 add their names to the README file and split work on the dataset.

11. Starting with Person 1, sequentially review and merge the code to the main branch.

12. After all code is pushed and without fetching new changes, Person 4 adds their name to the README (without branching from the main again, add on top of your old branch) and starts the process of uploading his code.

13. After all steps, continue the process until you manage to make the code running, each one of you uploading just the part you were responsible for. Every change needs to go through the process of creating a merge request, being reviewed by others and then merged.

In this assignment, everyone should have solved a task, created a merge request, and resolved a conflict. As a team, you should be able to run the 

# How to solve merge conflicts

You might notice that sometimes GitLab/Github might not let you merge through your merge request because of conflicts. Here is a quick guide on how to solve them.

1. **Identify the conflicts**. Firstly, you need to know what pieces of the code have conflicts. You can do this by merging your editor with the branch you want to merge your branch into. Then, if you are using Visual Studio code or other IDE the conflicts will be highlighted.

2. **Understanding the conflict**. You have to check where in the code the conflict is and understand what happened. Did you make a change on top of the other, or both changes are needed, or did you make them?

3. **Resolve the conflict** Combine the changes carefully and keep only what is necessary, remove any duplicate or outdated code. Sometimes discussions with your team are needed at this stage

4. **Merge the changes** Once you have re-checked everything and it works fine, merge the resolved code back into the project.

As a final note, resolving conflicts is all about paying attention to the changes and communication if needed. Do not rush solving them and when in doubt, discuss them with your team.