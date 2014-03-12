# Riemann Metrics

## General

Riemann Metrics is a small service that can export data produced by http://metrics.codahale.com/ (specifically the metrics servlet: http://metrics.codahale.com/getting-started/#reporting-via-http) to riemann

## Usage

<pre>
riemann-metrics --event-host &lt;monitored_host&gt; --host &lt;riemann_host&gt; --metric-servlet-uri &lt;metrics_servlet_uri&gt;
</pre>

## Installation

Deploy via https://github.com/hoccer/talk-deployment (see `services/riemann-metrics`)

## Development Setup

Required: `rvm` (http://rvm.io)

Enter directory and first link up the `.ruby*` files:

<pre>
$ ln -s .ruby-version.dev .ruby-version
$ ln -s .ruby-gemset.dev .ruby-gemset
$ cd . # to activate this setting
</pre>

Then install all required gems via

<pre>
$ bundle
</pre>
