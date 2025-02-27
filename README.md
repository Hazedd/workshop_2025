# Install python and dependencies

## python 3.x using scoop https://scoop.sh/

1. Open powershell en set set policy

```batch
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
 
2. Install scoop in powershell 

```batch
scoop install python
```

If installed you should update from time to time:

```batch
scoop update python
```


3. Check python version in powershell

```batch
python --version
``` 

## Get it running

1. Download repo from https://github.com/Hazedd/workshop_2025, on top left there is a code dropdown button, click it and hit download zip.
2. Unpack content to folder then open powershell in that folder (shift + right click shows a menu option "open powershell" if no file is selected)
3. Install dependencies whit:

```batch
pip install requirements.txt
```

✅ now yr set to go.


# Jupyter notebooks

There are predefined notebooks where you can adjust parameters and run the code to get default output.

We can reuse them for generating output.


## Fist we need to start jupyter whit:

Start jupyter
```batch
jupyter lab
```
Jupyter lab is web browser where we can run code.


# Then open a notebook
1. On the left side there is a filebrowser, navigate to the `/jupyter-notebooks/` folder.
2. For now there is one example `SingleImxFile.ipynb`, double click to open the notebook
3. The content of the notebook will be shown in the main part of the website.
4. This is the start point of the workshop.


