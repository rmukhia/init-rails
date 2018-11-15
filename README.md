# Initialize Environment for RAILS delvelopment for Ubuntu 18

Install using:
```
curl -sL https://raw.githubusercontent.com/rmukhia/init-rails/master/install-development.sh | bash -
```

Will install
* rbenv
* ruby 2.5.1
* postgres
* bundler gem
* rails gem
* nodejs 10
* yarn

After running this script, create a postgres user
```
sudo su postgres -c "createuser -s your_ubuntu_user_name"
```

