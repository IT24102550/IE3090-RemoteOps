# Design Diary - IE3090 RemoteOps (IT24102550)

## Day 1: Socket Programming Basics
- Learned TCP socket programming in C
- Created hello_server.c and hello_client.c for practice
- Chose thread-per-client concurrency model

## Day 2: Personalisation & AUTH
- Calculated personalised values (port 9410, SID 552, token OPS-2550)
- Implemented AUTH command with token validation

## Day 3: System Commands
- Added SYSINFO using sysinfo() syscall
- Added LISTPROC using popen() with ps command
- Fixed memory buffer warnings

## Day 4: EXEC & File Transfer
- Implemented whitelisted EXEC commands
- Added PUT/GET with binary file handling

## Day 5: Concurrency & UDP
- Added pthreads for multiple clients
- Implemented UDP monitoring thread with mutex

## Day 6: Logging
- Added log_event() function with timestamps
- Tested full system integration

## Challenges Faced
1. Makefile case sensitivity
2. Buffer overflow warnings - fixed with sizeof()
3. Function prototype ordering
4. Port already in use - pkill before restart
