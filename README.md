# custom-linux-metrics

## Requirements

* Code that can be called from an external C/C++, from python, and/or from go-lang
* Code creates new or updates an existing file under `/proc` folder e.g.: `/proc/path/to/new-file`
* Path/file under /proc folder may not exist and must be created by the code transparently

## Acceptance Criteria

* Minimal dependencies, especially global/OS level dependencies
* Automated bash script to configure a brand new Ubuntu 16.04 instance to build & link
* Automated bash script to configure a brand new Ubuntu 16.04 instance to run the code
* Unit test(s) to validate the write to existent/nonexistent path
* Unit test(s) to validate the read from existent/nonexistent path without a crash
* A script to generate a distributable binary
* Sample code how to use the deliverable from an **external** C/C++ code
* Sample code how to use the binary from **Python and/or Go** code

## How to submit

* Fork
* Implement
* Commit to own repo
* Submit a pull request back to this repo
