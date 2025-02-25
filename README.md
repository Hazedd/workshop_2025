# install python 3.10 using scoop

https://scoop.sh/


1. Open powershell en set set policy

```batch
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```
 
2. Install scoop in powershell 

```batch
scoop install python
```

3. Check python version in powershell

```batch
python --version
``` 


# Install dependencies

```batch
pip install requirements.txt
```

# start juptter
```batch
jupyter lab
```