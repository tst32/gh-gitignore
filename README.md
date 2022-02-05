# gh-gitignore

![screencast](https://user-images.githubusercontent.com/23115742/151840105-0420874b-f448-4030-8552-1d9746188cc5.svg)
###  GITHUB-CLI EXTENSION for manage **.gitignore**

  Allow you to download to `pwd` a gitignore template from web.
  You can use your own custom source, or download template from  
  oficial default repo [github/gitignore](https://github.com/github/gitignore)


## Prerequsites 
tools depends on:

  -  ```gh ``` [github cli version >=2](https://cli.github.com/) 
  -  ```jq ``` [command-line tool jq](https://stedolan.github.io/jq/)
  -  ```curl```[command-line tool curl](https://curl.se/download.html) 


## Install
### with these terminal commands 

linux flavor - ```bash gh extension install tst32/gh-gitignore```
windows way  - ```gh extension install tst32/gh-gitignore```
more options - ```gh extension --help```

## Usage

  - ```gh gitignore -h --help``` show help for more examples of use
  - ```gh gitignore node ``` download template and save it as .gitignore from https://github.com/github/gitignore/node.gitignore
  - ```gh gitignore -s mygitacc/myrepo myownfile ``` download template
       and save it as .gitignore from https://github.com/mygitacc/myrepo/myownfile  
