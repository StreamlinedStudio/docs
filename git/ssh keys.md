
#SSH Keys

- You can copy your ssh keys from one environment to another.
- After doing so you will need to reset the permissions within the new environment.

    chmod 600 ~/.ssh/id_rsa
    chmod 600 ~/.ssh/id_rsa.pub

- you may have to use sudo
    sudo chmod 600 ~/.ssh/id_rsa
    sudo chmod 600 ~/.ssh/id_rsa.pub