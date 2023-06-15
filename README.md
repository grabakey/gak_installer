# Grabakey OpenSSH Plugin

Let grabakey serve your sshd public keys.

## Howto

- Create a public key with:
```bash
curl https://grabakey.org/api/pubkey -d <EMAIL>
```
- Follow instructions on received confirmation email.

## Requirements

- openssh with `sshd_config.d` support
- openssh with `ed25519` support
- bash, sudo, curl, git, echo, mkdir, cat, tee, uname

## Compatibility

- ubuntu-server-22.04
