# Ansible Syshealth

Ansible playbook to check the inode information on the disk which stores the `/home/` directory.

## Usage

1. Please fill in the inventory file defined in the `ansible.cfg` file.
2. Run in your shell:
    ```bash
    ansible-playbook -uroot main.yml
    ```

## Author

Eugene Zyatev ([eu@businesslogic.io](mailto:eu@businesslogic.io))