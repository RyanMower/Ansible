# Ansible
Run ansible via:  
1. Create Box (likley Kali Linux VM)
2. `git clone git@github.com:RyanMower/kali-build.git`
3. `cd kali-build`
4. Install ansible: `python3 -m pip install ansible`
5. `ansible-galaxy install -r requirements.yml`
6. Caches sudo token - `sudo whoami`
7. `ansible-playbook main.yml`

