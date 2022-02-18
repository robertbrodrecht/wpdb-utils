# wpdb-utils
Scripts to automate WordPress database migration on the command line through WP-CLI.

1. [Install WP-CLI](https://wp-cli.org) on local and remote.
2. Make sure Python3 and Pip3 are installed on your local machine.
2. Download scripts and put them in your $PATH.
3. Make scripts writable with `chmod +x`.

Optionally, install these dependencies. The script tries to install them if needed.

1. On local and remote (per user): `wp package install wp-cli/find-command`
2. On local: `pip3 install sshconf`

Command line arguments can be found using `--help`.
