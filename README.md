# auto-newsletter
Automating the creation of the newsletter.

## Goals
The goal is to create a set of scripts that automatically generates the weekly newsletter based on information from the D-Lab website. The scripts should:
* pull the upcoming training information for the following two weeks
    - title
    - date
    - instructor
    - indicate whether or not registration is full
    - a link directed to the training registration
    - training description
* create a plain text file with the scraped information embedded
* this script will generate the newsletter from the Friday in the current week to the Friday 2 weeks later.
* this script is also capable of fetching all the past archived training with information of title, date and instructor.

## Setup
* One-time setup:
    - Get Python installation package from www.python.org if you don't have Python installed.
    - Go to pip.pypa.io/en/stable/installing/ and follow the instruction to install pip if you don't have pip installed.
* To generate the newsletter:
    - cd into your directory storing the Python file.
    - In the terminal run command 'python newsletter_data.py past_training' to generate all past training.
    - Run command 'python newsletter_data.py current_training' to generate training in the next two weeks.
