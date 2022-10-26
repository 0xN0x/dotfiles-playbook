# Deploy my dotfiles with an ansible playbook

## Deployment

```
git clone https://github.com/0xN0x/dotfiles-playbook /opt
cd /opt/dotfiles-playbook
ansible-playbook playbook.yml --tags <list of tags seperated by a comma>
```

## Availables tags
- Base
Clone my dotfiles, install general packages like fonts
- Bspwm
Install and configure my bspwm
- Polybar
Install and configure my polybar + Add it to my init script (run by the WM at start)