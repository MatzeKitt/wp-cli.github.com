---
layout: default
title: 'wp db drop'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [db](/commands/db/) &raquo; drop</small>

`wp db drop` - Delete the database in MySQL.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Adb-drop+sort%3Aupdated-desc">Github issues</a></small>

<hr />

Runs `DROP_DATABASE` MySQL statement using `DB_HOST`, `DB_NAME`,
`DB_USER` and `DB_PASSWORD` database credentials specified in
wp-config.php.

### OPTIONS

[\--yes]
: Answer yes to the confirmation message.

### EXAMPLES

    $ wp db drop --yes
    Success: Database dropped.



