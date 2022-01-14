# Mac Development Ansible Playbook

  1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
  2. Install Ansible
  3. Run `ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  4. Run `ansible-playbook main.yml --ask-become-pass` inside this directory. Enter your macOS account password when prompted for the 'BECOME' password.

