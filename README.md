# User Controlled Data Science
A fun data science project using configuration in place of hard coding to give a non-technical user limited control of the code.

# Details
Hard coding values in your data pipeline can create some inconveniences later on. With this project I wanted to use a configuration file to control variables and avoid hard coding. This gave me the idea to allow a non-technical person limited control over the code to produce visualizations and perform calculations with zero knowledge of Python other than being able to run the notebook.

# Features
There is a notebook file and a yaml file. The yaml file is where the values are stored for the variables in the program. You may change the values in the yaml file to change the behavior in the notebook.

# How to play with this program
First, you need to be able to run python code on your machine, so be sure you install the necessary packages.

Second, you need to download these files and save them in the same folder on your desktop. I have supplied a folder with the files inside it to make it easier.

Third, open the notebook in your IDE and the yaml file in notepad.

Fourth, run the notebook to see all the outputs.

Fifth, change some values in the yaml file within the given limitations and save the file.

Sixth, run the notebook again to see the difference your changes made. If errors occur, ensure you are using the options I gave you or that the color you chose is supported. It's best to keep it simple with "black", "red", "blue", "pink", etc.

# Benefits
This simple project is a very simple data pipeline displaying how the data moves from the source to the visualization with a flexible program structure. This type of programming allows the data scientist to use a different configuration file with the same code rather than rewrite code. There may be a development stage, testing stage, as well as a production stage each of which require different values; this is where using configuration comes in handy. Same code, different project, very readable.
