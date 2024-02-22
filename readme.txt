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
