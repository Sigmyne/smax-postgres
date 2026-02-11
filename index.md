---
excerpt: Record SMA-X history in PostgreSQL / TimescaleDB
---

<img src="/smax-postgres/resources/Sigmyne-logo-200x44.png" alt="Sigmyne logo" width="200" height="44" align="right"><br clear="all">

__smax-postgres__ is a daemon application, which can collect data from an SMA-X realtime database and insert these 
into a PostgreSQL database to create a time-series historical record for all or selected SMA-X variables. The program 
is highly customizable and supports both regular updates for changing variables as well as regular snapshots of all 
selected SMA-X variables.

The __smax-postgres__ applications was created, and is maintained, by Attila Kovács (Sigmyne, LLC), and it is 
available through the [Sigmyne/redisx](https://github.com/Sigmyne/smax-postgres) repository on GitHub. 

This site contains various online resources that support the library:

__Downloads__

 - [Releases](https://github.com/Sigmyne/smax-postgres/releases) from GitHub

__Documentation__

 - [User's guide](doc/README.md) (`README.md`)
 - [API Documentation](apidoc/html/files.html)
 - [History of changes](doc/CHANGELOG.md) (`CHANGELOG.md`)
 - [Issues](https://github.com/Sigmyne/smax-postgres/issues) affecting __smax-postgres__ releases (past and/or present)
 - [Community Forum](https://github.com/Sigmyne/smax-postgres/discussions) &ndash; ask a question, provide feedback, or 
   check announcements.

__Dependencies__

 - [Sigmyne/smax-clib](https://github.com/Sigmyne/smax-clib) -- structured data exchange framework
 - [Sigmyne/redisx](https://github.com/Sigmyne/redisx) -- A C/C++ Redis client library
 - [Sigmyne/xchange](https://github.com/Sigmyne/xchange) -- structured data exchange framework
 - [Smithsonian/smax-server](https://github.com/Smithsonian/smax-server) -- SMA-X server configuration kit
 - PostgreSQL development files (`libpq.so` and `lipq-fe.h`)
 - __Popt__ (command-line options parsing) library development files (`libpopt.so` and `popt.h`)
 - (optional) __systemd__ (runtime management) development files (`libsystemd.so` and `sd-daemon.h`)
 
