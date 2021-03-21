# pispotify
Ansible project to configure Raspberry Pi to run raspotify based on default raspian box.
Setup will install raspotify and then configure it to use USB card instead of audio jack and stream with high quality.

## Installation
- Update the Raspberry Pi IP in the inventory
- Update configuration options like Spotify credentials in main.yml
- Run the following command:
```ansible-playbook main.yml -i inventory -k```
- Enter the SSH PW when prompted or set up ssh keys.

## Acknowledgements

This project is based on [raspotify](https://github.com/dtcooper/raspotify)