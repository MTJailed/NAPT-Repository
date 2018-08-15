# NAPT-Repository
NAPT is a modern package manager that can be ran in any environment, including restrictive sandboxes.

NAPT Repositories contain packages for and information for the package manager.

This repository is an example of a repository containing an example package.

NAPT repositories were inspired on Bower, the encoding language used for configuration files is JSON.

NAPT by default provides and recommends code signatures using Pretty Good Privacy.

Packages and the repository's integrity are checked by public key and signature verifications.

It is up to the maintainer of the repository and packages to decide whether code signing is used or not.

NAPT repositories can be hosted at any web server but the guidelines are to run it on a server where the package file can automatically be updated via cron jobs.

SSL encryption for the server is also recommended.

# Guidelines
- Use GPG codesigning
- Use TLS


# Recommendations
- A webserver preferably with scripting functionality and cron support
