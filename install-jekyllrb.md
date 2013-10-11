### Install XCode Command Line Tools

Sign up apple developer, download and install Xcode   
<https://developer.apple.com/>

Open XCode, open `Preferences` (or `Command + ,`),   
Click on `Downloads` panel, `Install` **Command Line Tools**

### Install RVM & Ruby

After Command Line Tools is installed, open `Terminal` app and execute the following commands:

```bash
$ \curl -L https://get.rvm.io | bash -s stable --ruby=1.9.3
``` 

After it's finished, typing in the following commands to see ruby and gem version, if you don't see it, that's mean something is missing

```shell
$ gem -v
# you should see something like 1.8.23
$ ruby -v
# ruby 1.9.3p385 (2013-02-06 revision 39114) [x86_64-darwin12.2.1]
```

### Install Jekyll

```shell
$ gem install jekyll
```

### Run Jekyll Server

I assume your repository (azlrebuild) is on Desktop  

```shell
$ cd ~/Desktop/azlrebuild
$ jekyll serve -w
```


