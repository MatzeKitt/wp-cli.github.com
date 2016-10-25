---
layout: default
title: 'wp site option update'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [site](/commands/site/) &raquo; [option](/commands/site/option/) &raquo; update</small>

`wp site option update` - Update a site option.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Asite-option-update+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

&lt;key&gt;
: The name of the site option to update.

[&lt;value&gt;]
: The new value. If ommited, the value is read from STDIN.

[\--format=&lt;format&gt;]
: The serialization format for the value.
\---
default: plaintext
options:
  - plaintext
  - json
\---

### EXAMPLES

    # Update a site option by reading from a file
    $ wp site option update my_option < value.txt
    Success: Updated 'my_option' site option.



