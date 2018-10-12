# Galera Recovery Script

Painless galera cluster recovery by automatic host selection and bootstrapping.

## Installation

- Copy all file and it's folder structure to root directory
  ```
  cp -r {etc,usr} /
  ```
- Provide list of host IP address in the `/usr/local/etc/galera_cluster_ip`
  e.g.:
  ```
  192.168.1.1
  192.168.1.2
  ```

