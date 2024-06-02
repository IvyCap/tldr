# semanage login

> Manage mapping between a Linux user to the SELinux user.
> More information: <https://manned.org/man/semanage-login>.

- See current user mappings:s
`semanage login -l`

- Map a Linux user to a SELinux user:
`semanage login {{-a|--add}} {{-s|--seuser}} {{SELinux_username}} {{Linux_username}}`

- Remove mapping between a Linux user and a SELinux user:
`semanage login {{-d|--delete}} {{Linux_username}}`