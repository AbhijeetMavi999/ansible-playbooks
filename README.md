# ansible-playbooks for nginx server
- Firstly, you have to install ansible on your system. if you're using a Debian-based Linux distribution such as Ubuntu the command will be `sudo apt install ansible`
- After installation run this command `ansible-playbook -i inventory nginx-playbook.yml` to run nginx server on target machine

- And to check if nginx is running or not, go to target machine and run this command `sudo systemctl status nginx`
