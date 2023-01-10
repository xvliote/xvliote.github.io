


1.  创建虚拟环境
```
conda create -n venv python=3.9.5
conda activate venv
```

2.  安装所需库
    - `pip install mkdocs`
    - `pip install mkdocs-material`


3.  创建网站
    - `mkdir xvliote`
    - `cd xvliote`
    - `mkdocs new mysite`

4.  提交

    - 在包含`.yml`的文件中进行`git`操作
    - `git init`  
    - `git add .`
    - `git commit -m "first commit"`
    - `git remote add origin git@github.com:xvliote/xvliote.github.io.git`
    - `git push -u origin main`
    - `mkdocs gh-deploy`

5.  修改提交
    - `git status ` 
    - `git add .`
    - `git commit -m "xxxxx"`
    - `git push -u origin main`
    - `mkdocs gh-deploy`