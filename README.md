# vault_ha

### Configure SSH key
`ssh-keygen -t rsa`

### Copying SSH Keys to Servers Raft_ha_transit
`ssh-copy-id vagrant@192.168.56.2`<br />
`ssh-copy-id vagrant@192.168.56.4`<br />
`ssh-copy-id vagrant@192.168.56.5`<br />
`ssh-copy-id vagrant@192.168.56.6`<br />


### Copying SSH Keys to Servers Raft_ha_autopilot
`ssh-copy-id vagrant@192.168.56.4`<br />
`ssh-copy-id vagrant@192.168.56.5`<br />
`ssh-copy-id vagrant@192.168.56.6`<br />

### Run vagrant
`vagrant up`

### Run Ansible Playbook
`ansible-playbook -i inventory main.yaml`