# ansible-galaxy-update

Update your roles/requirements.yml file using the latest versions available on Ansible Galaxy

:warning: You should always ensure your playbook is compatible with the new
version of the role you are using. Please review changelog for incompatible
changes after updating your requirements.yml.

## Usage

```bash
ansible-galayx-update [path_to_requirements.yml]
```

Path defaults to `./roles/requirements.yml`

Example output:

```
geerlingguy.mysql None -> 4.3.3
geerlingguy.docker None -> 6.2.0
geerlingguy.pip None -> 2.2.0
geerlingguy.nginx None -> 3.1.4
```

## Install

```bash
curl https://github.com/STEAMULO/ansible-galaxy-update/raw/main/ansible-galaxy-update --output "$HOME/.local/bin/ansible-galaxy-update"

chmod +x "$HOME/.local/bin/ansible-galaxy-update"
```

## License

Licensed under MIT.
