# Lab 06: Taming data

## Preparation

- Read/ annotate: [Recipe \#6](https://qtalr.com/resources/recipes/recipe-06/). You can refer back to this document to help you at any point during this lab activity.

## Objectives

- Review using data documentation to understand a resource
- Learn to interpret data structure and documentation to plan data curation strategies
- Apply skills and knowledge to use R read, organize, and document data

## Instructions

### Getting started

In this lab, you will be using Git and Github to fork, clone, commit, and push changes to a repository. The repository you will select to use as the repository to fork to your own Github account can be one of the following:

- [Lab 06 repository](https://github.com/qtalr/lab-06)
- [Minimal template](https://github.com/qtalr/project)
- [Web-based project template](https://github.com/qtalr/project_web)
- Other (consult your instructor)

If you are starting with a new repository, fork and clone the repository you selected to your local machine. Then orient yourself to the repository by opening the README file and reviewing the template configuration.

If you are using an existing reproducible research project repository, open that project on your local machine, and `pull` the latest changes from the remote repository to ensure that your local and remote repositories are in sync.

Open a Quarto document in the process directory and name it accordingly (e.g., `2_curate.qmd`, `data_curation.qmd`, *etc.*).

The data you select to curate should be of the unstructured or semi-structured variety and may be one of the following:

- [The ACTIV-ES Corpus (v.02)](https://github.com/francojc/activ-es/tree/master/activ-es-v.02/corpus). Download either the `eagles.zip`, `plain.zip`, or `tagged.zip` versions using the `get_compressed_data()` function from the `qtalrkit` package.
- The data you collected in Lab 05
- Other (consult your instructor)

### Organizing data

In your curation process file,

1. add a section which provides a brief description of the data you are curating. Include:

  - the name and/ or source of the data
  - the nature of the data
  - the acquisition strategy that was used
  - the format of the data

2. add a section which provides a description of the data structure of the resource, outines the relationships between the data elements, and proposes an idealized format for the curated dataset. Include:

  - the relevant directories and data files
  - the metadata and/ or variables to be organized
  - the relationships between the data elements
  - the idealized format for the curated dataset in a tabular format

3. add a section which programmatically reads, organizes, and writes the curated dataset. This is where you will craft the code to curate the data.Include prose and code comments to describe the process of organizing the data.

4. Make sure to organize your data curation process in a way that is reproducible. This means that you should be able to run the code in your data curation process file and reproduce the data curation process. Use the `data/derived` (or similar) directory to store the curated dataset and the data dictionary.

5. Make sure that your code is well documented with code comments and that you have included prose to describe the process of curating the data.

6. Include a section to describe the resulting data and to display the data dictionary you have created for this data as a table.

7. Confirm that your code runs without errors and that the data is curated and displayed as expected.

8. Finally, commit and push your changes to your Github repository. *Make sure to include files or directories that you do not have permission to share in your `.gitignore` file.*

### Assessing your progress

1. In your repository on Github, open an issue to provide feedback on your experience with this lab (Click on the 'Issues' tab and then click the 'New issue' button). Title the issue "Lab 06 feedback" and provide your feedback in the body of the issue.

Some questions to consider:

  - What did you learn?
  - What did you find most/ least challenging?
  - What resources did you consult?
    - Instructor? R or Quarto documentation, Websites (provide links)?
  - What more would you like to know about curating datasets?
    - Find potential resources you might consult to continue your learning. Provide links and a brief description of the resource.

## Submission for feedback

- Provide a link to your GitHub repository

## License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
