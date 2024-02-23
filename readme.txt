https://forum.freecodecamp.org/t/building-a-node-js-application-using-docker/463269
https://stackoverflow.com/questions/26595874/heroku-src-refspec-master-does-not-match-any


heroku cli wants NODE 16
 1  ls
    2  sudo apt-get update
    3  sudo apt-get install -y ca-certificates curl gnupg
    4  sudo mkdir -p /etc/apt/keyrings
    5  curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
    6  NODE_MAJOR=16
    7  echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_$NODE_MAJOR.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list
    8  sudo apt-get update
    9  sudo apt-get install nodejs -y
   10  node -v
   11  curl https://cli-assets.heroku.com/install-ubuntu.sh | sh
   12  sudo npm install -g heroku
   13  sudo npm install -g heroku --force
   14  history












    1  ls
    2  sudo apt-get update
    3  sudo apt-get install -y ca-certificates curl gnupg
    4  sudo mkdir -p /etc/apt/keyrings
    5  curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
    6  NODE_MAJOR=16
    7  echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_$NODE_MAJOR.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list

    8  sudo apt-get update
    9  sudo apt-get install nodejs -y
   10  node -v
   11  curl https://cli-assets.heroku.com/install-ubuntu.sh | sh
   12  sudo npm install -g heroku
   13  sudo npm install -g heroku --force
   14  history
   15  heroku --version
   16  heroku login -i
   17  vi Dockerfile
   18  npm install express --save
   19  ls
   20  vi app.js
   21  node app.js
   22  vi Dockerfile
   23  vi .dockerignore
   24  ls




 25  docker build -t alfred .
   26  sudo snap install docker
   27  docker build -t alfred .
   28  sudo docker build -t alfred .
   29  vi Dockerfile
   30  sudo docker build -t alfred .
   31  ls
   32  mkdir alfred
   33  cp app.js alfred
   34  cp Dockerfile alfred
   35  cd alfred
   36  sudo docker build -t alfred .
   37  ls
   38  cd ..
   39  l
   40  ls
   41  ls -a
   42  cp .dockerignore alfred
   43  cp package.json alfred
   44  cd alfred
   45  sudo docker build -t alfred .
   46  sudo docker run -p 8080:8080  -tid alfred
   47  history


















1  git
    2  curl https://cli-assets.heroku.com/install.sh | sh
    3  curl https://cli-assets.heroku.com/install-ubuntu.sh | sh
    4  npm install -g heroku
    5  sudo apt install npm
    6  heroku --version
    7  heroku login -i
    8  history


ubuntu@ip-172-31-35-120:~$ heroku login -i
heroku: Enter your login credentials
Email: dalfredostrowski@gmail.com
Password: ****************
 ›   Error: Your account has MFA enabled; API requests using basic
 ›   authentication with email and password are not supported. Please generate
 ›   an authorization token for API access.
 ›
 ›   Error ID: vaas_enrolled



  1  git
    2  curl https://cli-assets.heroku.com/install.sh | sh
    3  curl https://cli-assets.heroku.com/install-ubuntu.sh | sh
    4  npm install -g heroku
    5  sudo apt install npm
    6  heroku --version
    7  heroku login -i
    8  history
    9  npm i express
   10  ls
   11  sudo apt-get install -y ca-certificates curl gnupg
   12  sudo mkdir -p /etc/apt/keyrings
   13  curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
   14  NODE_MAJOR=20
   15  echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_$NODE_MAJOR.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list
   16  sudo apt-get update
   17  sudo apt-get install nodejs -y
   18  node -v
   19  ls
   20  vi Dockerfile
   21  npm init -y
   22  sudo apt-get update
   23  npm
   24  sudo apt-get install nodejs -y
   25  history
