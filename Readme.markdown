
The following list has been put together manually according to this criteria:

- Is **more than** a list of **files**: This is the least helpful case (and I'll obviously not fill in the rest of the fields).
- Describes **basic functionality**: Has one or more meaningful sentences what the plugin does, apart from its name.
- Has a **usage example**.
- **Installation instructions** has more content than a link to the plugin site with general hints. 
- There are **no empty sections** are in the Readme.

I'll also leave the `sensu-plugins-` prefix out.

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
