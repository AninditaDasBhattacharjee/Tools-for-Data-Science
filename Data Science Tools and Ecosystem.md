<center>
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0105EN-SkillsNetwork/labs/Module2/images/SN_web_lightmode.png" width="300" alt="cognitiveclass.ai logo">
</center>


Data Science Tools and Ecosystem
In this notebook, Data Science Tools and Ecosystem are summarized.

Some of the popular languages that Data Scientists use are: 1.Python 2.Julia 3.R

Some of the commonly used libraries used by Data Scientists include: 1.Numpy 2.Pandas 3.Tensorflow


#### Add your code below following the instructions given in the course



```python
from IPython.display import Markdown, display

# Define the table contents
table = "| Tool | Description |\n| --- | --- |\n| NumPy | Numerical computing library |\n| Pandas | Data manipulation and analysis library |\n| Matplotlib | Data visualization library |\n| Scikit-learn | Machine learning library |\n| TensorFlow | Open-source machine learning platform |\n| Keras | High-level neural networks API |\n| PyTorch | Open-source machine learning library |\n| Seaborn | Data visualization library |\n| SciPy | Scientific computing library |\n| NLTK | Natural language processing library |\n| Statsmodels | Statistical modeling library |"

# Create the Markdown cell
display(Markdown(table))
```


| Tool | Description |
| --- | --- |
| NumPy | Numerical computing library |
| Pandas | Data manipulation and analysis library |
| Matplotlib | Data visualization library |
| Scikit-learn | Machine learning library |
| TensorFlow | Open-source machine learning platform |
| Keras | High-level neural networks API |
| PyTorch | Open-source machine learning library |
| Seaborn | Data visualization library |
| SciPy | Scientific computing library |
| NLTK | Natural language processing library |
| Statsmodels | Statistical modeling library |



```python
from IPython.display import Markdown, display

# Define the Markdown string with the H3 heading
md = "### Below are a few examples of evaluating arithmetic expressions in Python\n"

# Add the Markdown string to the existing Markdown cell
display(Markdown(md))
```


### Below are a few examples of evaluating arithmetic expressions in Python




```python
(5*6)+5
```




    35



# Define the value in minutes
minutes = 120

# Convert minutes to hours
hours = minutes / 60

# Print the result
print(f"{minutes} minutes is equal to {hours} hours")

Author Anindita Das Bhattacharjee
