# SymbianDevNetCode
There dump various tools with src from http://developer.symbian.com

## AnalyseRemoteHeap
This package contains the source files which implement a run-time version of AnalyseHeap for dumping the heaps of other ("remote") threads, which may be in other processes.

## AnalyseHeap Utility
This tool analyses the contents of Symbian OS heaps to produce meaningful representations of their structure and content. It reads in the heap file, and walks the heap structure contained in it. From this, it builds a set of all the allocated and free heap cells. These are then cross referenced so that ownership relationships can be identified.

## C++ Template Source Generators
This package contains utilities (Perl scripts) capable of automatically generating C++ template source code for various purposes in order to assist the developers.

## ProfileEngine
This contains the source code for a lightweight profiling tool which can be linked to an application or library under development.
It does not require modification of the ROM, so it is useful when developing with an SDK or production device.
