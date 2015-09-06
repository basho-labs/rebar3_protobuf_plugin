Rebar 3 Protobuf Plugin
=====

This is a rebar3 style plugin to compile protobuffs as part of a project build cycle. This code is rooted as a port from rebar, originally implemented by Tomas Abrahamsson (tomas.abrahamsson@gmail.com), with additional modifications by the Basho team.


Build
-----

    $ rebar3 compile

Use
---

Add the plugin to your rebar3 config:

    {plugins, [
        { rebar3_protobuf_plugin, ".*", {git, "git@host:user/rebar3_protobuf_plugin.git", {tag, "0.0.1"}}}
    ]}.

Then just call your plugin directly in an existing application:


    $ rebar3 rebar3_protobuf_plugin
    ===> Fetching rebar3_protobuf_plugin
    ===> Compiling rebar3_protobuf_plugin
    <Plugin Output>


Contributing and Reporting Bugs
----
Basho encourages contributions to all of our open source software from the community. Here’s how to get started.

* Fork the appropriate sub-projects that are affected by your change. Fork this repository if your changes are for release generation or packaging.
* Make your changes and run the test suite. (see below)
* Commit your changes and push them to your fork.
* Open pull-requests for the appropriate projects.
* Basho engineers will review your pull-request, suggest changes, and merge it when it’s ready and/or offer feedback.
* To report a bug or issue, please open a new [issue](https://github.com/basho/rebar3_protobuf_plugin/issues) against this repository.