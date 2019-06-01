# custom-linux-metrics

## Requirements

* Code that can be called from an external C/C++, from python, and/or from go-lang
* Code creates new or updates an existing file under `/proc` folder e.g.: `/proc/path/to/new-file`
* Path/file under /proc folder may not exist and must be created by the code transparently
* Input: filePath e.g. `/path/to/file`, string content e.g. `key: "value"`, appendFlag e.g. `true`
* Exception details in case of a failure

## Acceptance Criteria

* Minimal dependencies, especially global/OS level dependencies
* String buffer overflow validation
* Automated bash script to configure a brand new Ubuntu 16.04 instance to build & link
* Automated bash script to configure a brand new Ubuntu 16.04 instance to run the code
* Unit test(s) to validate the write to existent/nonexistent path
* Unit test(s) to validate the read from existent/nonexistent path without a crash
* Unit test(s) to validate replacing vs. appending content to the file
* Unit test(s) to validate exception handling called from C/C++ and from Python/Go
* A script to generate a distributable binary
* Sample code how to use the deliverable from an **external** C/C++ code without launching a process
* Sample code how to use the binary from **Python and/or Go** code without launching a process

## How to submit

* Fork
* Implement
* Commit to own repo
* Submit a pull request back to this repo
