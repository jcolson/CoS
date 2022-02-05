# www.karma.net/DragonHearts

## to run Jekyll locally

gem install bundler

bundle install

bundle exec jekyll serve --trace --drafts

## to import data from obsidian

find . -type f -name "*.md" -not -name "README.md" -delete

obsidian-export_MacOS-x86_64.bin ~/Google\ Drive/Obsidian/Jay\'s\ Notebook .

obsidianhtml -v -i config.yml


