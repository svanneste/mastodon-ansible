# mastodon-ansible

Just those hacky Ansbile playbooks I'm using to keep Octodon.social running.
It's made for Debian stable.

At the moment it can handle:

* mastodon's web app, streaming, and sidekiq servers (including multiple instances)
* pgbouncer (and make it work with mastodon)
* a NFS client to share uploaded media
* munin
* certificate management with letsencrypt
* and of course splitting the Mastodon instance into up to one service per host

Still missing and should be added soon:

* nginx
* postgresql and redis servers
* a Minio server instead of NFS
* backups with borg (I have really nice scripts but they're well integrated into another project for now)

