flatpress
=========

A flat design Octopress theme based on Bootstrap 3.

# Installation

Install the `bootstrap-sass` and `font-awesome-sass` gems:

```shell
$ gem install 'bootstrap-sass'
$ gem install 'font-awesome-sass'
```

Add these lines in your `config.rb` file:

```ruby
require 'bootstrap-sass'
require 'font-awesome-sass'
```

And then execute this command in your octopress directory:

```shell
$ cd my_blog
$ bundle exec compass install bootstrap
```

Install the theme:

```shell
$ git clone git://github.com/jledentu/flatpress.git .themes/flatpress
$ rake install['flatpress']
```
