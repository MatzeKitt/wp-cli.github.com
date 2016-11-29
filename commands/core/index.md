---
layout: default
title: 'wp core'
display_global_parameters: true
---

<small>[Commands](/commands/) &raquo; core</small>

`wp core` - Download, install, update and manage a WordPress install.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Acore+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### EXAMPLES

    # Download WordPress core
    $ wp core download --locale=nl_NL
    Downloading WordPress 4.5.2 (nl_NL)...
    md5 hash verified: c5366d05b521831dd0b29dfc386e56a5
    Success: WordPress downloaded.

    # Install WordPress
    $ wp core install --url=example.com --title=Example --admin_user=supervisor --admin_password=strongpassword --admin_email=info@example.com
    Success: WordPress installed successfully.

    # Display the WordPress version
    $ wp core version
    4.5.2



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
			<td><a href="/commands/core/check-update/">check-update</a></td>
			<td>Check for WordPress updates via Version Check API.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/config/">config</a></td>
			<td>Generate a wp-config.php file.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/download/">download</a></td>
			<td>Download core WordPress files.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/install/">install</a></td>
			<td>Runs the standard WordPress installation process.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/is-installed/">is-installed</a></td>
			<td>Check if WordPress is installed.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/language/">language</a></td>
			<td>Manage core language.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/multisite-convert/">multisite-convert</a></td>
			<td>Transform a single-site install into a WordPress multisite install.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/multisite-install/">multisite-install</a></td>
			<td>Install WordPress multisite from scratch.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/update/">update</a></td>
			<td>Update WordPress to a newer version.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/update-db/">update-db</a></td>
			<td>Run the WordPress database update procedure.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/verify-checksums/">verify-checksums</a></td>
			<td>Verify WordPress files against WordPress.org's checksums.</td>
		</tr>
		<tr>
			<td><a href="/commands/core/version/">version</a></td>
			<td>Display the WordPress version.</td>
		</tr>
	</tbody>
</table>
