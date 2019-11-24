# root

[![Build Status](https://cloud.drone.io/api/badges/machippie/root/status.svg)](https://cloud.drone.io/machippie/root)

Ansible role to configure root

## Table of content

* [Default Variables](#default-variables)
  * [root_castles](#root_castles)
  * [root_castles_force](#root_castles_force)
  * [root_password](#root_password)
  * [root_shell](#root_shell)
  * [root_sshkeys](#root_sshkeys)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

## Default Variables

### root_castles

List of castles to use

#### Default value

```YAML
root_castles: []
```

#### Example usage

```YAML
root_castles:
  - tboerger/homeshick-base
  - name: tboerger/homeshick-osx
    force: True
```

### root_castles_force

Force castle updates

#### Default value

```YAML
root_castles_force: true
```

### root_password

Update root password to this value

#### Default value

```YAML
root_password:
```

### root_shell

Enforce this shell for root

#### Default value

```YAML
root_shell: /bin/bash
```

### root_sshkeys

List of authorized keys

#### Default value

```YAML
root_sshkeys: []
```

#### Example usage

```YAML
root_sshkeys:
  - ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAINaQYR0/Oj6k1H03kshz2J7rlGCaDSuaGPhhOs9FcZfn tboerger@host1
  - ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIC7oOi3qaDtfQVFhPKyd0Wk0C/y+QM71vtln8Rl44NlB tboerger@host2
  - ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIFcPTmdo+7eK+8n2yE7Kx1vyQ4yJwHBngvQOt1MPhKhR tboerger@host3
```

## Dependencies

None.

## License

Apache-2.0

## Author

Thomas Boerger
