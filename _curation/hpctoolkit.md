---
layout: page
title: HPCToolkit
category: 
  - Research Profilers
  - Profiling Tools
  - Tracing Tools
os_support:
  - Linux
  - Windows
  - macOS
thumbnail:
gallery:
social:
    website: http://hpctoolkit.org/
    github: https://github.com/HPCToolkit/hpctoolkit
    twitter:
    facebook:
    reddit: 
    youtube: 
    twitch: 
    docs: http://hpctoolkit.org/manual/HPCToolkit-users-manual.pdf
tagline: HPCToolkit is an integrated suite of tools for measurement and analysis of program performance on computers ranging from multicore desktop systems to the nation's largest supercomputers.
---
HPCToolkit is an integrated suite of tools for measurement and analysis of program performance on computers ranging from multicore desktop systems to the nation's largest supercomputers. By using statistical sampling of timers and hardware performance counters, HPCToolkit collects accurate measurements of a program's work, resource consumption, and inefficiency and attributes them to the full calling context in which they occur. HPCToolkit works with multilingual, fully optimized applications that are statically or dynamically linked. Since HPCToolkit uses sampling, measurement has low overhead (1-5%) and scales to large parallel systems. HPCToolkit's presentation tools enable rapid analysis of a program's execution costs, inefficiency, and scaling characteristics both within and across nodes of a parallel system. HPCToolkit supports measurement and analysis of serial codes, threaded codes (e.g. pthreads, OpenMP), MPI, and hybrid (MPI+threads) parallel codes.

These are the primary components of HPCToolkit:
* **hpcrun**: hpcrun collects accurate and precise calling-context-sensitive performance measurements for unmodified fully optimized applications at very low overhead (1-5%). It uses asynchronous sampling triggered by system timers and performance monitoring unit events to drive collection of call path profiles and optionally traces.
* **hpcstruct**: To associate calling-context-sensitive measurements with source code structure, hpcstruct analyzes fully optimized application binaries and recovers information about their relationship to source code. In particular, hpcstruct relates object code to source code files, procedures, loop nests, and identifies inlined code.
* **hpcprof**: hpcprof overlays call path profiles and traces with program structure computed by hpcstruct and correlates the result with source code. hpcprof/mpi handles thousands of profiles from a parallel execution by performing this correlation in parallel. hpcprof and hpcprof/mpi generate a performance database that can be explored using the hpcviewer user interface.

HPCToolkit is part of the ECP which is a collaborative effort of two US Department of Energy (DOE) organizations - the Office of Science (DOE-SC) and the National Nuclear Security Administration (NNSA).
