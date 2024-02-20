# Playbook to setup Forester controller

## Use

Install required collections:

```
ansible-galaxy install -r requirements.yml
```

Run the playbook:

```
ansible-playbook --connection=local -K -v setup_forester.yml
```

Unfortunatelly editing the libvirt network to support pxe is still a manual process
Please update the libvirt network according to [docs](https://foresterorg.github.io/docs/contributing/#libvirt-setup)