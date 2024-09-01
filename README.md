
# Install the gloox ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_gloox

# Clone the gloox ansible role. 
git clone git@github.com:computate-org/computate_gloox.git ~/.ansible/roles/computate.computate_gloox

# Change into the gloox ansible role directory. 
cd ~/.ansible/roles/computate.computate_gloox
```

# Run the gloox ansible playbook to install gloox locally. 

```bash
ansible-playbook install.yml
```

