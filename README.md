# Ansible
Run ansible via:  
1. Create Box (likley Kali Linux VM)
2. `git clone git@github.com:RyanMower/kali-build.git`
3. `cd kali-build`
4. Install ansible: `python3 -m pip install ansible`
5. `export PATH=$PATH:~/.local/bin`
6. `ansible-galaxy install -r requirements.yml`
7. Caches sudo token - `sudo whoami`
8. `ansible-playbook main.yml`

