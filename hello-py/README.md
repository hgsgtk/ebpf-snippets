# an example in the iovisor/bcc project

See https://github.com/iovisor/bcc/blob/master/examples/tracing/hello_fields.py.

## Output example

```bash
# Open an another terminal and SSH to the same instance.
$ sudo -E python3 hello.py
TIME(s) COMM PID MESSAGE
1705.503414000 sshd 3211 Hi I'm Ao! Hello World!
1705.524882000 sshd 20891 Hi I'm Ao! Hello World!
1705.648679000 sshd 20891 Hi I'm Ao! Hello World!
1705.651274000 eic_run_authori 20893 Hi I'm Ao! Hello World!
1705.651654000 eic_run_authori 20894 Hi I'm Ao! Hello World!
1705.652070000 eic_run_authori 20895 Hi I'm Ao! Hello World!
1705.654456000 eic_run_authori 20893 Hi I'm Ao! Hello World!
1705.655617000 timeout 20897 Hi I'm Ao! Hello World!
...
```