# jupyter_templates
templates for converting jupyter notebooks

Add these templates to 
`~/.jupyter/templates`

Use these templates by running:
`$ jupyter-nbconvert --to python --template my_template my_notebook.ipynb`


## [python_clean](./python_clean.tgz)
Export only python and comments
* remove:
  - markdown cells
  - cell numbers
  - cell output
  - notebook magic (!, %, etc.)
