# semanage login

> Manage mapping between a Linux user to the SELinux user.
> See also: `semanage`.
> More information: <https://manned.org/man/semanage-login>.

- See current user mappings:

`semanage login -l`

- Map a Linux user to a SELinux user:

`semanage login {{-a|--add}} {{-s|--seuser}} {{selinux_username}} {{linux_username}}`

- Remove mapping between a Linux user and a SELinux user:

`semanage login {{-d|--delete}} {{linux_username}}`