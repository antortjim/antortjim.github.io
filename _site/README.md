Antonio's personal site
===============================

# Install dependencies in Ubuntu 18.04

```
sudo apt-get install ruby-full build-essential zlib1g-dev
```

```
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

```
gem install jekyll bundler
```

```
jekyll install github-pages
jekyll install nokogiri
jekyll install ffi
jekyll install jekyll-paginate
jekyll install jekyll-sitemap
jekyll install jekyll-gist
jekyll install jekyll-feed
jekyll install jemoji
```
# Serve locally
`bundle exec jekyll serve`


# Multilingual support

