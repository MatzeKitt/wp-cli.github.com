---
layout: default
title: 'wp scaffold _s'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [scaffold](/commands/scaffold/) &raquo; _s</small>

`wp scaffold _s` - Generate starter code for a theme based on _s.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Ascaffold-_s+sort%3Aupdated-desc">Github issues</a></small>

<hr />

See the [Underscores website](http://underscores.me/) for more details.

### OPTIONS

&lt;slug&gt;
: The slug for the new theme, used for prefixing functions.

[\--activate]
: Activate the newly downloaded theme.

[\--enable-network]
: Enable the newly downloaded theme for the entire network.

[\--theme_name=&lt;title&gt;]
: What to put in the 'Theme Name:' header in 'style.css'.

[\--author=&lt;full-name&gt;]
: What to put in the 'Author:' header in 'style.css'.

[\--author_uri=&lt;uri&gt;]
: What to put in the 'Author URI:' header in 'style.css'.

[\--sassify]
: Include stylesheets as SASS.

[\--force]
: Overwrite files that already exist.

### EXAMPLES

    # Generate a theme with name "Sample Theme" and author "John Doe"
    $ wp scaffold _s sample-theme --theme_name="Sample Theme" --author="John Doe"
    Success: Created theme 'Sample Theme'.



