McSecurity
==========

McSecurity is a suite of programs designed to emulate network functions virtually.
These inclue:

1. mcProxy - A CLI tool that can create a reverse proxy that will route requests to a list of application servers.
2. mcLogger - Keeps a tab on the actions for the system.

mcProxy
-------

Usage:

```bash
$ mcproxy <SUBCOMMAND> [ARGUEMENTS]
```

Sub-Cmd | Explanation
--------|-----------
build | creates a reverse proxy profile that can be mounted to
mount | adds a business server that proxy should route to
unmount | removes a business server that proxy has mounted
run | runs instance of selected profile
profiles | list out mcProxy profiles
remove | removes a profile from memory


### add
```bash
$ mproxy add _proxy-name_ _proxy-port_
```
#### Requirements

* Business:
Develop your own networking programs to watch, modify, and route network traffic to your HTTP server apps. Functions may be implemented as one application binary, or as several binaries.
* Solution:
    1. Functional
    2. Quality
        - [X] Documentation
        - [X] Agile Project Management
        - [ ] Unit Testing
        - [ ] Logs & Metrics
        - [ ] Environment Configuration
        - [X] Secuirty
        - [X] Build & Deploy Scripts
        - [ ] Containerization
    3. Performance
* Stakeholder & Legal:
    * 10 Minute Demonstration
    * Presentation Slides
