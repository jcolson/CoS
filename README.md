# www.karma.net/DragonHearts

## to run Jekyll locally

sudo gem install bundler
sudo gem install jekyll\

cp Gemfile from other site

bundle install

## to import data from obsidian

goto the obsidian-html source dir - git pull and then install via pip3 (this installs the latest from github)

`pip3 install .`

### run the converter

rm -Rf output; rm -Rf _site; obsidianhtml convert -v -i config.yml

### run jekyll

bundle exec jekyll serve --trace --drafts

