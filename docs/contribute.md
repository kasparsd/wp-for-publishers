---
title: How to Contribute
---

The source of this website is available [on GitHub]({{ site.github.repository_url }}). To suggest a change please open [a new issue]({{ site.github.repository_url }}/issues/new) or create [a pull request](https://help.github.com/articles/creating-a-pull-request/).


## Technology

This is a static website assambled by [Jekyll](https://jekyllrb.com/) from a set of [Markdown](https://daringfireball.net/projects/markdown/syntax) files, [HTML templates]({{ site.github.repository_url }}/tree/master/docs/_layouts) and some [basic styles]({{ site.github.repository_url }}/tree/master/docs/assets/css).

The website is deployed and hosted by [Netlify](https://www.netlify.com).


## Local Development

Requires [Ruby 2.1.0 or higher](https://www.ruby-lang.org/en/downloads/) which is available on MacOS by default.

1. Clone the project repository:

       $ git clone {{ site.github.clone_url }}

2. Install [Bundler](http://bundler.io/):

       $ gem install bundler

3. Setup and configure Jekyll:

       $ bundle install

4. Start a local server with live reload:

       $ bundle exec jekyll serve

Now the development website should be available at [http://127.0.0.1:4000](http://127.0.0.1:4000)
