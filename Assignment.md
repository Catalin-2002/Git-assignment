# Assignment description 

Now that you have learned the basics of git it is time to apply them to a project. You should sit with your project group, and we will use the Pytorch tutorial application to get going.

# Why is this important?

In bigger projects, you need to collaborate and help each other to achieve the goal. They also become complex, so using a Jupyter Notebook for your code will become difficult to maintain. In this example, we would use Python files for the code to make sure you know how to collaborate. 

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

You need to port the initial Pytorch application tutorial to the following folder structure and later on train it on RunPod.

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

1. Each team member selects a specific task.

2. Review the Jupyter Notebook to determine your specific task and its dependencies.

2. Everyone clones the project repository to their local machine.

4. Person 4 adds a template README file to the project and creates a merge request for this addition (and merges when he gets approval from team members).

5. Decide together on the project's structure, dependency management, and how to ensure the code will run in the end.

6. Each member creates the necessary files and writes their code (important note: no merge has happened yet and everyone starts their branch from main/master).

7. You will run the code locally. Ensure the dataset is in your local raw data folder, but excluded from GitLab pushes via `.gitignore`.

8. Each member pushes their code to GitLab and opens a merge request.

9. All members except Person 4 add their names to the README file and split work on the dataset.

10. Starting with Person 1, sequentially review and push the code to the main branch.

11. After all code is pushed and without fetching new changes, Person 4 adds their name to the README (without branching from main again, add on top of your old branch) and starts the process for uploading his code.

12. After all steps, continue the process until you manage to make the code running, each one of you uploading just the part you were responsible for. Every change needs to go through the process of creating a merge request, review by others and then merge on.