---
layout: default
title: 'wp site option list'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [site](/commands/site/) &raquo; [option](/commands/site/option/) &raquo; list</small>

`wp site option list` - List site options.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Asite-option-list+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

[\--search=&lt;pattern&gt;]
: Use wildcards ( * and ? ) to match option name.

[\--field=&lt;field&gt;]
: Prints the value of a single field.

[\--fields=&lt;fields&gt;]
: Limit the output to specific object fields.

[\--format=&lt;format&gt;]
: The serialization format for the value. total_bytes displays the total size of matching options in bytes.
\---
default: table
options:
  - table
  - json
  - csv
  - count
  - yaml
  - total_bytes
\---

### AVAILABLE FIELDS

This field will be displayed by default for each matching option:

* meta_key
* meta_value

These fields are optionally available:

* meta_id
* site_id
* size_bytes

### EXAMPLES

    # List all site options begining with "i2f_"
    $ wp site option list --search="i2f_*"
    +-------------+--------------+
    | meta_key    | meta_value   |
    +-------------+--------------+
    | i2f_version | 0.1.0        |
    +-------------+--------------+



