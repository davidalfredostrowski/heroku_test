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



