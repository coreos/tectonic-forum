# Tectonic Community Forum

Welcome to the Community Forum for Tectonic, the Enterprise Kubernetes Solution. 

## Tectonic resources

Documentation: https://coreos.com/tectonic/docs/latest/

Product Feedback: tectonic-feedback[at]coreos.com

## Reporting issues

This Community Forum is primarily for helping each other work through issues, reporting bugs, identifying requirements for more documentation, or submitting feature requests for Tectonic.

### Opening an issue

If you find bugs or documentation issues in any part of Tectonic, please let us know by [opening an issue](https://github.com/coreos/tectonic-forum/issues). We treat bugs and mistakes very seriously and believe no issue is too small. Before creating a bug report, please check that an issue reporting the same problem does not already exist.

To make the bug report accurate and easy to understand, please try to create issues that are:

* _Specific_. Include as much details as possible: which version, what environment, what configuration, etc.

* _Reproducible_. Include the steps to reproduce the problem. We understand some issues might be hard to reproduce, but please attempt to include as much information as is necessary for the bug to be reproduced by others.

* _Isolated_. Please try to isolate and reproduce the bug with minimal dependencies. Too many dependencies can significantly slow down the speed of diagnosing and fixing a bug.

* _Unique_. Please search [existing issues](https://github.com/coreos/tectonic-forum/issues) before filing a new one to see if your bug has already been reported. Do not duplicate existing bug reports.

* _Scoped_. One bug per issue; please do not follow up with another bug inside one report. It may be worthwhile to read [Elika Etemad’s article on filing good bug reports](http://fantasai.inkedblade.net/style/talks/filing-good-bugs/) before creating a bug report.

We might ask for further information to locate a bug. A duplicated bug report will be closed.

#### Tectonic Installer Progress file

Click the *Save progress* button at the top right corner of any Installer screen to download a snapshot of install configuration and progress. A JSON-formatted file named `tectonic-progress` will be written beneath the browser's default download path. Including the Progress file from a failed installation can assist troubleshooting.

Before sending a Progress file, ensure that the potentially sensitive values of the following keys are removed or obscured from the Progress file:

* AWS access key (`awsAccessKeyId`)

* AWS secret (`awsSecretAccessKey`)

* Tectonic key (`accountID`)

* Tectonic secret (`accountSecret`)

* Tectonic license (`tectonicLicense`)

* Pull secret (`pullSecret`)
