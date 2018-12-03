# Galera Recovery Script

Painless galera cluster recovery by automatic host selection and bootstrapping.

## Installation

- Edit username used for ssh in `usr/local/bin/recover_galera_cluster:4`
- Provide list of host IP address in the `/usr/local/etc/galera_cluster_ip`
  e.g.:
  ```
  192.168.1.1
  192.168.1.2
  ```
- Copy all file and it's folder structure to root directory
  ```
  cp -r {etc,usr} /
  ```
