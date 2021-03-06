Database

NIST Vulnerability Database: Checks and stores for vulnerabilities on software packages. 

OSS Component Database: Stores software package license and vulnerability results.



Dataflow

Add Policy Documents: To add policy documents to the Manage Policy Documents process.

Known Vulnerability Results: Reveils vulnerability results on software packages to send to the Manage Software Package for License Scanning.

Request Software Project Policy: Entities and processes are able to request for software project policies.

Request Software Package License and Vulnerability Results: Entities and processes are able to request for software package license and vulnerability results.

Software Package Name: Name of software package sent to NIST Vulnerability Database.

Software Package: Component that is used to create projects.

Software Package License and Vulnerability Results: Results for licenses and vulnerabilites for software packages.

Software Project Policy: Policies in software projects. 

Update Policy Documents: To update policy documents on the Manage Policy Documents process.



Entities 

Developer: Sends software packages to be scanned for licenses and vulnerabilities. Receives software project policies and project licenses and vulnerabilities.

Manager: Requests and receives software project policies and project licenses and vulnerabilities. Can add or update project policies.


Processes

Manage Software Package for License Scanning: Manages software packages for license scanning.

Manage Software Package License for Project Scanning: Manages software package licenses for project scanning.

Manage Policy Documents: Manages policy documents that the manager may add or update policies.

Query DB for All Software Packages and License Information: Manages requests from manager and developer for project license and vulnerability results.

Scan for Licenses: Scans for licenses in software packages.

