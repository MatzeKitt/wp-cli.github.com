---
layout: default
title: 'wp role list'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [role](/commands/role/) &raquo; list</small>

`wp role list` - List all roles.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Arole-list+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

[\--fields=&lt;fields&gt;]
: Limit the output to specific object fields.

[\--format=&lt;format&gt;]
: Render output in a particular format.
\---
default: table
options:
  - table
  - csv
  - json
  - count
  - yaml
\---

### AVAILABLE FIELDS

These fields will be displayed by default for each role:

* name
* role

There are no optional fields.

### EXAMPLES

    # List roles.
    $ wp role list --fields=role --format=csv
    role
    administrator
    editor
    author
    contributor
    subscriber



