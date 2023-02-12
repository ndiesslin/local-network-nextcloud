# Local Network Nextcloud Using Docker
A Nextcloud setup exclusively for local networks using Docker.

## Setup
1. Install [Docker](https://www.docker.com/).
2. Set a static IP Address on your computer that will run this project.
- 2.1. NOTE: If you set your static IP Address other than ``192.168.1.2,`` you will need to find and replace this IP Address in this project.
3. Define directory location in the [.env](./.env) file.
4. Start project by running ``docker-compose up -d``.
5. Login at ``localhost`` in your web browser.
- 5.1. Username: admin
- 5.2. Password: password
6. Login on other devices at ``192.168.1.2`` or your specified static IP Address.

## Notes:
1. Anytime you restart Docker your data should be still available.
