<h1>First Machine Learning Project</h1>

<h3>Built with Python and Jupyter</h3>

•	Jupyter tends to be the best code writing editor for machine learning. AI engineers don’t use VS code because VS code and other similar editors don’t have the capability of analyzing the data properly. Use Anaconda to install Jupyter

•	Ensure you have Jupyter, Anaconda, Scikit-Learn installed. You may need to use the following install prompts in your terminal:

**o	pip install jupyter
o	pip install pandas
o	 pip install scikit-learn**

<h3>Steps:</h3>

1.	 **Import the data** (often a .csv file)
	Use the Jupyter local host http://localhost:8888/notebooks/HelloWorld.ipynb.
Use the following as a template:
import pands as pd
pd.read_csv(‘music.csv’)

2.	**Clean the data** (ie. Remove duplicates, etc). You don’t want to feed bad data to your model.
Example, show only data you want to see using:
import pandas as pd
music_data = pd.read_csv('music.csv')
X = music_data.drop(columns=['genre'])
y = music_data['genre']
y

3.	**Split the data **into training (80%) / test sets (20%)

4.	**Create a model**. Select an algorithm to analyze the data (i.e decision trees, neural networks, etc). Each algorithm has pros and cons in terms of the problems you are trying to solve.
Example: using a Decision Tree model from the Scikit-Learn library

5.	**Find a library** (aka input data) to help you solve your problems (i.e Numby, Pandas, MatPlotLib, c etc)
   
6.	**Train the model** (feed it your training data). Training a model can take a long time with large datasets which is while model persistence is important.

7.	Ask the model to **make predictions**. It will be very likely that the predictions will be wrong at the beginning.
   
8.	**Evaluate and improve**. Either select a new model type, library, or fine tune parameters within the algorithm.


Tutorial here: https://youtu.be/_uQrJ0TkZlc?feature=shared&t=15023
