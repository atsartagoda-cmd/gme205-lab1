# Project Title

# How to set up the virtual environment

# How to run Python scripts
Run the Python script from the project root using:

python src/hello.py
Edited on GitHub web interface
# Reflection: Computational Thinking Lenses
For abstraction, the exercise focused on inspecting the rows, columns, missing values, coordinate validity, and bounding box because these provide an initial understanding of the dataset's structure, quality, and spatial extent before it is used for further processing or analysis. This made me realize that a computer only follows the instructions given to it, so a person still needs to decide which information is relevant to the task. For representation, the CSV treats each row as a geographic point and assumes that the `lon` and `lat` columns contain numeric longitude and latitude values that are correctly labeled and represented in WGS84. For responsibility, the script can automatically check missing values, invalid coordinate ranges, and other predefined conditions, but human judgment is still necessary to determine whether the coordinates actually make sense for the intended study area. For scale, processing 10 points is simple, but a dataset with 10 million rows could require much more memory and processing time and may also be difficult to visualize efficiently. Therefore, larger datasets may require more efficient approaches to storing, processing, and visualizing the data.
