# Assessment Brief

**Principles of Data Analytics, Summer 25/26**

This assessment is an opportunity for you to demonstrate achievement of the module learning outcomes.
The primary focus of this assessment is to complete the problems in the [Problems](#problems) section of this document.
Start by making a new GitHub repository solely for this assessment.
Create a new Jupyter notebook named `problems.ipynb` in the root of the repository.
Submit the repository URL using the link below before the given URL submission date.
You should then work consistently on your repository until the final deadline for commits below.
The last commit pushed to GitHub on or before the deadline will be assessed.

> [!IMPORTANT]
> [Submit Your Repository URL Here by 20 February 2026 (ATU Login required)](https://forms.cloud.microsoft/e/hGx0Qw330p)  
> 
> Final Deadline for Commits:  
> <ins>**01 May 2026**</ins>  

Always keep your latest work in GitHub.
If you have problems, especially with git, ask for help well before the deadline.
Do not delete your repository without consulting the lecturer.
Disproportionately large commits, especially late in the semester, will usually not be accepted.
Make sure to consult and adhere to the policies on the student portal, such as those relating to student conduct and plagiarism.

## Target Audience

Complete the assessment with the following target audience in mind: an informed computing professional, such as a prospective employer.
Assume they have a strong background in computing but may not be familiar with the specific language, packages, or tools you use.
They should be able to clone your repository and run any code within it with minimal setup and without any extra help from you.
Include setup instructions in your `README.md`, and keep all necessary data files and images cleanly organized.
If any files are too large to include in your repository, explain this in your `README.md` and, where possible, provide code to automatically download them.

## Organization and Structure

Your submission should be in the `main` branch of your repository.
Include a clear [`README.md`](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes), a suitable [`.gitignore` file](https://www.toptal.com/developers/gitignore), and an [accurate `requirements.txt` file](https://realpython.com/what-is-pip/#using-requirements-files).
Avoid including [unnecessary files or folders](https://realpython.com/python-git-github-intro/#what-not-to-add-to-a-git-repo).
Use lowercase file and folder names, except for the usual files like `README.md`.
Do not use spaces or special characters in filenames.
Underscores, hyphens, and full stops are okay.

Your commit history should show how your work evolved: improvements, refinements, and added clarity.
Keep your notebook [reproducible, clean, and concise.](https://arxiv.org/pdf/2202.07233)
Use a [level 1 heading](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings) for the notebook title.
Use [level 2 Markdown headings](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#headings) to clearly identify each problem within the notebook.
Use Markdown cells to give explanations and insights into your code.

Follow Python coding standards and guidelines such as [PEP8](https://peps.python.org/pep-0008/).
Write clean, readable, and efficient code using meaningful variable names and consistent formatting.
Break code into smaller, manageable cells whenever possible.
Each code cell should focus on a single step in your overall solution.
Include [meaningful comments](https://realpython.com/python-comments-guide/) and [docstrings](https://peps.python.org/pep-0008/#documentation-strings) in your code.
You can use [modules in the standard library](https://en.wikipedia.org/wiki/Standard_library) and any of the packages in the [requirements.txt file in this repository](./requirements.txt) and their dependencies.
Ask before using anything else.

## Submission Checklist

- [ ] **Repository Link Submitted:** You have submitted your GitHub repository URL in the format `https://github.com/username/reponame` via the Microsoft Forms link above.

- [ ] **Correct Notebook Name:** Your primary submission file is located in the root of the repository and is named exactly `problems.ipynb` (all lowercase, no spaces).

- [ ] **Essential Files:** Your repository includes a `.gitignore`, a `README.md` with setup instructions, and a `requirements.txt` listing all necessary Python packages (e.g., `numpy`).

- [ ] **Notebook Cell Order:** You have restarted the kernel and run all cells in your notebook to ensure they execute in sequential order (1, 2, 3...) without errors, providing a clean and reproducible output.

- [ ] **Folder Organization:** Any extra files are organized into subfolders; specifically, any datasets are in a `/data` folder and any images, plots, or diagrams are in an `/img` folder.

- [ ] **Repository Tidiness:** You have removed all irrelevant files (e.g., `.DS_Store`, `__pycache__`, local checkpoints, or temporary scratchpads).

- [ ] **Environment Reproducibility:** When someone clones your repo, they will likely use the following workflow. Ensure your `README.md` and `requirements.txt` make this process seamless:

    1. `git clone <repo-url>`
    2. `pip install -r requirements.txt`
    3. `jupyter notebook problems.ipynb`

## Marking Scheme

Your submission will be assessed across the following five equally-weighted categories.
Make sure you provide clear evidence within your repository of the criteria listed.
A good submission will meet most of the criteria in each category.
An excellent submission will demonstrably meet all the criteria.
Note that the overall impression your submission makes may influence marks in each category.

### Presentation

- Your repository should be well-organized, with a clear and logical structure.
- Your `README.md` should clearly explain the purpose of your repository and how to run any code it contains.
- Your notebook should present a clear narrative, making it easy to follow your thought process.
- A knowledgeable expert reviewing your repository should be able to understand its contents without your help.

### Research

- Your submission should demonstrate research on relevant topics, showing an understanding of the material.
- You should build upon existing literature and documentation rather than just presenting basic solutions.
- References and comparisons to similar work should be included.
- References should be put into context - how and why they are relevant to your submission.

### Documentation

- Your repository should contain standard files, such as a `README.md`, to provide context for your work.
- All concepts should be clearly and concisely explained within your notebooks.
- Code should include informative comments that clarify its purpose and functionality.
- Your `README.md` and notebook should have clear headings and provide a clear context as to what is contained within.

### Development

- Your code should be efficient and well-structured, effectively addressing the problem at hand.
- Standard programming structures, algorithms, and testing methods should be applied where appropriate.
- The overall architecture of your code should be clean, demonstrating good coding practices.
- Your code should demonstrate your knowledge of established style conventions and norms.

### Consistency

- Each commit should focus clearly on a single unit of work.
- Your commit history should show consistent activity across the semester, not a burst of late submissions.
- Your repository should demonstrate incremental review and refinement rather than one-off completion.
- Commits should capture improvements to both code quality and explanations over time.

## Problems

Complete all problems below in your `problems.ipynb` notebook.

Your notebook should tell a story, using Markdown cells to explain your thinking and code cells to perform the technical tasks.

### Problem 1: Creating Your Repository

On [github.com](https://github.com), create a new repository for this assessment.

- Repository Name: Choose a meaningful, lowercase name (e.g., `principles-of-data-analytics-problems`).
- Initialize: Select the option to Add a README file and select Python from the Add .gitignore dropdown menu.
- Submission: Copy your repository URL (e.g., `https://github.com/username/reponame`) and submit it via the official module submission form above.

### Problem 2: The README.md

Open your repository in Visual Studio Code (or whatever way you prefer).
Edit the `README.md` file to include:

- A Level 1 heading with the project title.
- A brief description of the repository's purpose.
- A Level 2 heading for Contents followed by a list of the problems you will solve.

Save your changes, commit them with a meaningful message (e.g., Initialize README), and push/sync them to GitHub.

### Problem 3: gitignore

While GitHub provides a basic `.gitignore`, professional projects often require more detail to prevent temporary or other unnecessary files being added to your repository.

- Go to [Toptal's gitignore.io website](https://www.toptal.com/developers/gitignore) and generate a comprehensive `.gitignore` file for Python, Visual Studio Code, and Jupyter Notebooks.
- Replace the contents of the `.gitignore` in your repository with this generated text.

Save, commit, and push these changes.

### Problem 4: The Notebook

In the root of your repository, create a new file named `problems.ipynb`.

- Add a Markdown cell at the top with a Level 1 heading title for the notebook.
- Add a Code cell to import the necessary libraries: `pandas`, `numpy`, and `matplotlib.pyplot`.
- Add another Markdown cell explaining what these libraries do in the context of data analytics.

Save, commit, and push your notebook.

### Problem 5: The Penguins

For the remaining problems, you will use the Palmer Penguins dataset.

- In your notebook, add a Level 2 heading for Problem 5.
- Search for the raw URL of the `penguins.csv` file (e.g., from this repository or a reputable GitHub source) and use `pandas` to load it into a DataFrame.
- Use the `describe()` method to calculate descriptive statistics for the numeric variables (bill length, bill depth, flipper length, and body mass).
- In a Markdown cell, explain what information the `mean`, `std`, and `quartiles` (or `percentiles`) provide about the penguin populations.

Save, commit, and push your notebook.

### Problem 6: Visualizing Distributions

Select one numeric variable from the dataset.

- In your notebook, add a Level 2 heading for Problem 6.
- Create a Histogram of this variable to show its distribution.
- Create a Box Plot of the same variable to identify the median and potential outliers.
- In a Markdown cell, compare these two plots. What does the box plot tell you that the histogram does not?

Save, commit, and push your notebook.

### Problem 7: Investigating Relationships

Do larger penguins have longer bills?

- In your notebook, add a Level 2 heading for Problem 7.
- Create a Scatter Plot comparing `body_mass_g` (X-axis) and `bill_length_mm` (Y-axis).
- Use the `species` column to colour-code the dots, allowing you to see if the relationship differs between Adelie, Chinstrap, and Gentoo penguins.
- In a Markdown cell, describe any trends or patterns you observe in the plot.

Save, commit, and push your notebook.

### Problem 8: Modelling the Data

Finalize your analysis by fitting a straight line to the data.

- In your notebook, add a Level 2 heading for Problem 8.
- Use `numpy.polyfit` to find the best-fit straight line for the relationship between body mass and bill length.
- Calculate the R-squared value to evaluate how well this line fits the data.
- Plot the best-fit line on top of a scatter plot of the two variables.
- In a final Markdown cell, interpret the R-squared value: Does body mass accurately predict a penguin's bill length?

Save, commit, and push your notebook.

***

**End**
