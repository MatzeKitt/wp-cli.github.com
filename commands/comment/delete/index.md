---
layout: default
title: 'wp comment delete'
display_global_parameters: true
---

`wp comment delete` - Delete a comment.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Acomment-delete+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OPTIONS

&lt;id&gt;...
: One or more IDs of comments to delete.

[\--force]
: Skip the trash bin.

### EXAMPLES

    # Delete comment
    $ wp comment delete 1337 --force
    Success: Deleted comment 1337.

    # Delete multiple comments
    $ wp comment delete 1337 2341 --force
    Success: Deleted comment 1337.
    Success: Deleted comment 2341.



