# changelog

## v1.2.4

* Bump `consul_agent` role to **v1.2.2**
* Switched `traefik` logs to JSON-format

## v1.2.3

* Return `502` error-code from `traefik` if `consul-agent` is unavailable or stopped

## v1.2.2

* Bump `consul_agent` role to **v1.2.1**

## v1.2.1

* Fixed a `consul_agent_server_backups_keep_count` variable name

## v1.2.0

* Bump consul_agent role to **v1.2.0**
* Added a new variables for backup system

## v1.1.1

* Allow an anonymous users on 'traefik' read key-value storage
* Fixed a defined `x-consul-token` header pass-thru on `traefik`

## v1.1.0

* Added support of multiple datacenters
* Added support of changing of 'local' token's parameter
* Improve a status output of removed tokens

## v1.0.0

* The first version from refactoring
