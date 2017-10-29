# vyos-tools
## Scripts for vyos
## bin
- config-backup

    Output current configuration as command format for restoring it into new vyos instance. This script is expected to use in cron or something like that.

- reset-config

    Reset all configuration of vyos instance.

- run-command

    This is a helper script of `config-backup` above.

## cron.d
- config-backup

    This is a sample of crontab for `config-backup`.
