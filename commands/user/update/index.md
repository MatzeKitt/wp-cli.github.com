---
layout: default
title: 'wp user update'
display_global_parameters: true
---

`wp user update` - Update a user.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Auser-update+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

&lt;user&gt;...
: The user login, user email or user ID of the user(s) to update.

\--&lt;field&gt;=&lt;value&gt;
: One or more fields to update. For accepted fields, see wp_update_user().

### EXAMPLES

    wp user update 123 --display_name=Mary --user_pass=marypass



