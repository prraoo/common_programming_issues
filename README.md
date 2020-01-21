# Common Issues
Solutions that are not usually available on stackoverflow.

## Python
### 1. Import error:

The exsisting folder is not recognised as module for import.

<em>Solution:</em>

`import sys`                                          #for path to external scripts<br />
`sys.path.insert(0, '/home/JackGrimm/mysite')`        #path to my scripts<br />
`from mypackage.module import foo`                     #importing scripts and giving a local name<br />
