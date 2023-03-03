# Git-and-GitHub-final-assignment
This template repository hosts the final Git & GitHub assignment.

## Description
We learnt how to use Git & GitHub to keep records of milestones during  projects. Now, this is time for the final assignment that consists in creating *3 repositories* each having a *minimum of 3 commits* to host some of the previous projects you worked on, during the previous phase of the program and fill the table in the `Recap Table` section.

## Assignment
The following steps constitute your assignment :
1. **Clone this repository** on your local machine; 
1. Configure it as described in the `Setup` section;
1. Select `3` projects, your own ones or projects done during the previous part of the Azubi program ;
1. **Create one public repository** for each project, with a complete and personalized readme file and repository's description ;
1. **Commit** `at least 3 times for each repository` while including simple and clear commit's messages, and **push**;
1. **Fill** the table in the `Recap Table` section with the details of your created repositories.
1. Finally, **commit** with the message `My 3 repositories has been created`, then **push your commit**.

## Recap Table
The below table must contain the details of the repositories you will create, fill it please.


|  | Project's Name | Description    | GitHub's Link  |
|:--:|:--------------:|:--------------:|:--------------:|
| 1 |  -          Sales Prediction   |  - LifeLux Inc, a consumer goods company sells variety products through various retail channels. Over the years, they have invested a lot in television, radio, newspaper advertisement to drive sales and increase brand awareness. The company recently has become concerned about the effectiveness of its advertising spend, as it is becoming difficult to measure the return on investment for each advertising channel. In order to better understand the relationship between advertisement and unit sales, the company has task us to build a model that will effectively predict unit sales based on the amount spent on TV, Radio and newspaper advertisement            | https://github.com/Newton23-nk/Sales-Prediction.git   |
| 2 |  -       Coffe Machine      |  -          You have been hired! Congratulations. Your first task we have been experiencing issues with our coffee machine. Breakdown and theft. We will need you to build a virtual coffee machine that takes coins process it check the resource available for making the coffee and if all checks are successful, it gives you your coffee . The application should prompt the user to make their coffee choice, prompt the user for the coins to be entered and process it. Check to see if the user has sufficient funds, after that check if there are sufficient resources to make the coffee. The program should keep running until the user shut it down.   | https://github.com/Newton23-nk/Coffee-Machine.git  |
| 3 |  -        Password_Generator     |  -          Evergarden produce Ltd is setting up a new online platform for its customers to access their accounts and manage their information. 

Manually creating and assigning passwords for each customer would be a tedious and error-prone process with a customer size 1 million. To automate this process, the company has asked you to develop a program that generate customer password.

The customer should specify the count of letters, symbols and numbers they want in their password. The program randomly mix letters, symbol and numbers to make up the password. Store the password and customer name in a dictionary.   | https://github.com/Newton23-nk/Password_Generator.git      |

**NB**: `Do not modify` the general structure of this table above to avoid issue of evaluation, just fill the rows .

## Setup
Install the required packages to be able to run the evaluation locally.

You need to have [`Python 3`](https://www.python.org/) on your system (**a Python version lower than 3.10**). Then you can clone this repo and being at the repo's `root :: repository_name> ...`  follow the steps below:


- Windows *(Python should be added to the Path variable of environment)*:
        
        python3 -m venv venv; venv\Scripts\activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt  

- Linux & MacOs:
        
        python3 -m venv venv; source venv/bin/activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt

The both long command-lines have a same structure, they pipe multiple commands using the symbol **;** but you may manually execute them one after another.

1. **Create the Python's virtual environment** that isolates the required libraries of the project to avoid conflicts;
2. **Activate the Python's virtual environment** so that the Python kernel & libraries will be those of the isolated environment;
3. **Upgrade Pip, the installed libraries/packages manager** to have the up-to-date version that will work correctly;
4. **Install the required libraries/packages** listed in the `requirements.txt` file so that it will be allow to import them into the python's scripts and notebooks without any issue.

## Evaluation
This evaluation will be automatically grade, so please follow the instructions carefully. 

You can run this command bellow being at the root of the repository to be sure your solutions are the good ones before to push your solutions.
```command
python -m pytest -v
```

If everything is okay, you will have such an output

```terminal
================================================= test session starts =================================================
platform xxx -- Python 3.9.6, pytest-7.2.0, pluggy-1.0.0 -- /xxx/python3
cachedir: .pytest_cache
rootdir: xxx/Git-and-GitHub-final-assignment
collected 3 items                                                                                                     

tests/test_filled_table.py::test_not_empty_table PASSED                                                         [ 33%]
tests/test_filled_table.py::test_not_empty_rows PASSED                                                          [ 66%]
tests/test_readme_table.py::test_contains_table PASSED                                                          [100%]

================================================== 3 passed in 0.000s ==================================================

```
