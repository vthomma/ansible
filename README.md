
**To run the ansible script**

# ansible-playbook -i inventory.ini nginx_install.yml --ask-become-pass


-   **Explanation of interactions:** 

- **i inventory.ini** : Specifies your **inventory file**.


-  **nginx_install.yml**: The name of your **playbook file**.

-  **--ask-become-pass**: Prompts for the sudo password on the target host(s) if required. If you are using SSH keys with sudo configured for passwordless execution, you might not need this flag.