---
layout: default
title: 'wp super-admin'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; super-admin</small>

`wp super-admin` - List, add, and remove super admins from a network.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Asuper-admin+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### EXAMPLES

    # List user with super-admin capabilities
    $ wp super-admin list
    supervisor
    administrator

    # Grant super-admin privileges to the user.
    $ wp super-admin add superadmin2
    Success: Granted super-admin capabilities.

    # Revoke super-admin privileges to the user.
    $ wp super-admin remove superadmin2
    Success: Revoked super-admin capabilities.



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
			<td><a href="/commands/super-admin/add/">add</a></td>
			<td>Grant super-admin privileges to one or more users.</td>
		</tr>
		<tr>
			<td><a href="/commands/super-admin/list/">list</a></td>
			<td>Show a list of users with super-admin capabilities.</td>
		</tr>
		<tr>
			<td><a href="/commands/super-admin/remove/">remove</a></td>
			<td>Revoke super-admin privileges to one or more users.</td>
		</tr>
	</tbody>
</table>
