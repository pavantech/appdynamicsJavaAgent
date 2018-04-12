install ansible in suse 12
zypper addrepo https://download.opensuse.org/repositories/systemsmanagement/SLE_15/systemsmanagement.repo
zypper refresh
zypper install ansible


check ansible is sinatlled or not
ansible -v
run the follwoing command
add host informaiton on hosts file
we add the gourp names in main.yml
ansible-playbook main.yml

