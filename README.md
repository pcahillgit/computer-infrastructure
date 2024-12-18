# Computer Infrastructure

![UserInterface](https://upload.wikimedia.org/wikipedia/commons/6/6b/Gem_11_Desktop.png)

## About this Notebook
This is my repository for the Computer Infrastructure module assessment. Each task outlined below demonstrates specific competencies in command-line operations, scripting, and data analysis.

| Task | Title | What the Task Involves |
| :--  | :---: |  :---:  |
| 1 | Create Directory Structure | Creating directories and subdirectories on the command line. |
| 2 | Timestamps | Saving multiple dates and times as now.txt using the `date` command. |
| 3 | Formatting Timestamps | Saving another date (this time in YYYYmmdd_HHMMSS format) as formatted.txt . |
| 4 | Create Timestamped Files| Embedding a date command in backticks into a `touch` command to create an empty file in the YYYYmmdd_HHMMSS.txt format. |
| 5 | Download Today's Weather Data | Using the `wget` command to save the latest weather data for the Athenry weather station from Met Eireann. |
| 6 | Timestamp the Data | Modifying the  command from task 5 to save the downloaded file with a timestamped name in the format YYYYmmdd_HHMMSS.json . |
| 7 | Write the Script | Writing a bash script called weather.sh which automates the process from task 6. |
| 8 | Notebook | Recording brief descriptions of the commands used in each task and their role in completing the task. |
| 9 | pandas | Using the pandas function within my Juyter Notebook to load in one of the weather data files made via the script in order to examine and sumarise the data. |

The project component of this module involved setting up a GitHub Actions workflow which runs once daily and executes the weather.sh script. This workflow is the weather-data YAML file in the .github/workflows folder.

## Get Started
I used [Anaconda](https://www.anaconda.com/download) in [Visual Studio Code](https://code.visualstudio.com/download) to create and write the [Jupyter Notebook](https://realpython.com/jupyter-notebook-introduction/) for task 8 which outlines my metodology and reasoning for each task involved in the assessment. I recommend you download and use the same to view the work. Visual Studio Code is a tool which allows the user to view and edit code.

Much of the coding in this particular work was done via Visual Studio Code which runs in GitHub Codespaces (GitHubs cloud based development environment).

## Contribute
Click the badge below, generated from [openincolab.com](https://openincolab.com/) to open the weather.ipynb notebook in [Google Colab](http://colab.research.google.com/):

<a target="_blank" href="https://colab.research.google.com/github/pcahillgit/computer-infrastructure/blob/main/weather.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

## Get Help
Please feel free to log any issues you spot on the Git repository page or to email me with any queries (my student email is included below).

## Author
*Paul Cahill*

## Contact
ATU student email: G00438905@atu.ie