this project contain coder with
all clojure development  system

#  component
1. java
2. clojure cli
3. lein
4. shadow-cljs
5. codercom
6. with extensions calva
7. and parinfer


#  used 

### go to your directory
- if you don't have clojure code before then you can use this in any directory
### run
docker run -it -p 8443:8443 -v "${PWD}:/home/coder/project" vehas/coder-clojure --no-auth  --allow-http

### and go to  http://localhast:8443
- you will see  codercom start, It's look as same as vs code and it's also include  calva and parinfer
### click terminal > new terminal to make new one
- if you just start with clojure you can type `lein new app` to make new clojure app then  `lein repl`
- or  if you familiar with clojure you can just type `lein repl` or `shadow-cljs run watch`
### then connect calva with repl by type short key `cmd+shift+p` to open vs code navigator then type `calva: Connect `
- you should be able to use clojure with repl now, ping me if you have any problem



# development

### bulid
docker build -t vehas/coder-clojure .
