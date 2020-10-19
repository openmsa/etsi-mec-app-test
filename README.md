# MEC Testing Framework in Robot Framework - GS 032-2

## Introduction
This repositories contains the test specifications and test adapter code for MEC Testing project in Robot Framework.

Latest publicly available drafts are available at https://docbox.etsi.org/isg/mec/open.


For more information on ETSI ISG Multi-access Edge Computing (MEC), visit https://www.etsi.org/technologies/multi-access-edge-computing.

## Contact information

Email at `cti_support` at `etsi` dot `org`.

## License
Unless specified otherwise, the content of this repository and the files contained are released under the BSD-3-Clause license.
See the attached LICENSE file or visit https://forge.etsi.org/legal-matters.

## Standard links
- Mobile-Edge Computation standards, accessible [here](https://www.etsi.org/standards#page=1&search=MEC&title=1&etsiNumber=1&content=1&version=0&onApproval=1&published=1&historical=1&startDate=1988-01-15&endDate=2019-05-06&harmonized=0&keyword=&TB=&stdType=&frequency=&mandate=&collection=&sort=1)

## RFC links
- RFC 7159 - The JavaScript Object Notation (JSON) Data Interchange Format, accessible [here](https://tools.ietf.org/html/rfc7159.html)

NOTE All draft can be found in the 'IETF XML Registry', accessible [here](https://www.iana.org/assignments/xml-registry/xml-registry.xhtml)


## Installation

The main precondition for running the tests is having [Robot Framework](http://robotframework.org/) installed.
The [Robot Framework Installation Instructions](https://github.com/robotframework/robotframework/blob/master/INSTALL.rst) provide full details of the installation procedure.
For those familiar with installing Python packages with [pip](http://pip-installer.org/) package manager, the following command can be run to install [Robot Framework](http://robotframework.org/):

[Robot Framework](http://robotframework.org/) >3.0 is recommended. It requires Python 3.

### Robot Framework Required Libraries
The [Robot Framework](http://robotframework.org/) Test Cases in this repository depend on the following libraries:

* [RESTInstance](https://github.com/asyrjasalo/RESTinstance)
* [DependencyLibrary](https://github.com/mentalisttraceur/robotframework-dependencylibrary)
* [JSONLibrary](https://github.com/nottyo/robotframework-jsonlibrary)
* [JSONSchemaLibrary](https://github.com/jstaffans/robotframework-jsonschemalibrary)
* [Requests](https://pypi.org/project/robotframework-requests/)

A [pip](http://pip-installer.org/) [requirements file](https://forge.etsi.org/rep/mec/gs032p3-robot-test-suite/blob/2.1.1-fix-plu/requirements.txt) is provided to ease the installation of the required python libraries, as follows:
```
$ pip install -r requirements.txt
```


## Usage

TODO


## How to Report a Bug

The ETSI MEC Testing Framework project is under constant development, so it is possible that you will
encounter a bug while using it. You may report in the [Issues section](https://forge.etsi.org/rep/mec/gs032p3-robot-test-suite/issues) of the project.

For any other inquiry, you may contact cti_support at etsi dot org.

