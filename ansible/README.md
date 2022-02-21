## Usage

Edit `inventory/hosts` to match the system information based on the example below:

```bash
Example:

[homeserver]
homeserver.local.harissaeed.com ansible_host=100.68.129.77 ansible_ssh_user=pi ansible_port=33 become=true become_user=root
```
More hosts can also be added.

Start provisioning of the cluster using the following command:

```bash
ansible-playbook -i inventory/hosts upgrade.yaml
```

## Output
![image](https://user-images.githubusercontent.com/57041349/163784226-6ad1c9be-e759-447c-84e8-0472933b05c6.png)
