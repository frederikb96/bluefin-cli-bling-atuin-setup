#### Description:
This playbook checks if the system is running the Bluefin distro, runs `bluefin-cli` interactively, copies and modifies the `bling.sh` script for Atuin, and updates `.bashrc` to point to the modified script. Finally, it triggers an `atuin import auto`.

#### Quickstart:

1. Run the playbook:
   ```bash
   ansible-playbook -i localhost bluefin_setup.yml
   ```

This will guide you through running the `bluefin-cli` interactively and then modify the necessary files for Atuin's configuration.