flatpress
=========

A flat design Octopress theme based on Bootstrap 3.

# Installation

Install the `bootstrap-sass` gem:

```shell
$ gem install bootstrap-sass
```

Add this line in your `config.rb` file:

```ruby
require 'bootstrap-sass'
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
