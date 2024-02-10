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