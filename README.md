# Git Fit - Docker Compose Stack

*A fitness tracking application powered by wger*
Git Fit contains 3 docker compose environments:

* prod (in root of this repository)
* dev (uses sqlite)
* dev-postgres (uses postgresql)

The production Docker Compose file initializes a production environment with the
application server, a reverse proxy, a database, a caching server, and a Celery
queue, all configured. Data is persisted in volumes, if you want to use folders,
read the warning in the env file.

**TLDR:** just do `docker compose up -d`

For more details about the underlying wger platform, consult the documentation:

* production: <https://wger.readthedocs.io/en/latest/production/docker.html>
* development: <https://wger.readthedocs.io/en/latest/development/docker.html>

It is recommended to regularly pull the latest version of the compose file,
since sometimes new configurations or environmental variables are added.

## Contact

Git Fit is built on the excellent wger platform. For platform-related issues,
please refer to the original wger project:

* Mastodon: <https://fosstodon.org/@wger>
* Discord: <https://discord.gg/rPWFv6W>
* Issue tracker: <https://github.com/wger-project/docker/issues>


## Sources

Git Fit is based on the open-source wger project:

* <https://github.com/wger-project/>

This Git Fit deployment configuration is a customized version for enhanced fitness tracking.

## Licence

The application is licenced under the Affero GNU General Public License 3 or
later (AGPL 3+).



