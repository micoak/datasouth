## python

### jupyter notebooks and conda kernels
- from [jvdp pythonic perambulations](http://jakevdp.github.io/blog/2017/12/05/installing-python-packages-from-jupyter/)

`source activate myenv`

`python -m ipykernel install --user --name myenv --display-name "Python (myenv)"`

### yaml docs

from ansible yaml [basics](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html)

### markdown docs

[markdown cheetsheets](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

#### solution for lab and notebook

- option 1 
```python
from IPython.display import Markdown as md
# Instead of setting the cell to Markdown, create Markdown from withnin a code cell!
# We can just use python variable replacement syntax to make the text dynamic
n = 10
md("The data consists of {n} observations. Bla, Bla, ....")
```

- option 2 use magics

```%%html
<div class="topnav" id="myTopnav">
  <a href="#home" class="active">Home</a>
  <a href="#news">News</a>
  <a href="#contact">Contact</a>
  <a href="#about">About</a>
  <a href="javascript:void(0);" class="icon" onclick="myFunction()">
    <i class="fa fa-bars"></i>
  </a>
</div>
```
code from w3schools

#### displaying a website

```python
from IPython.display import IFrame
IFrame(src="https://michaeloak.org.za", width='100%', height='500px')
```

## ruby

which ruby and which jekyll version to use. not sure. 
I use [rbenv](https://github.com/rbenv/rbenv) to manage ruby version. has worked seamlessly so far. 

going to use ruby 2.7.0 to keep consistent with other projects.

### Jekyll

see [websites](/websites/)