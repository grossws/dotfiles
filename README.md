## Usage

```bash
git clone --shallow-submodules --recurse-submodules https://github.com/grossws/dotfiles ~/.dotfiles

cd ~/.dotfiles

ansible-playbook bootstrap.yml
# if private is present
ansible-playbook bootstrap-private.yml
```

