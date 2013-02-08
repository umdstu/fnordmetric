FnordMetric
===========

FnordMetric is a highly configurable (and pretty fast) realtime app/event 
tracking thing based on [ruby eventmachine](http://rubyeventmachine.com/) and [redis](http://redis.io/). You define your own 
plotting and counting functions as ruby blocks! [See it in action! (RailsCasts)](http://railscasts.com/episodes/378-fnordmetric)


Getting Started
---------------

Simple Example: this will listen for json-events with `type=unicorn_seen` 
and render a timeline-plot showing the number of received events per hour.

See master branch

This is the easiest way to submit an event:

    echo '{"_type": "unicorn_seen"}' | nc localhost 1337



Installation
------------

    gem install fnordmetric

or in your Gemfile:

    gem 'fnordmetric', :git => 'git://github.com/umdstu/fnordmetric.git'


Documentation
-------------





Full Example
------------
See master branch



Contributors
------------


License
-------

