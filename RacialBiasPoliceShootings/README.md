# Racial Bias in Police Shootings

Here, I try to reproduce [ctross](https://github.com/ctross)'s
[article](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0141854)
in a Jupyter notebook. The data and scripts are freely available in
the SI from his article, but don't seem to be preproduced on his
github site. I want to clarify that I'm just trying to follow along;
mistakes are mine, smart stuff is his.

## Installation

I had some trouble getting everything to work with my default Python
environment (in particular, getting the rpy2 extension to work). Doing
this worked:

```shell
conda create -n rpy -c r r-essentials rpy2 matplotlib scipy numpy pandas pystan seaborn jupyter python=3
conda remove --name rpy --all
conda create -n rpy -c r r-essentials rpy2 jupyter python=3
```


