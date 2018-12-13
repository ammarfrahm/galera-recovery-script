# Galera Recovery Script

Painless galera cluster recovery by automatic host selection and bootstrapping.

## Installation

- Specify configuration file which containing `wsrep_cluster_address` directive in `etc/systemd/system/mysql.service.d/override.conf:2` as parameter to `/usr/local/bin/recover_galera_cluster`
- Edit username used for ssh in `usr/local/bin/recover_galera_cluster:4`
- Copy all file and it's folder structure to root directory
  ```
  cp -r {etc,usr} /
  ```
