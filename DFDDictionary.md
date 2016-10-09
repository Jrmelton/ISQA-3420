#Entities

###Developer
A person that submits Software Packages to be populated into the database as well as requests Policy information.

###Manager
A user that submits requests for Software  Package information from the Software Package License and Vulnerabilities Results Database as well as sumbits requests for adding new policies, modifying policies, and obtaining policy information in the Policy Database.

#Datastores

###Software Package License and Vulnerabilities Results Database
A database containing the results from the Policy Scan and Vulnerability Check.

###NIST Vulnerabilities Database
A database containing vulnerability information used for checking a Software Package.

###Policy Database
A database containing policy information used by both a Manager and a Developer.

#Processes

###Manage Software Package for License Scanning/Vulnerabilies Check
A process used by a developer that forwards software packages to scan for licenses and check for vulnerabilities as well as storing the data within the Software Package License and Vulnerabilities Results Database and reporting results back to the developer.

###Manage Software Vulnerabiltiy Checking
A process to check the NIST Vulnerability Database for vulnerabilities using the Software Package to be sent back to the Developer and recorded within the Software Package License and Vulnerabilities Results Database via the Manage Software Package for License Scanning/Vulnerabilies Check.

###Scan for Licenses
A process to scan the Software Package to verify license information to be sent back to the Developer and recorded within the Software Package License and Vulnerabilities Results Database via the Manage Software Package for License Scanning/Vulnerabilies Check.

###Query the Database to Retrieve all Software Package License and Vulnerability Information
A process used by the manager to retrieve the information located within the Software Package License and Vulnerability Information Database for a software package and return the information to the manager.

###Query the Policy Database
A process used by both manager and developer to check the policy database for policy information.

###Add or Modify Policy
A process used by a manager to add a new policy to or modify an existing policy within the policy database.

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
A request made by a manager or developer to obtain information from the Software Package License and Vulnerabilities Results Database regarding a specific software package.

###Software Package License and Vulnerability Information Response
A response from the Software Package License and Vulnerabilities Results Database for the manager or developer.

###Policy Information Request
A request made by a manager or developer to obtain information from the Policy Database regarding a specific software package.

###Policy Information Response
A response from the Policy Database for the manager or developer.

###New Policy
A policy submitted by the manager to be added into the Policy Database.

###Modify Policy
A modified policy submitted by the manager to be updated within the Poliocy Database.
