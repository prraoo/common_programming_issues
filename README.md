# Common Issues
Solutions that are not usually available on stackoverflow.

## Python
### 1. Import error:

The exsisting folder is not recognised as module for import.

<em>Solution:</em>

```python
import sys                                          #for path to external scripts<br />
sys.path.insert(0, '/my/program/path')        #path to my scripts<br />
from mypackage.module import foo                  #importing scripts and giving a local name<br />
```   
## Git
### 1. git push (ssh way):
Use 
```bash
$ git remote add origin git@github.com:username/new_repo
$ git push -u origin master`
 ```
rather than 
```bash 
$ git remote add origin https://github.com/username/new_repo
```
The former is for use with ssh (ssh setup) and you won’t have to type your password every time you push things to github. If you use the latter construction, you’ll have to type your github password every time you push to github.
