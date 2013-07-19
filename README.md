# Compass sprite generator v0.1.1-build

Css sprites using the compass css framework.

## General Sprite Defaults

    $icon-sprite-base-class : ".icon-sprite" !default;
    $icon-sprite-dimensions : false !default;
    $icon-position : 0% !default;
    $icon-spacing : 0 !default;
    $icon-repeat : no-repeat !default;
    $icon-prefix : '' !default;
    $icon-clean-up : true !default;
    $icon-layout : vertical !default;
    $icon-inline : false !default; 

## Requirements

* [RubyGems](https://rvm.io/rvm/install)
* [Sass](http://sass-lang.com)
* [Compass](http://compass-style.org)

## Installation
	$ gem update --system
	$ gem install sass
	$ gem install compass
    $ git clone git://github.com/nelsondelega/sprite-generator.git
    $ cd sprite-generator
    $ sass --compass --watch --trace scss/sprites.scss:css/sprites.css

## Contributing

[Fork](https://help.github.com/articles/fork-a-repo) this project and:

    $ git clone git@github.com:<username>/sprite-generator.git	
	$ git remote add owner git@github.com:nelsondelega/sprite-generator.git
    $ git pull owner master
    $ git add .
    $ git commit -am "Your commit"
    $ git push origin master

Make the [Pull Request](https://help.github.com/articles/using-pull-requests) from your branch `master` to branch `master` on [nelsondelega/sprite-generator](https://github.com/nelsondelega/sprite-generator).