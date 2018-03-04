# Alternatives to running a project locally
If you are unable to get the guides or website running on your computer,
you can use an online VM/IDE to test out your work.

## Using cloud9
Visit [AWS Cloud9](https://console.aws.amazon.com/) and log in with the credentials provided by your
workshop leaders.

Once you are logged in, visit 
[https://us-east-2.console.aws.amazon.com/cloud9/home/shared](https://us-east-2.console.aws.amazon.com/cloud9/home/shared)
and select the instance that matches your username.

You will find the guides and website pre-installed. You should fork the
repositories. For each fork of the repository, copy the cloning url:

```
cd repository-name
git remote set-url your-fork-url
```

This will allow you to push to your fork to save your work.
You should commit and push often, as cloud9 projects do
not make any guarantees about persistance across time.

### Install dependencies and start the server
```
gem install bundler
bundle install
bundle exec middleman -p 8080
```

Click on the "Preview" button to see your app in action!
In the right hand corner is a button to expand into a new window.

## Instructions for facilitators
These scripts below can be used to create dev environments for the website and 
guides.

### Set up a new dev env

Copy and paste this entire block into the command line. Enter "yes" to any prompts.

```
rvm implode
```

Then,
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"
nvm install 8.9.4
nvm alias default 8.9.4
npm install -g ember-cli
git clone https://github.com/rbenv/rbenv.git ~/.rbenv
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bashrc
echo 'eval "$(rbenv init -)"' >> ~/.bashrc
exec $SHELL
git clone https://github.com/rbenv/ruby-build.git ~/.rbenv/plugins/ruby-build
echo 'export PATH="$HOME/.rbenv/plugins/ruby-build/bin:$PATH"' >> ~/.bashrc
exec $SHELL
rbenv install 2.4.3 --verbose
rbenv global 2.4.3
gem install bundler
git clone https://github.com/emberjs/guides
cd guides
bundle install
cd ..
git clone https://github.com/emberjs/website.git
cd website
bundle install
cd ..
```

Some Linux environments require this before installing rbenv. Errors about missing c compilers
are a sign that you need this.
```
sudo apt-get update
sudo apt-get install build-essential libssl-dev libreadline-dev libyaml-dev libsqlite3-dev sqlite3 libxml2-dev libxslt1-dev libcurl4-openssl-dev python-software-properties libffi-dev
```
