# Passwordless SSH

This repository describes SSH setup with SSH key authentication and complete disabling of password login.

## Prerequisites
- SSH key created on client
- Key added to server via ssh-copy-id
- Passwordless login verified

## Steps
1. Copy public key to server
2. Disable PasswordAuthentication
3. Restart SSH
