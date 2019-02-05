# jj4nsw

## Generation instructions

This is a useful tutorial https://www.youtube.com/watch?v=c7vpcqA6SEQ

### 1) Create github repo

### 2) Clone repo to local machine

### 3) Download Hugo
For windows 
https://github.com/gohugoio/hugo/releases

Put the executable in the documents folder (you can add it as path, but who can be bothered)

### 4) Run Hugo to generate site
Inside jj4nsw folder
~~~
C:\Users\james\Documents\hugo.exe new site jj4nsw
~~~

### 5) Move contents of the folder into the parent
i.e. all the files in /jj4nsw/jj4nsw/, move into /jj4nsw/

### 6) Start server to test how it works
~~~
C:\Users\james\Documents\hugo.exe server
~~~

Navigating to http://localhost:1313/ should show a blank page


### 7) Install Casper Two (or other theme)
https://themes.gohugo.io/hugo-casper-two/

~~~
cd themes
git clone https://github.com/eueung/hugo-casper-two.git casper-two
~~~


### 8) Copy sample configuration 
On this page: https://themes.gohugo.io/hugo-casper-two/
into config.toml


### 9) Start server with theme
~~~
C:\Users\james\Documents\hugo.exe server -t casper-two
~~~

### 10) Make the builds end up in /docs
Add a build parameter to config.toml
~~~
publishDir = "docs"
~~~

### 11) Build the site into docs
~~~
C:\Users\james\Documents\hugo.exe -t casper-two
~~~


### 12) Turn on Github Pages support in repository settings

Ensure the page is server out of the /docs folder.




