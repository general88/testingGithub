

### Exercise 4 -- Data part

A file named

    weather_2023-01.csv

contains hourly weather observations from Jyväskylä, Finland.

| Abbreviation | Meaning |
| --- | --- |
| TA | Temperature Average |
| RH | Relative Humidity |
| WS | Wind Speed |
| WD | Wind Direction |
| PRA | Precipitation Amount |
| PRI | Precipitation Intensity |
| PA | Pressure Average |
| WAWA | Most Significant Weather Code |

Some of the data has been encrypted with your GPG public key. Ignoring any NaN values, find out what percentage of the hourly temperature observations satisfy the following:

> The difference between the maximum and minimum temperature is within 0.8 standard deviations away from the total average of the differences between the maximum and minimum temperatures.

Please write your answer (number only) in the file

    exrc-04-answer.txt

Please also write a separate report (Jupyter notebook) about solving Exercise 4 in the file

    exrc-04-report.ipynb

This report should contain (e.g.)

- code snippets used
- AI prompts used
- links to external material used
- your general thoughts about the process (e.g. difficulty level)
- some more specific thoughts (e.g. strategies that were tried but abandoned).

We will download your answers from this GitLab repository right after the deadline.

