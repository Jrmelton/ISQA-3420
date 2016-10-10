#Entities

###Developer
A person that submits software packages to be populated into the Software Package License and Vulnerabilities Results Database as well as requests Policy information.

###Manager
A user that submits requests for software package information from the Software Package License and Vulnerabilities Results Database as well as sumbits requests for adding new policies, modifying policies, and obtaining policy information in the Policy Database.

#Datastores

###Software Package License and Vulnerabilities Results Database
A database containing software package results from the Policy Scan and Vulnerability Check processes.

###NIST Vulnerabilities Database
A database containing vulnerability information used for checking software packages.

###Policy Database
A database containing policy information for software packages. It is accessed by both a Manager and a Developer.

#Processes

###Manage Software Package for License Scanning/Vulnerabilies Check
A process used by a developer that forwards software packages to Manage Software Vulnerabiltiy Checking and Scan for Licenses, stores the data within the Software Package License and Vulnerabilities Results Database, and reports results back to the developer.

###Manage Software Vulnerabiltiy Checking
A process to check the NIST Vulnerability Database for vulnerabilities using the software package submitted. The information is then sent back to the Software Package for License Scanning/Vulnerabilies Check process.

###Scan for Licenses
A process to scan the software package to verify license information. The information is then sent back to the Software Package for License Scanning/Vulnerabilies Check process.

###Query the Database to Retrieve all Software Package License and Vulnerability Information
A process used by the manager and developer to retrieve the information located within the Software Package License and Vulnerability Information Database for a software package. The information is then returned to the manager or developer.

###Query the Policy Database
A process used by both manager and developer to check the Policy Database for software package policy information.

###Add or Modify Policy
A process used by a manager to add a new policy to or modify an existing policy within the Policy Database.

#Dataflows

###Software Package
The software submitted by the developer to be scanned for licenses, checked for vulnerabilities, and populated into the Software Package License and Vulnerabilities Results Database.

###Software Package Name
The specific name of a software package to be used for checking the NIST Vulnerabilities Database for software vulnerabilities.

###Published Known Vulnerabilities
Specific software vulnerabilties within the NIST Vulnerability Database classified with the specific software package license information to be stored within the Software Package License and Vulnerabilities Results Database.

###Software Package License Results
Specific software licenses to be stored within the Software Package License and Vulnerabilities Results Database with the corresponding software package's published known vulnerabilities.

###Software Package License and Vulnerability Information Request
A request made by a manager or developer to obtain information from the Software Package License and Vulnerabilities Results Database.

###Software Package License and Vulnerability Information Response
A response from the Software Package License and Vulnerabilities Results Database for the manager or developer.

###Policy Information Request
A request made by a manager or developer to obtain information from the Policy Database.

###Policy Information Response
A response from the Policy Database for the manager or developer.

###New Policy
A policy submitted by the manager to be added into the Policy Database.

###Modify Policy
A modified policy submitted by the manager to be updated within the Poliocy Database.
