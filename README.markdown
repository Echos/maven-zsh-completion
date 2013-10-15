maven-zsh-completion ![Project status](http://stillmaintained.com/nicoulaj/maven-zsh-completion.png)
====================================================================================================

[Zsh](http://www.zsh.org) completion script for [Maven](http://maven.apache.org).

How to use
----------

Add something like this to your `~/.zshrc`

    fpath=(./maven-zsh-completion $fpath)
    rm -f ~/.zcompdump; compinit
 
