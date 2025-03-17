# freebsd-conf

### Configs for ansible

#### How to use:
`# pkg install py311-ansible git`

`# ansible-pull -o -U http://gitlab.dc.int/pki/freebsd-conf.git`

#### For convenience it will add a scheduled job to check for updates at intervals, so you only need to run the above once.
# Ansible roles for freebsd

Ansible roles to configure FreeBSD hosts and jails to my liking.

These roles are mainly used on dedicated servers from Hetzner.com.

| Service         | Documentation |
|-----------------|---------------|
| acme.sh         | ✅ |
| dma             | ✅ |
| dnsmasq         | ✅ |
| firewall        | ✅ |
| generic-service | ✅ |
| github-runner   | ✅ |
| grafana-agent   | ✅ |
| haproxy         |  |
| jail_exporter   |  |
| jails           |  |
| kanboard        |  |
| lychee          |  |
| network         |  |
| newsyslog       |  |
| nginx           |  |
| nomad-server    |  |
| ntpd            |  |
| packages        |  |
| postgres        |  |
| ssh             |  |
| sudo            |  |
| users           |  |
