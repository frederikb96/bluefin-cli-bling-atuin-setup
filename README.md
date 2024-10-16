### Description:
This playbook is useful if you don't want the up arrow functionality for Atuin in Bluefin CLI enabled, but you still want the extra bling provided by Bluefin. It modifies the configuration to only use the nice Atuin search with `Ctrl + R` while keeping the rest of the Bluefin bling setup.

### Prerequisites:
You must have already executed `bluefin-cli` and enabled it for this playbook to work properly.

### Quickstart:

Run the playbook:
   ```bash
   ansible-playbook -i localhost bluefin-atuin.yml
   ```

This will prompt you to confirm that `bluefin-cli` has been installed and then proceed to modify the Atuin configuration and `.bashrc` file as needed.