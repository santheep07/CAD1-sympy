# CAD1 - Sympy lectures

This is a git repo

Firs thing: 

* Create a github account 

* Fork this repo

* clone the repo from your own github accout 
```
	git clone your_repo_address

```
* check your remote, you should have only one remote origin with your personal username 
```
	git remote -v
```
* add upstream remote using this address `https://github.com/ViBOT-Erasmus/CAD1-sympy.git`
```
	git remote add upstream https://github.com/ViBOT-Erasmus/CAD1-sympy.git

``` 

##IMPORTANT 
#### End of each session 
add and commit your changes using:

* adding :
```
	git add --all
```
	or 
```
	git add new_file.ipynb
```

* commit your changes : 

```
	git commit -am 'your message'

```
#### Begining of each session 
Update the remotes to get the new materials 

```
	git remote update 

```
In case there is updates from origin 

```
	git rebase origin/master

```
In case there is updates from upstream 

```
	git rebase upstream/master

```