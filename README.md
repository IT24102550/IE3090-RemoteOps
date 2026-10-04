# RemoteOps - Remote System Monitoring Tool

**Student:** IT24102550
**Module:** IE3090 - Network Programming

## Personalised Values
- **Agent Port:** 9410
- **SID:** 552
- **Auth Token:** OPS-2550
- **Log File:** remoteops_IT24102550.log
- **Storage Path:** ./agentfiles/IT24102550/

## Build
make -f Makefile_550

## Run
./agent_550
./controller_550

## Features
- AUTH authentication
- SYSINFO (CPU, memory, uptime)
- LISTPROC (process list)
- EXEC (whitelisted: DATE, UPTIME, DISKFREE, HOSTNAME, WHOAMI)
- PUT/GET (file transfer)
- Multiple clients (threads)
- UDP monitoring (MONITOR START/STOP)
- Logging
