https://devcenter.heroku.com/articles/getting-started-with-python
don't install windows heroku CLI, use instead:
$ curl https://cli-assets.heroku.com/install.sh | sh

fix installation of python and postgres
$ sudo apt update && upgrade
$ sudo apt install python3 python3-pip ipython3
(https://medium.com/@rhdzmota/python-development-on-the-windows-subsystem-for-linux-wsl-17a0fa1839d)
$ sudo service postgresql start

follow linus steps for installing until "run the app locally"
$ heroku local web -f Procfile.windows
deployed: https://secret-woodland-13272.herokuapp.com/
local: http://localhost:5000/