metrics-jruby
=============

This is a wrapper to use the great java-library `metrics` with `jruby`.

To use, just add `gem 'metrics-jruby'` to your `Gemfile` and `require
'metrics_jruby'` in your initalization.  
Now you can access `Java::com.codahale.metrics.MetricRegistry` or
`Java::ComCodahaleMetrics::MetricRegistry`.

More documentation and examples will follow (hopefully).

[![Build Status](https://travis-ci.org/rynr/metrics-jruby.svg?branch=master)](https://travis-ci.org/rynr/metrics-jruby)
