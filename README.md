# combined-docker-training

!! in den Ordnern: conten, mkdocs und router sind die urls noch fix auf den Trainigs servern !!

Wordpress hat probleme die domain aufzu lösen und ist nicht erreichbar
```
AH00558: apache2: Could not reliably determine the server's fully qualified domain name, using 172.22.0.7. Set the 'ServerName' directive globally to suppress this message,
AH00558: apache2: Could not reliably determine the server's fully qualified domain name, using 172.22.0.7. Set the 'ServerName' directive globally to suppress this message,
[Wed Dec 02 19:09:47.820938 2020] [mpm_prefork:notice] [pid 1] AH00163: Apache/2.4.38 (Debian) PHP/7.4.13 configured -- resuming normal operations,
[Wed Dec 02 19:09:47.821019 2020] [core:notice] [pid 1] AH00094: Command line: 'apache2 -D FOREGROUND',
[Wed Dec 02 19:11:39.193556 2020] [mpm_prefork:notice] [pid 1] AH00170: caught SIGWINCH, shutting down gracefully,
AH00558: apache2: Could not reliably determine the server's fully qualified domain name, using 172.27.0.3. Set the 'ServerName' directive globally to suppress this message,
AH00558: apache2: Could not reliably determine the server's fully qualified domain name, using 172.27.0.3. Set the 'ServerName' directive globally to suppress this message,
[Wed Dec 02 19:13:21.583027 2020] [mpm_prefork:notice] [pid 1] AH00163: Apache/2.4.38 (Debian) PHP/7.4.13 configured -- resuming normal operations,
[Wed Dec 02 19:13:21.583248 2020] [core:notice] [pid 1] AH00094: Command line: 'apache2 -D FOREGROUND',
```
