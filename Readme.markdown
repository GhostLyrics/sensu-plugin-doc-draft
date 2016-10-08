
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



## Notes

- The [aws][] plugin is comparatively large and would not fit the same minimal standard for docs well. This is an edge case that has to be kept in mind, since other plugins could also grow larger.

<!-- links -->
[ansible]: https://github.com/sensu-plugins/sensu-plugins-ansible
[apache]: https://github.com/sensu-plugins/sensu-plugins-apache
[aws]: https://github.com/sensu-plugins/sensu-plugins-aws
[beanstalk]: https://github.com/sensu-plugins/sensu-plugins-beanstalk
[boundary]: https://github.com/sensu-plugins/sensu-plugins-boundary
