---
layout: default
title: 'wp user get'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [user](/commands/user/) &raquo; get</small>

`wp user get` - Get a single user.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Auser-get+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

&lt;user&gt;
: User ID, user email, or user login.

[\--field=&lt;field&gt;]
: Instead of returning the whole user, returns the value of a single field.

[\--fields=&lt;fields&gt;]
: Get a specific subset of the user's fields.

[\--format=&lt;format&gt;]
: Accepted values: table, json, csv, yaml. Default: table

### EXAMPLES

    # Get user
    $ wp user get 12 --field=login
    supervisor

    # Get user and export to JSON file
    $ wp user get bob --format=json > bob.json



