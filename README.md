# gh-gitignore

![screencast](https://user-images.githubusercontent.com/23115742/151840105-0420874b-f448-4030-8552-1d9746188cc5.svg)
  GITHUB-CLI EXTENSION **gitignore**
  Allow you to download to `pwd` a gitignore template from web.
  You can use your own custom source  invoke with ```-s```  option, 
  without option the default repo [github/gitignore](https://github.com/github/gitignore) will be used as template source.


## Prerequsites 
bash script depends on:
  -  ```gh ``` [github cli version >=2](https://cli.github.com/) 
  -  ```jq ``` [command-line tool jq](https://stedolan.github.io/jq/)
  -  ```curl```[command-line tool curl](https://curl.se/download.html) 


## Usage

  - ```bash gh extension install tst32/gh-gitignore```
  - ```gh gitignore -h ``` show help
  - ```gh gitignore node ``` download template and save it as .gitignore from https://github.com/github/gitignore/node.gitignore
  - ```gh gitignore -s mygitacc/myrepo myownfile ``` download template and save it as .gitignore from https://github.com/mygitacc/myrepo/myownfile  
