# Ansible Role: Pi-hole Redirect

This Ansible role configures Pi-hole to redirects the base URL to the `/admin` Log in page

## Requirements

- Ansible 2.9 or higher
- A system with Pi-hole already installed and configured

## Role Variables

There are no variables to set, just add the Role and aim it at a PiHole Server

## Dependencies

None

## Example Playbook

```yaml
- hosts: pihole_servers
  become: true
  gather_facts: false
  roles:
    - sixteenone.pihole-redirect
```

## License

MIT

## Author Information

This Role was created by [SixteenOne](https://twitter.com/sixteenone)