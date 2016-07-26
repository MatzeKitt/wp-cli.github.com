---
layout: default
title: 'wp cron schedule'
display_global_parameters: true
---

`wp cron schedule` - Manage WP-Cron schedules.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Acron-schedule+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### EXAMPLES

    # List available cron schedules
    $ wp cron schedule list
    +------------+-------------+----------+
    | name       | display     | interval |
    +------------+-------------+----------+
    | hourly     | Once Hourly | 3600     |
    | twicedaily | Twice Daily | 43200    |
    | daily      | Once Daily  | 86400    |
    +------------+-------------+----------+





### SUBCOMMANDS

<table>
	<thead>
	<tr>
		<th>Name</th>
		<th>Description</th>
	</tr>
	</thead>
	<tbody>
		<tr>
			<td><a href="/commands/cron/schedule/list/">list</a></td>
			<td>List available cron schedules.</td>
		</tr>
	</tbody>
</table>
