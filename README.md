# _Find benefits and services_ documentation

_Find benefits and services_ is a web-based application that helps Veterans find relevant benefits. The application is currently in beta and can be found at [benefits-avantages.veterans.gc.ca](https://benefits-avantages.veterans.gc.ca/). It is undergoing development and is not yet publicly released for use.


This repository contains companion documentation for the project and can be viewed at [https://veteransaffairscanada.github.io/](https://veteransaffairscanada.github.io/).

## Editing the documentation

The documentation uses [Jekyll](http://jekyllrb.com/) and the [DOCter](https://github.com/cfpb/DOCter) theme.

DOCter needs Jekyll and other dependencies to run locally. These can be installed with Bundler by running the following commands.

```
gem install bundler
bundle install
```

Run Jekyll:

```
bundle exec jekyll serve --watch --baseurl ''
```

Open it up in your browser: <http://localhost:4000/>

### \_config.yml

Options within the `_config.yml` file allow you to control some of the site's
content and left column navigation.
