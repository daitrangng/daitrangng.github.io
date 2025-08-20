Personal website using [customized theme of Thi](https://github.com/dinhanhthi/dinhanhthi.com-v1).

__Note__: This can be run with **Github Pages**.

After cloning to a local server, run these:

```
# install git

# install ruby then
ruby --version

# install bundler
gem install bundler

# cd to the repo directory and install gems
bundle install

# run the server (http://localhost:4000)
bundle exec jekyll serve

# incremental build (only build the changes, faster)
bundle exec jekyll serve -I
```

If there are some technical problems, check [this note first](https://dinhanhthi.com/jekyll-tips/) and then ask Thi.

Some known issues:

🐞 You don't have write permissions for the /Library/Ruby/Gems/2.6.0 directory. -> install using brew,

```bash
# Install Ruby via Homebrew
brew install ruby

# Add Homebrew Ruby to your PATH (add this to your ~/.zshrc)
echo 'export PATH="/opt/homebrew/opt/ruby/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc

# Now install bundler
gem install bundler
```

🐞 'Kernel#load': cannot load such file -- /opt/homebrew/Cellar/ruby/3.4.5/lib/ruby/...

```bash
# First, uninstall the problematic bundler
gem uninstall bundler

# Clean up any broken gem installations
gem cleanup

# Reinstall bundler with the correct paths
gem install bundler

# Verify bundler is working
bundle --version
```