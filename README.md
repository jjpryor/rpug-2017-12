# 2017-12 Raleigh Puppet User Group Meeting notes

## RPUG News
+ [Next meeting is Monday January 8 at Arista Networks in Cary](https://www.meetup.com/Raleigh-Puppet-User-Group/events/245647135/)

## Puppet ecosystem software announcements and news bits
+ [Foreman 1.6.0 released](https://groups.google.com/forum/?fromgroups#!topic/foreman-announce/RW3n6y9klR8)
  - includes Puppet 5 support
  - drops Puppet 3 support (installer modules)
+ [Bolt 0.9.0 released](https://groups.google.com/forum/#!topic/puppet-announce/tOV04aniHNA)
  - v0.8.0 added sudo and sudo password as features, and v0.9.0 has bug fixes for sudo
  - Bolt no uses scp instead of sftp for ssh file transfer to support a wider range of targets.
+ [Puppet Enterprise 2016.4.9, 2017.2.5, and 2017.3.2 are now available](https://groups.google.com/forum/#!topic/puppet-announce/PjzAU73fRKk)
+ Puppet tips from Example42 blog:
  - [Tip of the Week 46 - Checking config files before applying them](https://www.example42.com/2017/11/13/checking-config-files-before-applying-them/)
  - [Tip of the Week 47 - HowTo DevOps](https://www.example42.com/2017/11/20/how_devops_changes_infrastructure/)
  - [Tip of the Week 48 - Puppet modules documentation](https://www.example42.com/2017/11/27/puppet_modules_documentation/)
  - [Tip of the Week 49 - LibRAL and a proposal for the new Puppet Resource API](https://www.example42.com/2017/12/04/libral_puppet_resource_api/)

## Selected news items from Puppet.com Blog:
+ [Latest version of AWS module adds Puppet Tasks](https://puppet.com/blog/latest-version-puppet-aws-module-adds-tasks)

# Meeting's topic: Modules and Tools Discussion
Jere says: *"My role is a little different but here are the things I find most useful day-to-day:*
+ http://garylarizza.com/blog/2013/11/25/fun-with-providers/
+ http://garylarizza.com/blog/2013/11/26/fun-with-providers-part-2/
+ http://garylarizza.com/blog/2013/12/15/seriously-what-is-this-provider-doing/
+ Ruby 'pry'
+ PDK, linting, & rubocop
+ https://www.camptocamp.com/en/actualite/puppet-test-driven-development-part-iii-create-custom-type-provider/ *shows how to test your code for idempotency!*

I've examined and used just about all of these and this is what I would use in my r10k Puppetfile:
+ https://forge.puppet.com/puppet/hiera
+ https://forge.puppet.com/puppet/r10k
+ https://forge.puppet.com/puppetlabs/stdlib
+ https://forge.puppet.com/puppetlabs/ntp
+ https://forge.puppet.com/puppet/yum
+ https://forge.puppet.com/lwf/remote_file
+ https://forge.puppet.com/puppet/archive
+ https://forge.puppet.com/puppet/selinux
+ https://forge.puppet.cohoneycutm/gt/ssh
+ https://forge.puppet.com/puppetlabs/accounts
+ https://forge.puppet.com/camptocamp/openssl
+ https://forge.puppet.com/camptocamp/accounts
+ https://forge.puppet.com/puppet/rhsm
+ https://forge.puppet.com/camptocamp/systemd
+ https://forge.puppet.com/crayfishx/firewalld
+ https://forge.puppet.com/stahnma/epel
+ https://forge.puppet.com/saz/sudo
+ https://forge.puppet.com/puppetlabs/lvm
+ https://forge.puppet.com/icinga/icinga2
+ https://forge.puppet.com/puppet/autofs
