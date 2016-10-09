#Use Case 1:
Title: Determine License and Vulnerability Information

Primary Actor: Manager

Goal in Context: The manager is able to determine license and vulnerability information from provided project information

Stakeholders: Manager, Developer

Preconditions:
  Relevant file/package information is in the database
  Proper project information has been provided

Main Success Scenario: Manager receives accurate license and vulnerability information for the requested project packages

Failed End Conditions: Manager receives inaccurate or invalid license and vulnerability information for the requested project packages

Trigger: Manager sends the request for all license and vulnerability information

#Use Case 2:
Title: Add New Policy

Primary Actor: Manager

Goal in Context: Manager adds a new policy to the Policy Database.

Stakeholders: Manager, Developer

Preconditions:
  Policy Database is accessible.

Main Success Scenario: New policy is added into Policy Database.

Failed End Conditions: The policy is not successfully added into the Policy Database.

Trigger: Manager submits a new policy.

#Use Case 3:
Title: Modify Policy

Primary Actor: Manager

Goal in Context: Manager modifies an existing policy within the Policy Database.

Stakeholders: Manager, Developer  

Preconditions:
  The Policy Database is accessible.
  The Policy Database contains the policy intended to be modified.

Main Success Scenario: The intended policy to be modified is modified successfully within the Policy Database.

Failed End Conditions: The policy s unsuccessfully modified.

Trigger: Manager submits a modified policy to be updated.
