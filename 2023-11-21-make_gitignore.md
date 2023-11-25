---
layout: post
title: gitignore 파일 만들기
subtitle: Let's try to make gitignore file
gh-repo: devguno/conventional-repo
gh-badge: [star, fork, follow]
tags: [test]
comments: true
author: iamguno
---

{: .box-success}
gitignore 는 대중에 공개해서는 안되는 파일들(올라가면 안되는 파일들 like 비밀번호,,,)을 시스템적으로 걸러주기 위한 파일이다. 



## 생성 방법

[gitignore.io 사이트](https://www.toptal.com/developers/gitignore)에서 편하게 세팅 가능


**옵션 세팅**  
주로 세가지를 세팅한다.(OS, 언어, 에디터)  
무슨 OS 쓰는지.. 무슨 언어 쓰는지... 에디터 어떤거 쓰는지..

![Crepe](https://github.com/devguno/conventional-repo/assets/130540234/9b616b54-447a-4f90-8ec9-c5f52b5dceac)

그 다음 생성(create)를 눌러주면 아래와 같이 text 가 만들어진다.
~~~
# Created by https://www.toptal.com/developers/gitignore/api/macos,windows,linux,python,node,jupyternotebooks,visualstudiocode,vim,pycharm
# Edit at https://www.toptal.com/developers/gitignore?templates=macos,windows,linux,python,node,jupyternotebooks,visualstudiocode,vim,pycharm

### JupyterNotebooks ###
# gitignore template for Jupyter Notebooks
# website: http://jupyter.org/

.ipynb_checkpoints
*/.ipynb_checkpoints/*

# IPython
profile_default/
ipython_config.py

# Remove previous ipynb_checkpoints
#   git rm -r .ipynb_checkpoints/

### Linux ###
*~
~~~

이제 에디터로 돌아가서 gitignore.io에 대한 new file을 생성해준다. 그리고 text 붙여넣기 해주면 `끝`

_vim에서는 vi.gitignore -> i -> cmd+v -> esc -> :wq_
