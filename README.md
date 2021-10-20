# MostStarredGitHubProjects

A simple Python script to create bar charts with the github projects most starred for each of the following languages:
* C
* Javascript
* Java
* Ruby
* Go

By running the main python file, one SVG file is created for each of the programming languages listed, which includes a bar chart with the most starred projects on github for each of these languages. A tooltip is included on every bar with a brief description of each project and a hyperlink which redirects to the URL of the same project. Chart is sorted in descending order.

Libraries used:

* Pygal
* Requests

API calls are done to the github api to obtain the data which is populated into lists and dictionaries, used to populate the plots
