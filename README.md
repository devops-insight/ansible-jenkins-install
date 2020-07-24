# ansible-jenkins-install
Ansible playbook to install Jenkins server on Ubuntu OS

### Configure
- Update inventory with list of servers
- Replace the machine root password 

### Run Play Book
 `
ansible-playbook jenkins-pb.yml -i inventory.ini --extra-vars 'ansible_become_pass=<<machine admin password>>'
`

### Jenkins Console UI
`
http://your-host-name:8080
`
http://localhost:8080
`