# Applied Statistics

![AS](./img/vecteezy_person-draws-line-graph-using-blue-colored-pencil-amongst_69119759.jpg)

This repository contains the assessment task for the **Applied Statistic** module of the ATU Higher Diploma in Science in Computing in Data Analytics course.
***
## Repository Contents and Description

```
/applied-statistics
├── img/                # directory containing image files used in the repository
├── .gitignore          # lists files and directories that should be excluded
├── README.md           # provides an overview of the repository
├── problems.ipynb      # Jupyter Notebook containing solutions for each problem and the final project
└── requirements.txt    # contains Python dependencies and libraries required to run the code in the repository
```

## Get Started

To get started with this repository, you will need to download the necessary software/applications if you don't already 
have them:
- **[Anaconda](https://www.anaconda.com/)** - A platform used for developing and sharing machine learning and data 
science projects. It is an open-source distribution of the Python and R programming languages. The modules required for 
this project are Pandas and Matplotlib.

- **[Visual Studio Code](https://visualstudio.microsoft.com/downloads/)** - An integrated development environment (IDE) 
designed by Microsoft for writing, editing, debugging, and building code.

- **[GitHub](https://github.com/)** - A cloud-based platform that allows developers to store, manage, and share their 
code. Git is a free, open-source version control system used by GitHub to track changes in both small and large projects.

## Running this Repository

This repository can be **run locally** on your machine or using **GitHub Codespaces**.

### Running Locally

To run the repository locally, you will need Anaconda and Visual Studio Code installed as described above. 
Then follow the steps below:

- Clone repository: 
  `https://github.com/UWASIKLK/applied-statistics`

- Instal dependencies: 
  `pip install -r requirements.txt`

- Open the `problems.ipynb` file in `Visual Studio Code` and run the notebook.

### GitHub Codespaces

GitHub Codespaces is a cloud-based development environment that allows a user to code from any device with internet 
access. To start using codespaces, you'll need to have a personal GitHub account, which has a monthly quota of free use 
of GitHub code 
spaces. The codespace can be created directly from your GitHub repository or you can select an existing template. 

### Create GitHub Codespaces:

-	Clone the repository by using following link: `https://github.com/UWASIKLK/applied-statistics`
-	Navigate to your GitHub repository
-	Click on the green `<>Code` button on the right top side
-	Select `Create codespace on main`

![Codespaces](./img/Codespaces.png)

The contents of your repository will immediately load into the online version of Visual Studio Code in your browser, and 
you can start writing your code. It will have all the tools that Visual Studio Code provides. 

More information can be found on: **[GitHub Docs](https://docs.github.com/en/codespaces/overview)**

## Assessment Problems Summary

### Problem 1: Extending the Lady Tasting Tea

Let's extend the Lady Tasting Tea experiment as follows.
The original experiment has 8 cups: 4 tea-first and 4 milk-first.
Suppose we prepare 12 cups: 8 tea-first and 4 milk-first.
A participant claims they can tell which was poured first.  

Simulate this experiment using `numpy` by randomly shuffling the cups many times and calculating the probability of the 
participant correctly identifying all cups by chance.
Compare your result with the original 8-cup experiment.  

In your notebook, explain your simulation process clearly, report and interpret the estimated probability, and discuss 
whether, based on this probability, you would consider extending or relaxing the p-value threshold compared to the 
original design.  

### Problem 2: Normal Distribution

Generate 100,000 samples of size 10 from the standard normal distribution.
For each sample, compute the standard deviation with `ddof=1` (sample SD) and with `ddof=0` (population SD).
Plot histograms of both sets of values on the same axes with transparency.
Describe the differences you see.
Explain how you expect these differences to change if the sample size is increased.

### Problem 3: t-Tests

A type II error occurs when a test fails to reject the null hypothesis even though it is false.
For each mean difference $d = 0, 0.1, 0.2, \dots, 1.0$, repeat the following simulation 1,000 times:

1. Draw two samples of size 100, one from the standard normal distribution and one from the normal distribution with mean 
$d$ and standard deviation 1.
2. Run an independent samples t-test on the two samples, rejecting the null hypothesis if the p-value is less than 0.05.
3. Record the proportion of times the null hypothesis is not rejected.

Plot this proportion against $d$, and explain how the type II error rate changes as the difference in means increases.

### Problem 4: ANOVA

Generate three independent samples, each of size 30, from normal distributions with means 0, 0.5, and 1, each with 
standard deviation 1.

1. Perform a one-way ANOVA to test whether all three means are equal.
2. Perform three independent two-sample t-tests: samples 1 vs 2, 1 vs 3, and 2 vs 3.
3. Compare the conclusions.

Write a short note on why ANOVA is preferred over running several t-tests.

## Getting Help

If you have any difficulties or questions, please feel free to contact me.

## Contribute

Any contributions are more than welcome. Feel free to clone the repository if you want 
to make any changes or improvements.

## Author

Katarina Siklodyova, student at Atlantic Technological University (2024 -2025)