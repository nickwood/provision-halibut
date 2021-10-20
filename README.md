# Provisioning Arch/Manjaro Linux

 * `sudo pacman -Syy ansible`
 * `ansible-galaxy collection install -r requirements.yml`
 * `ansible-playbook provision_halibut.yml --ask-become-pass`
