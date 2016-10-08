
The following list has been put together manually according to this criteria:

- Is **more than** a list of **files**: This is the least helpful case (and I'll obviously not fill in the rest of the fields).
- Describes **basic functionality**: Has one or more meaningful sentences what the plugin does, apart from its name.
- Has a **usage example**.
- **Installation instructions** has more content than a link to the plugin site with general hints. 
- There are **no empty sections** are in the Readme.

I have left the `sensu-plugins-` prefix out.

| plugin name | more than files | basic functionality | usage example | install instructions | no empty sections |
| --- | --- | --- | --- | --- | --- |
| [ansible][] | YES | NO | YES | NO | NO |
| [apache][] | NO | | | | |
| [aws][] | YES | NO | YES | YES | YES |
| [beanstalk][] | NO |  |  |  |  |
| [boundary][] | NO |  |  |  |  |
| [campfire][] | YES | NO | YES | NO | NO |
| [cassandra][] | NO |  |  |  |  |
| [ceph][] | NO |  |  |  |  |
| [chef][] | NO |  |  |  |  |
| [consul][] | NO |  |  |  |  |
| [couchbase][] | NO |  |  |  |  |
| [cpu-checks][] | NO |  |  |  |  |
| [cucumber][] | YES | YES | YES | NO | NO |
| [datadog][] | YES | YES | YES | YES | NO |
| [dhcp][] | NO |  |  |  |  |
| [disk-checks][] | YES | YES | YES | NO | YES |
| [dns][] | NO |  |  |  |  |
| [docker][] | NO |  |  |  |  |
| [elasticsearch][] | NO |  |  |  |  |
| [erlang][] | NO |  |  |  |  |
| [etcd][] | YES | NO | NO | NO | NO |
| [eye][] | NO |  |  |  |  |
| [filesystem-checks][] | NO |  |  |  |  |
| [fluentd][] | YES | YES | YES | NO | NO |
| [ftp][] | NO |  |  |  |  |
| [github][] | YES | YES | NO | NO | NO |
| [gluster][] | NO |  |  |  |  |
| [gpg][] | NO |  |  |  |  |
| [graphite][] | YES | NO | YES | NO | NO |
| [graylog][] | NO |  |  |  |  |
| [growthforecast][] | NO |  |  |  |  |
| [haproxy][] | NO |  |  |  |  |
| [hbase][] | NO |  |  |  |  |
| [hipchat][] | YES | NO | YES | NO | NO |
| [http][] | YES | NO | NO | NO | NO |
| [icecast][] | NO |  |  |  |  |
| [imap][] | NO |  |  |  |  |
| [influxdb][] | YES | NO | YES | NO | NO |
| [ipmi][] | NO |  |  |  |  |
| [java][] | NO |  |  |  |  |
| [jenkins][] | NO |  |  |  |  |
| [kannel][] |  |  |  |  |  |
| [logs][] | YES | NO | YES | NO | NO |
| [lxc][] | NO |  |  |  |  |
| [memcached][] | NO |  |  |  |  |
| [memory-checks][] | YES | NO | YES | YES | NO |
| [mesos][] | NO |  |  |  |  |
| [mongodb][] | YES | NO | NO | NO | NO |
| [monit][] | YES | YES | YES | NO | NO |
| [mysql][] | YES | NO | YES | NO | NO |
| [nzbget][] | NO |  |  |  |  |
| [network-checks][] | YES | NO | YES | NO | NO |
| [newrelic][] | NO |  |  |  |  |
| [nginx][] | YES | YES | NO | NO | NO |
| [officehours][] | NO |  |  |  |  |
| [openldap][] | NO |  |  |  |  |
| [openstack][] | NO |  |  |  |  |
| [openvpn][] | YES | NO | YES | NO | NO |
| [opsgenie][] | YES | NO | YES | NO | NO |
| [pacemaker][] | NO |  |  |  |  |
| [pagerduty][] | YES | NO | YES | NO | NO |
| [percona][] | NO |  |  |  |  |
| [php-fpm][] | YES | NO | YES | NO | NO |
| [pingdom][] | NO |  |  |  |  |
| [postfix][] | NO |  |  |  |  |
| [postgres][] | NO |  |  |  |  |
| [process-checks][] | YES | YES | NO | NO | NO |
| [puma][] | NO |  |  |  |  |
| [qmail][] | NO |  |  |  |  |
| [rabbitmq][] | NO |  |  |  |  |
| [raid-checks][] | NO |  |  |  |  |
| [redis][] | NO |  |  |  |  |
| [resque][] | NO |  |  |  |  |
| [riak][] | YES | NO | YES | NO | NO |
| [rspec][] | YES | NO | YES | NO | NO |
| [selinux][] | NO |  |  |  |  |
| [sensu][] | NO |  |  |  |  |
| [serverspec][] | NO |  |  |  |  |
| [sftp][] | NO |  |  |  |  |
| [sip][] | NO |  |  |  |  |
| [snmp][] | NO |  |  |  |  |
| [solr][] | NO |  |  |  |  |
| [springboot][] | NO |  |  |  |  |
| [ssl][] | NO |  |  |  |  |
| [supervisor][] | NO |  |  |  |  |
| [syslog-ng][] | NO |  |  |  |  |
| [telapi][] | NO |  |  |  |  |
| [trafficserver][] | NO |  |  |  |  |
| [tripwire][] | NO |  |  |  |  |
| [twemproxy][] | YES | YES | YES | NO | NO |
| [twilio][] | YES | NO | YES | NO | NO |
| [uchiwa][] | NO |  |  |  |  |
| [unicorn][] | NO |  |  |  |  |
| [varnish][] | NO |  |  |  |  |
| [windows][] | YES | YES | NO | NO | YES |
| [youtube][] | NO |  |  |  |  |



## Notes

- The [aws][] plugin is comparatively large and would not fit the same minimal standard for docs well. This is an edge case that has to be kept in mind, since other plugins could also grow larger.
- The [monit][] readme needs to be completely rewritten to fit the style of other sensu plugin docs.
- Some plugins provide additional instructions that should be in "installation" in other sections.

<!-- links -->
[ansible]: https://github.com/sensu-plugins/sensu-plugins-ansible
[apache]: https://github.com/sensu-plugins/sensu-plugins-apache
[aws]: https://github.com/sensu-plugins/sensu-plugins-aws
[beanstalk]: https://github.com/sensu-plugins/sensu-plugins-beanstalk
[boundary]: https://github.com/sensu-plugins/sensu-plugins-boundary
[campfire]: https://github.com/sensu-plugins/sensu-plugins-campfire
[cassandra]: https://github.com/sensu-plugins/sensu-plugins-cassandra
[ceph]: https://github.com/sensu-plugins/sensu-plugins-ceph
[chef]: https://github.com/sensu-plugins/sensu-plugins-chef
[consul]: https://github.com/sensu-plugins/sensu-plugins-consul
[couchbase]: https://github.com/sensu-plugins/sensu-plugins-couchbase
[cpu-checks]: https://github.com/sensu-plugins/sensu-plugins-cpu-checks
[cucumber]: https://github.com/sensu-plugins/sensu-plugins-cucumber
[datadog]: https://github.com/sensu-plugins/sensu-plugins-datadog
[dhcp]: https://github.com/sensu-plugins/sensu-plugins-dhcp
[disk-checks]: https://github.com/sensu-plugins/sensu-plugins-disk-checks
[dns]: https://github.com/sensu-plugins/sensu-plugins-dns
[docker]: https://github.com/sensu-plugins/sensu-plugins-docker
[elasticsearch]: https://github.com/sensu-plugins/sensu-plugins-elasticsearch
[erlang]: https://github.com/sensu-plugins/sensu-plugins-erlang
[etcd]: https://github.com/sensu-plugins/sensu-plugins-etcd
[eye]: https://github.com/sensu-plugins/sensu-plugins-eye
[filesystem-checks]: https://github.com/sensu-plugins/sensu-plugins-filesystem-checks
[fluentd]: https://github.com/sensu-plugins/sensu-plugins-fluentd
[ftp]: https://github.com/sensu-plugins/sensu-plugins-ftp
[github]: https://github.com/sensu-plugins/sensu-plugins-github
[gluster]: https://github.com/sensu-plugins/sensu-plugins-gluster
[gpg]: https://github.com/sensu-plugins/sensu-plugins-gpg
[graphite]: https://github.com/sensu-plugins/sensu-plugins-graphite
[graylog]: https://github.com/sensu-plugins/sensu-plugins-graylog
[growthforecast]: https://github.com/sensu-plugins/sensu-plugins-growthforecast
[haproxy]: https://github.com/sensu-plugins/sensu-plugins-haproxy
[hbase]: https://github.com/sensu-plugins/sensu-plugins-hbase
[hipchat]: https://github.com/sensu-plugins/sensu-plugins-hipchat
[http]: https://github.com/sensu-plugins/sensu-plugins-http
[icecast]: https://github.com/sensu-plugins/sensu-plugins-icecast
[imap]: https://github.com/sensu-plugins/sensu-plugins-imap
[influxdb]: https://github.com/sensu-plugins/sensu-plugins-influxdb
[ipmi]: https://github.com/sensu-plugins/sensu-plugins-ipmi
[java]: https://github.com/sensu-plugins/sensu-plugins-java
[jenkins]: https://github.com/sensu-plugins/sensu-plugins-jenkins
[kannel]: https://github.com/sensu-plugins/sensu-plugins-kannel
[logs]: https://github.com/sensu-plugins/sensu-plugins-logs
[lxc]: https://github.com/sensu-plugins/sensu-plugins-lxc
[memcached]: https://github.com/sensu-plugins/sensu-plugins-memcached
[memory-checks]: https://github.com/sensu-plugins/sensu-plugins-memory-checks
[mesos]: https://github.com/sensu-plugins/sensu-plugins-mesos
[mongodb]: https://github.com/sensu-plugins/sensu-plugins-mongodb
[monit]: https://github.com/sensu-plugins/sensu-plugins-monit
[mysql]: https://github.com/sensu-plugins/sensu-plugins-mysql
[nzbget]: https://github.com/sensu-plugins/sensu-plugins-nzbget
[network-checks]: https://github.com/sensu-plugins/sensu-plugins-network-checks
[newrelic]: https://github.com/sensu-plugins/sensu-plugins-newrelic
[nginx]: https://github.com/sensu-plugins/sensu-plugins-nginx
[officehours]: https://github.com/sensu-plugins/sensu-plugins-officehours
[openldap]: https://github.com/sensu-plugins/sensu-plugins-openldap
[openstack]: https://github.com/sensu-plugins/sensu-plugins-openstack
[openvpn]: https://github.com/sensu-plugins/sensu-plugins-openvpn
[opsgenie]: https://github.com/sensu-plugins/sensu-plugins-opsgenie
[pacemaker]: https://github.com/sensu-plugins/sensu-plugins-pacemaker
[pagerduty]: https://github.com/sensu-plugins/sensu-plugins-pagerduty
[percona]: https://github.com/sensu-plugins/sensu-plugins-percona
[php-fpm]: https://github.com/sensu-plugins/sensu-plugins-php-fpm
[pingdom]: https://github.com/sensu-plugins/sensu-plugins-pingdom
[postfix]: https://github.com/sensu-plugins/sensu-plugins-postfix
[postgres]: https://github.com/sensu-plugins/sensu-plugins-postgres
[process-checks]: https://github.com/sensu-plugins/sensu-plugins-process-checks
[puma]: https://github.com/sensu-plugins/sensu-plugins-puma
[qmail]: https://github.com/sensu-plugins/sensu-plugins-qmail
[rabbitmq]: https://github.com/sensu-plugins/sensu-plugins-rabbitmq
[raid-checks]: https://github.com/sensu-plugins/sensu-plugins-raid-checks
[redis]: https://github.com/sensu-plugins/sensu-plugins-redis
[resque]: https://github.com/sensu-plugins/sensu-plugins-resque
[riak]: https://github.com/sensu-plugins/sensu-plugins-riak
[rspec]: https://github.com/sensu-plugins/sensu-plugins-rspec
[selinux]: https://github.com/sensu-plugins/sensu-plugins-selinux
[sensu]: https://github.com/sensu-plugins/sensu-plugins-sensu
[serverspec]: https://github.com/sensu-plugins/sensu-plugins-serverspec
[sftp]: https://github.com/sensu-plugins/sensu-plugins-sftp
[sip]: https://github.com/sensu-plugins/sensu-plugins-sip
[snmp]: https://github.com/sensu-plugins/sensu-plugins-snmp
[solr]: https://github.com/sensu-plugins/sensu-plugins-solr
[springboot]: https://github.com/sensu-plugins/sensu-plugins-springboot
[ssl]: https://github.com/sensu-plugins/sensu-plugins-ssl
[supervisor]: https://github.com/sensu-plugins/sensu-plugins-supervisor
[syslog-ng]: https://github.com/sensu-plugins/sensu-plugins-syslog-ng
[telapi]: https://github.com/sensu-plugins/sensu-plugins-telapi
[trafficserver]: https://github.com/sensu-plugins/sensu-plugins-trafficserver
[tripwire]: https://github.com/sensu-plugins/sensu-plugins-tripwire
[twemproxy]: https://github.com/sensu-plugins/sensu-plugins-twemproxy
[twilio]: https://github.com/sensu-plugins/sensu-plugins-twilio
[uchiwa]: https://github.com/sensu-plugins/sensu-plugins-uchiwa
[unicorn]: https://github.com/sensu-plugins/sensu-plugins-unicorn
[varnish]: https://github.com/sensu-plugins/sensu-plugins-varnish
[windows]: https://github.com/sensu-plugins/sensu-plugins-windows
[youtube]: https://github.com/sensu-plugins/sensu-plugins-youtube
