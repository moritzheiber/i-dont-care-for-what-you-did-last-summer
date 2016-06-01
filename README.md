# I don't care for what you did last summer

A presentation about Continuous Delivery and Immutable Servers.

The presentation is written in [RemarkJS](http://remarkjs.com), needs a webserver to run and includes all perks like presenter notes etc. e.g. press `p` to show my notes for each slide, clone the display with `c`. It's an amazing tool and I love using it for presentations.

## Run a local webserver

I've written a small `rake` task to run a local webserver to take a look at the presentation. It uses [Ruby](https://ruby-lang.org) and [Bundler](https://bundler.io), so you need to have those installed.

Run the following commands to use it:

    bundle install --path vendor/bundle
    bundle exec rake webserver

Use [http://localhost:8000/](http://localhost:8000/) to gain access.
