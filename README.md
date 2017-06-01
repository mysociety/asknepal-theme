About AskNepal
===============
AskNepal Initiative is an open platform which can be used by everyone to ask data and information with Nepal government directly, which will increase citizen's reach of Access to Information through the use of technology and encourage citizens engagement in government decision making.

For Local Development

Alaveteli Theme
==============

This is a "hello world" type theme package for Alaveteli.

The intention is to support simple overlaying of templates and
resources without the need to touch the core Alaveteli software.

Typical usage should be limited to that described in the [documentation](http://alaveteli.org/docs/customising/themes/):


## To install:

In the Alaveteli `general.yml` configuration file change the default mysociety  theme repository to your theme repository in the [`THEME_URLS`](http://alaveteli.org/docs/customising/config/#theme_urls) setting:

    THEME_URLS:
      - 'git://github.com/YOUR_GITHUB_USERNAME/YOUR_THEME_NAME.git'

You can then switch the theme the application is using:

    bundle exec rake themes:install

## To run tests:

To run tests, in the Alaveteli Rails.root (with this theme installed):

        bundle exec rspec lib/themes/alavetelitheme/spec


Copyright (c) 2011 mySociety, released under the MIT license
