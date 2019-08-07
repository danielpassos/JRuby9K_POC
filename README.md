# JRuby9K_POC

Proof of concept for using JRuby 9K in a Ruboto project

This repository contains a sample Android Studio project using JRuby.


## Adding JRuby to an AndroidStudio project

Use the `update_jar.sh` script in the `app` folder:

    cd app
    ./update_jar.sh

## Adding gems

* Add your Gemfile in the `app` directory.
* Run the `bundle` Rake task using JRuby

    jruby -S rake bundle
