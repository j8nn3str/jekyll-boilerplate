# Jekyll Boilerplate

## Initial Setup
Run the following

### Ubuntu / Debian WSL
```sh
sudo apt update && sudo apt upgrade -y
sudo apt-get install -y ruby-full build-essential zlib1g-dev
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
sudo gem install bundler
sudo gem install jekyll

```