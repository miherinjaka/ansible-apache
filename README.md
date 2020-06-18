## To run:

```bash
$  ansible-playbook install.yml -e 'ansible_python_interpreter=/usr/bin/python3' -b -K
```

```bash
-b : as we need to become root for this operation
-K : because sudo still requires password
```
 

