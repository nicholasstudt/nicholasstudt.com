---
published: false
layout: post
title: Installing rbenv and jekyll
tags: ['tag']
---

This process was pretty simple once I stopped trying to deal with the
local system ruby. 

## Install rbenv

Pull both the rbenv and ruby-build source.

    git clone git://github.com/sstephenson/rbenv.git ~/.rbenv
    git clone git://github.com/sstephenson/ruby-build.git \
	    ~/.rbenv/plugins/ruby-build

Update your bash to include rbev and local gem files.

    echo 'export PATH="$HOME/.rbenv/bin:$HOME/.gem/ruby/1.9.1/bin/:$PATH"' \
	     >> ~/.bash_profile
    echo 'eval "$(rbenv init -)"' >> ~/.bash_profile

Actually install ruby and change the global ruby.

    rbenv install 1.9.3-p327
    rbenv global  1.9.3-p327

## Install jekyll

    $ gem install --user-install rake
    $ gem install --user-install jekyll

Now that this is installed you can use jekyll to build and preview your
site. In my [case](https://github.com/nicholasstudt/nicholasstudt.com)
just `git clone` the site and `rake preview`.
