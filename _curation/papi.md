---
layout: page
title: PAPI
category: 
  - Performance Data Collectors
os_support:
  - Linux
thumbnail:
gallery:
social:
    website: https://icl.utk.edu/exa-papi/
    github: https://bitbucket.org/icl/papi
    twitter: https://twitter.com/icl_utk?lang=en
    facebook:
    reddit: 
    youtube: https://www.youtube.com/channel/UC9hJuvuwDdTLRdKb3oCSr-Q
    twitch: 
    docs: https://bitbucket.org/icl/papi/wiki/Home
tagline: The Performance Application Programming Interface (PAPI) provides tool designers and application engineers with a consistent interface and methodology for the use of low-level performance counter hardware found across the entire compute system.
---
The Performance Application Programming Interface (PAPI) provides tool designers and application engineers with a consistent interface and methodology for the use of low-level performance counter hardware found across the entire compute system (i.e. CPUs, GPUs, on/off-chip memory, interconnects, I/O system, energy/power, etc.). PAPI will enable users to see, in near real time, the relations between software performance and hardware events across the entire computer system.

The ECP Exa-PAPI project builds on the latest PAPI project and extends it with:
* Performance counter monitoring capabilities for new and advanced ECP hardware, and software technologies.
* Fine-grained power management support.
* Functionality for performance counter analysis at "task granularity" for task-based runtime systems.
* "Software-defined Events" that originate from the ECP software stack and are currently treated as black boxes (i.e., communication libraries, math libraries, task-based runtime systems, etc.).

The objective is to enable monitoring of both types of performance events---hardware- and software-related events---in a uniform way, through one consistent PAPI interface. Third-party tools and application developers will have to handle only a single hook to PAPI in order to access all hardware performance counters in a system, including the new software-defined events.
