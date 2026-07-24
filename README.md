# ansible-forgejo
forgejo ansible-pull

## TLDR;

```bash
/opt/ansible_env/bin/ansible-pull -U https://github.com/rhildred/ansible-forgejo.git
```

## Security

Registration is disabled by ansible-pull. Set up your authentication sources like ldap or github in the web ui. When you create a user choose their authentication source. For github, I had to give the user a single use password. When the user first logged in they needed to use the password to link to the account. It isn't needed for successive logins. 
