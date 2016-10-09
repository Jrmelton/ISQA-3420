Entities

Developer: A person that submits Software Packages to be populated into the database as well as requests Policy information.

Manager: A user that submits requests for Software  Package information from the Software Package License and Vulnerabilities Results Database as well as sumbits requests for adding new policies, modifying policies, and obtaining policy information in the Policy Database.

Datastores
Software Package License and Vulnerabilities Results Database: A database containing the results from the Policy Scan and Vulnerability Check.

NIST Vulnerabilities Database: A database containing vulnerability information used for checking a Software Package.

Policy Database: A database containing policy information used by both a Manager and a Developer.

Processes

Manage Software Package for License Scanning/Vulnerabilies Check: a process used by a developer that forwards software packages to scan for licenses and check for vulnerabilities as well as storing the data within the Software Package License and Vulnerabilities Results Database.

Manage Software Vulnerabiltiy Checking:

Scan for Licenses:

Query the Database to Retrieve all Software Package License and Vulnerability Information:

Query the Policy Database:

Add or Modify Policy:

Dataflows

Software Package: The software submitted by the developer to be scanned for OSS licenses and populated into the databse.

Software Package Name:

Published Known Vulnerabilities:

Software Package License Results:

Software Package License and Vulnerability Information Request:

Software Package License and Vulnerability Information Response:

Policy Information Request:

Policy Information Response:

New Policy:

Modify Policy:
