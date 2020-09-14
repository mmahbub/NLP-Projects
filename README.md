# This repo contains codes for NLP project assignments. 
# Memory Hierarchy Simulator

This program simulates the behavior of a memory hierarchy. The hierarchy includes a data translation look-aside buffer (DTLB), page table (PT), first level data cache (DC),
and a second level data cache (L2). The program reads a trace of references from standard input and produce statistics about the trace to standard output. 

Run `memhier_simulator.py` file using the following commands on the command line:

python3 memhier_simulator.py <config_file> <trace_data>

example: python3 memhier_simulator.py trace.config trace.dat
