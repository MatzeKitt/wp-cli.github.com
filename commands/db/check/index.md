---
layout: default
title: 'wp db check'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; [db](/commands/db/) &raquo; check</small>

`wp db check` - Check the current status of the database.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Adb-check+sort%3Aupdated-desc">Github issues</a></small>

<hr />

Runs `mysqlcheck` utility with `--check` using `DB_HOST`,
`DB_NAME`, `DB_USER` and `DB_PASSWORD` database credentials
specified in wp-config.php.

[See docs](http://dev.mysql.com/doc/refman/5.7/en/check-table.html)
for more details on the `CHECK TABLE` statement.

### EXAMPLES

    $ wp db check
    Success: Database checked.



