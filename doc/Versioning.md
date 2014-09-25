# Apache Role: Versioning

We use [semantic versioning][semver], which briefly is:

Given a version number MAJOR.MINOR.PATCH, increment the:

1. MAJOR version when you make incompatible API changes,
1. MINOR version when you add functionality in a backwards-compatible manner, and
1. PATCH version when you make backwards-compatible bug fixes.

## Releases

When something is ready for production usage, we [tag][tag] so you can refer
to that [release][releases] on your [Ansible Galaxy roles being used][galaxy-doc].

## What comes when?

Following [semantic versioning][semver], we have [milestones][] which hold
things that will be [released][releases] when they are ready.

[semver]: http://semver.org/
[milestones]: https://github.com/augustohp/ansible-role-apache/milestones
[releases]: https://github.com/augustohp/ansible-role-apache/releases
[tag]: http://git-scm.com/book/en/Git-Basics-Tagging
[galaxy-doc]: http://docs.ansible.com/galaxy.html
