elixir-couchdb
==============

CouchDB client for Elixir

What is it?
-----------

Well - the name is selfcontained. This is the github repository for the first CouchDB client written in Elixir. This will be a package and will be published as a package at [https://hex.pm/packages](https://hex.pm/packages).

Authors
-------

Until now, there is awesome [Alexander Shorin](https://github.com/kxepal) and me starting with this package. We are both members of the Apache CouchDB PMC and are actively contributing to the CouchDB project. You can get in touch with us easily at irc.freenode.net#couchdb-dev. 

Version
-------

As of today, this is version 0.0.1. This is a project done in our freetime. So please be patient.

Contributing
------------

Would you like to contribute? You are welcome. Please get in touch with us or write an issue.

Run the tests
-------------

In the project folder run:

    mix test

Handling dependencies
---------------------

In the project folder run:

    mix deps.get

> to get the dependencies

    mix deps.update

> to update the dependencies

API documentation
-----------------

The API provided by Couchdb Elixir is based on the CouchDB API. Please see the documentation at [docs.couchdb.org](http://docs.couchdb.org)

Code documentation
------------------

To create the Code documentation run

    mix docs

Usage
-----

Add `couchdb` as a dependency to your mix application in mix.exs:

    defp deps do
        [
          {:couchdb, "~> 0.0.1"}
        ]
    end


