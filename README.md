# Ansible Timezone Role

[![Build Status](https://travis-ci.org/weareinteractive/ansible-role-timezone.png?branch=master)](https://travis-ci.org/weareinteractive/ansible-role-timezone)
[![Stories in Ready](https://badge.waffle.io/weareinteractive/ansible-role-timezone.svg?label=ready&title=Ready)](http://waffle.io/weareinteractive/ansible-role-timezone)

> `timezone` is an [ansible](http://www.ansible.com) role which: 
> 
> * configures timezone

## Installation

Using `ansible-galaxy`:

```
$ ansible-galaxy install franklinkim.timezone
```

Using `arm` ([Ansible Role Manager](https://github.com/mirskytech/ansible-role-manager/)):

```
$ arm install franklinkim.timezone
```

Using `git`:

```
$ git clone https://github.com/weareinteractive/ansible-role-timezone.git
```

## Variables

```
timezone: 'Europe/Berlin'
```

## Example playbook

```
- host: all
  roles: 
    - franklinkim.timezone
  vars:
    timezone: 'Europe/Berlin'
```

## Testing

```
$ git clone https://github.com/weareinteractive/ansible-role-timezone.git
$ cd ansible-role-timezone
$ vagrant up
```

## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests and examples for any new or changed functionality.

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License
Copyright (c) We Are Interactive under the MIT license.
