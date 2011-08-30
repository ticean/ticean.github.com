---
layout: post
title: "Handy Git Aliases"
date: 2011-08-30 14:51
comments: true
categories: 
---

When using git, you can create your own aliases. You might define some aliases to save you some time. Like, maybe you'd rather type 'co' in place of 'checkout'.

To add an alias, you'll need to edit the .gitconfig file that's located in your home directory. Add an [alias] section that will contain all the definitions. Like this:



    [user]
      name = Your Name
      email = your@email.com

    [alias]
      co = checkout



### Join the Advanced Team
Adding a personalized alias is cool and all, but what's really handy is that you can add commands as aliases. If you'd like to customize the log output, or add a shortcut to some custom mojo, you can do that.

Here's a nice example that I use daily. From [Bart's Pimping out Git Log](http://www.jukie.net/bart/blog/pimping-out-git-log)


    [alias]
      lg = log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative

