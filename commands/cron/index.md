---
layout: default
title: 'wp cron'
display_global_parameters: true
---

`wp cron` - Manage WP-Cron events and schedules.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Acron+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### EXAMPLES

    # Test WP Cron spawning system
    $ wp cron test
    Success: WP-Cron spawning is working as expected.



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
			<td><a href="/commands/cron/event/">event</a></td>
			<td>Manage WP-Cron events.</td>
		</tr>
		<tr>
			<td><a href="/commands/cron/schedule/">schedule</a></td>
			<td>Manage WP-Cron schedules.</td>
		</tr>
		<tr>
			<td><a href="/commands/cron/test/">test</a></td>
			<td>Test the WP Cron spawning system and report back its status.</td>
		</tr>
	</tbody>
</table>
