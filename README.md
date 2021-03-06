# Linux Tracing Scripts
Author: Luca.Canali@cern.ch

This repository contains example scripts and tools for troubleshooting and performance analysis on Linux systems. It includes dynamic tracing scripts with FTrace, Perf, SystemTap, BPF/bcc.

| Directory                  | Short description
| -------------------------- | -------------------------------------------------------------------------------------
| [Ftrace](Ftrace)           | I/O latency histograms at microsecond resolution using ftrace
| [Perf](Perf_probes)               | Linux Perf and uprobes for Oracle tracing and profiling
| [SystemTap_Linux_IO](SystemTap_Linux_IO) | SystemTap scripts for Linux I/O tracing and I/O latency measurements
| [SystemTap_Userspace_Oracle](SystemTap_Userspace_Oracle) | SystemTap scripts for Oracle RDBMS troubleshooting and internals investigations using userspace dynamic tracing
| [BPF-bcc_Userspace_Oracle](BPF-bcc_Userspace_Oracle) | BPF/bcc scripts for Oracle userspace tracing, mostly ports from previous SystemTap and Perf work 

Disclaimer:
Many of the scripts provided here are experimental, may cause unwanted effect especially on busy production systems and overall may be incompatible with your current set-up and/or need some tweaking before running.

Acknowledgements:
- [Brendan Gregg](https://twitter.com/brendangregg) for many original ideas and tools that have inspired large parts of this work
- [Frits Hoogland](https://twitter.com/fritshoogland) for collaboration on investigating Oracle internals and userspace tracing
- Dev teams for Ftrace, SystemTap, Perf, BPF and bcc

