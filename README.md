# ansiblerole-sshd

---

Basic Installation and Configuration of openssh-server on Linux (Ubuntu OS).
This role offer some security features, configured in SSHD configuration file.
By Default, openssh deamon allow many things, that can be used by hackers.

*Main functions of the Role:*

- Defining TCP port, on which SSHD deamon will be Listening;
- Binding SSHD deamon to Default IP address;
- Disable Root Login;
- Defined special users of OS, that can connect through SSH;
- Disable TCP Redirection (Can be Enabled with special Variable).


----

**Author of the Role** - Andrey Useinov aka andreyus.
