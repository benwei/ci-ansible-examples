# Setup ansible environment

```
sudo apt install ansible ansible-lint
```

# modify hosts file

please replace the variables
- `your_ssh_host`
- `your_ssh_host_port`
- `your_ssh_username`
- `your_ssh_private_key_pathname`

## dummy-example of hosts file

```
[group1]
ci-runner1 ansible_ssh_host=your_ssh_host ansible_ssh_port=your_ssh_host_port ansible_ssh_user=your_ssh_user_name ansible_ssh_private_key_file=your_ssh_private_key_pathname
```

# run the playbook

command syntax:

```
ansiable-playbook ansible-playbook.yml
```

or 
```
./ci.sh
```
