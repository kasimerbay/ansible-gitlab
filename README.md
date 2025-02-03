# Ansible Project

This project uses Ansible to automate the deployment and configuration of your Gitlab Installation.

## Prerequisites

- Ansible installed on your local machine
- SSH access to the target servers
- A vault password file (`vault_pass.txt`)

## Installation

1. Clone the repository:
    ```sh
    git clone https://gitlab.com/ansible-gitlab.git
    cd your-repo
    ```

## Usage

1. Update the inventory file with your target servers.
2. Customize the playbooks and variables as needed.
3. Run the playbook:
    ```sh
    ansible-playbook -i inventory install_gitlab.yml
    ```

## License

This project is licensed under the MIT License.
