# Initial Project Setup Instructions
To create a virtual environment for a Jupyter Notebook project using Windows PowerShell, you can follow these steps:

Open Windows PowerShell:

Press Win + X on your keyboard.
Select "Windows PowerShell" from the menu.
Create a new directory for your project and navigate into it:

```mkdir my_project```
```cd my_project```

Create a virtual environment:
```python -m venv my_env```

Activate the virtual environment:
```.\my_env\Scripts\Activate.ps1```

Install Jupyter Notebook within the virtual environment:
```pip install jupyter```

Start Jupyter Notebook:
```jupyter notebook```

This will launch Jupyter Notebook in your web browser, allowing you to create and work with notebooks within the virtual environment.

Note: When you're done working with your virtual environment, you can deactivate it by running the following command:
```deactivate```

Remember to activate the virtual environment again whenever you want to work on your project in Jupyter Notebook.

### About this dataset:

@misc{willden,
url={http://theconceptcenter.com/simple-research-study-udemy-courses/},
journal={Concept Center},
author={Willden, Chase}}
