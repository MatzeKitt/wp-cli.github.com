---
layout: default
title: 'wp scaffold plugin-tests'
display_global_parameters: true
---

`wp scaffold plugin-tests` - Generate files needed for running PHPUnit tests.

<small>Quick links: <a href="https://github.com/wp-cli/wp-cli/issues?q=is%3Aopen+label%3Acommand%3Ascaffold-plugin-tests+sort%3Aupdated-desc">Github issues</a></small>

<hr />

### OVERVIEW

The following files are generated for your plugin by this command:

* `phpunit.xml.dist` is the configuration file for PHPUnit.
* `.travis.yml` is the configuration file for Travis CI. Use `--ci=&lt;provider&gt;` to select a different service.
* `bin/install-wp-tests.sh` configures the WordPress test suite and a test database.
* `tests/bootstrap.php` is the file that makes the current plugin active when running the test suite.
* `tests/test-sample.php` is a sample file containing the actual tests.

Learn more from the [plugin unit tests documentation](http://wp-cli.org/docs/plugin-unit-tests/).

### ENVIRONMENT

The `tests/bootstrap.php` file looks for the WP_TESTS_DIR environment
variable.

### OPTIONS

[&lt;plugin&gt;]
: The name of the plugin to generate test files for.

[\--dir=&lt;dirname&gt;]
: Generate test files for a non-standard plugin path. If no plugin slug is specified, the directory name is used.

[\--ci=&lt;provider&gt;]
: Add a configuration file for a continuous integration provider.
\---
default: travis
options:
  - travis
  - circle
	 - gitlab
\---

[\--force]
: Overwrite files that already exist.

### EXAMPLES

    $ wp scaffold plugin-tests sample-plugin
    Success: Created test files.



