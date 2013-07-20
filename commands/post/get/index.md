---
layout: default
title: 'wp post get'
---

`wp post get` - Get a post's content by ID.

### OPTIONS

	[--format=<format>]
			The format to use when printing the post, acceptable values:

	**content**: Outputs only the post's content.

	**table**: Outputs all fields of the post as a table. Note that the
	post_content field is omitted so that the table is readable.

	**json**: Outputs all fields in JSON format.

	<id>
			The ID of the post to get.

### EXAMPLES

	wp post get 12 --format=content

	wp post get 12 > file.txt


