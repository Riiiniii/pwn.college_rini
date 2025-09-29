# Challenge Name
Printing exported variables

## My solve
**Flag:** `pwn.college{Uc9eab4n85TlFTOa5tTpAooPV7N.QX4UTN0wyM3MzNzEzW}`

```bash
Connected!
hacker@variables~printing-exported-variables:~$ env
SHELL=/run/dojo/bin/bash
HOSTNAME=variables~printing-exported-variables
PWD=/home/hacker
MANPATH=/run/dojo/share/man:
DOJO_AUTH_TOKEN=605d371c22453dc2b16cdcd29808fbc546e0bcbb36d7b78bb651c563411c1a4a
HOME=/home/hacker
LANG=C.UTF-8
FLAG=pwn.college{Uc9eab4n85TlFTOa5tTpAooPV7N.QX4UTN0wyM3MzNzEzW}
TERMINFO=/run/dojo/share/terminfo
TERM=xterm-256color
SHLVL=2
LC_CTYPE=C.UTF-8
SSL_CERT_FILE=/run/dojo/etc/ssl/certs/ca-bundle.crt
PATH=/run/challenge/bin:/run/dojo/bin:/root/.cargo/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
DEBIAN_FRONTEND=noninteractive
_=/run/dojo/bin/env
hacker@variables~printing-exported-variables:~$ $FLAG
bash: pwn.college{Uc9eab4n85TlFTOa5tTpAooPV7N.QX4UTN0wyM3MzNzEzW}: command not found
```

## What I learned
I learnt about the "env" command. This command is used to print out every exported variable in the shell.
## References 
None.
