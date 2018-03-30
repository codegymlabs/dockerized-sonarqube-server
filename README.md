Dockerized SonarQube Server
===

System Requirements
---

Modern Linux system, recommended with 1Gb available RAM at least; `docker` and 
`docker-compose` worked-well is required, too.

Build and start server
---

```bash
git clone https://github.com/codegymlabs/dockerized-sonarqube-server
cd dockerized-sonarqube-server
./up.sh
```

After server started, you can logged in with username and password is `admin` both.

Logging
---

Show logs and fetch log into file:

```bash
./log.sh
./log.sh >> sonar-log.log
```

...follow logs:

```bash
./log.sh -f
```

Teleport into server machine
---

```bash
./ssh.sh
```

Stopping
---

```bash
./stop.sh
```

Uninstall
---

```bash
./uninstall.sh
```

From codegym with <3

Thanks,