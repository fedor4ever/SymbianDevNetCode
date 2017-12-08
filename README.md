# SymbianDevNetCode
There dump various tools with src from http://developer.symbian.com

## AnalyseRemoteHeap
This package contains the source files which implement a run-time version of AnalyseHeap for dumping the heaps of other ("remote") threads, which may be in other processes.

## AnalyseHeap Utility
This tool analyses the contents of Symbian OS heaps to produce meaningful representations of their structure and content. It reads in the heap file, and walks the heap structure contained in it. From this, it builds a set of all the allocated and free heap cells. These are then cross referenced so that ownership relationships can be identified.
