# ansible-roles

Shareable Ansible roles

## Usage

1.  Create a `requirements.yml` in your Playbook folder with the following contents:

    ```yml
    ---
    - src: https://github.com/psiberia/ansible-roles.git
      scm: git
      version: origin/main
    ```

1.  Install requirements and run your Playbook:

    ```bash
    ansible-galaxy install -r requirements.yml
    ansible-playbook -i hosts site.yml
    ```
