# MongoDB replica set docker-compose

This repository provides a docker-compose file that spins up MongoDB instances and configure them as a replica set.

## Installation
1. Modify hostnames as per your liking. Currently, `mongo1, mongo2, mongo3` are being used.
2. Add your hostnames into `/etc/hosts` as:
  ```
  127.0.0.1 mongo1 mongo2 mongo3
  ```
3. Update `scripts/rs-init.sh` to include your modified hostnames.
