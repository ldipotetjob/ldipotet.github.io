installing hugo themes:
ref: https://gohugo.io/getting-started/installing/#binary-cross-platform
     https://gohugo.io/getting-started/installing/#step-2-download-the-tarball

download any hugo release(as possible the last one: https://github.com/gohugoio/hugo/releases):

- example: osx : hugo_0.55.6_macOS-64bit.tar.gz

save binary file at:
/usr/local/bin


- create in your github repository: ldipotetjob/ldipotetjob.github.io
- create a repo where should be the info that you want to include in your hugo blog (nomorethanonehundredandsixtysix)
- create directory with the same name (mkdir nomorethanonehundredandsixtysix)
- go to nomorethanonehundredandsixtysix directory (cd nomorethanonehundredandsixtysix)
- hugo statetement: hugo new site .
- git init
- git remote add origin https://github.com/ldipotetjob/nomorethanonehundredandsixtysix.git
- git pull origin master
- echo "public/" >> .gitignore
- git add .
- git commit -m "initial commit"
- git push origin master
- cd nomorethanonehundredandsixtysix/themes [https://gohugo.io/themes/installing-and-using-themes/]
- git clone https://github.com/Track3/hermit.git
- cd ..
- vim confi..... add sample site ( vi config.toml + edit base url + other customized info + css if needed[not in my   case] )
- recommend create directory named as your github page and then ==>
- hugo -d ../ldipotet.github.io/

===================================
            
MBP-de-Luis:nomorethanonehundredandsixtysix ldipotet$ hugo -d ../ldipotet.github.io/

                   | EN  
+------------------+----+
  Pages            | 33  
  Paginator pages  |  0  
  Non-page files   |  0  
  Static files     | 10  
  Processed images |  0  
  Aliases          |  0  
  Sitemaps         |  1  
  Cleaned          |  0  

Total in 84 ms

===================================

- cd ../ldipotet.github.io/
- git add --all
- git commit -m "initial commit"
- git pull origin master 

======= modification & refactoring proccess =====
- modify nomorethanonehundredandsixtysixtyline/conf.toml with the url of your site (in case that you want blogs in different environments)
- each modification first in your local env then ==> hugo -d ../ldipotet.github.io/
- git pull from your working directory onto your repo ==> ../ldipotet.github.io/
- all commit proccess and upload to your github page.

