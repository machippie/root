
## Default Variables

### root_bashit

Install bash-it repo

#### Default value

```yaml
root_bashit: false
```

### root_castles

List of castles to use

#### Default value

```yaml
root_castles: []
```

#### Example usage

```yaml
root_castles:
  - tboerger/homeshick-base
  - name: tboerger/homeshick-osx
    force: True
```

### root_castles_force

Force castle updates

#### Default value

```yaml
root_castles_force: true
```

### root_ohmyzsh

Install oh-my-zsh repo

#### Default value

```yaml
root_ohmyzsh: false
```

### root_password

Update root password to this value

#### Default value

```yaml
root_password:
```

### root_shell

Enforce this shell for root

#### Default value

```yaml
root_shell: /bin/bash
```

### root_sshkeys

List of authorized keys

#### Default value

```yaml
root_sshkeys: []
```

#### Example usage

```yaml
root_sshkeys:
  - ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAINaQYR0/Oj6k1H03kshz2J7rlGCaDSuaGPhhOs9FcZfn tboerger@host1
  - ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIC7oOi3qaDtfQVFhPKyd0Wk0C/y+QM71vtln8Rl44NlB tboerger@host2
  - ssh-ed25519 AAAAC3NzaC1lZDI1NTE5AAAAIFcPTmdo+7eK+8n2yE7Kx1vyQ4yJwHBngvQOt1MPhKhR tboerger@host3
```
## Dependencies

None

## License

Apache-2.0

## Author

Thomas Boerger