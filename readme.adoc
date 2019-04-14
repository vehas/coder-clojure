this project contain coder with
all clojure development  system

### bulid
docker build -t vehas/coder-clojure .

### run
docker run -it -p 8443:8443 -v "${PWD}:/home/coder/project" vehas/coder-clojure --no-auth  --allow-http
