----
title: Guide
----
[QuickStart](https://jekyllrb.com/docs/) <br>
[Themes](https://jekyllrb.com/docs/themes/)

## 1. Install dependencies 

```bash
sudo apt install ruby-full build-essential zlib1g-dev
```

## 2. Set up a **`gem`** installation for system account
#### add environment variables to **`~/.bashrc`** file

```bash
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
```

## 3. Install Jekyll and Bundler `gems`

```bash
gem install jekyll bundler
```

## 4. Create a new Jekyll projects and change path

```bash
jekyll new myBlog
cd myBlog
```
## 5. Build and see the site on a local server

```bash
bundle exec jekyll serve
```

## 6. Browse to [`http://localhost:4000`](http://localhost:4000)
#### option to serve automatically refresh the page
```bash
bundle exec jekyll serve --livereload
```