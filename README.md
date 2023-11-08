# Altschool-project-06

## Task:

- Create an Ansible Playbook to setup a server with Apache
- The server should be set to the Africa/Lagos Timezone
- Host an index.php file with the following content, as the main file on the server:

`<?php
date("F d, Y h:i:s A e", time());
?>`

## Instruction:
- Submit the Ansible playbook
- The output of systemctl status apache2 after deploying the playbook
- A screenshot of the rendered page


##  DELIVERABLES:

### Content of Ansible Playbook
- [Content_of_Ansible_Playbook](https://github.com/wave-cloud0/Ansible-Project/blob/master/playbook.yml)

### Using Vagrant to Build test_host_machine
- ![test_host_machine](<images/test_host_machine.png>)

### Output Screenshot of Running_Ansible_Playbook
- ![image_of_Running_Ansible_Playbook](<images/Running_Ansible_Playbook.png>)

### Output Screenshot of systemctl
- ![Image_of_systemctl](<images/Image_of_systemctl.png>)

### Screenshot of rendered page
- ![image_of_index.php](<images/image_of_index_php.png>)
