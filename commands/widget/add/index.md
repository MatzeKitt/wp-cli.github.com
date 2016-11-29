---
layout: default
title: 'wp widget add'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [widget](/commands/widget/) &raquo; add</small>

`wp widget add` - Add a widget to a sidebar.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Awidget-add+sort%3Aupdated-desc">Github issues</a></small>

<hr />

Creates a new widget entry in the database, and associates it with the
sidebar.

### OPTIONS

&lt;name&gt;
: Widget name.

&lt;sidebar-id&gt;
: ID for the corresponding sidebar.

[&lt;position&gt;]
: Widget's current position within the sidebar. Defaults to last

[\--&lt;field&gt;=&lt;value&gt;]
: Widget option to add, with its new value

### EXAMPLES

    # Add a new calendar widget to sidebar-1 with title "Calendar"
    $ wp widget add calendar sidebar-1 2 --title="Calendar"
    Success: Added widget to sidebar.



