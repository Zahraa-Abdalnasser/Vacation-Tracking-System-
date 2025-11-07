# Vacation-Tracking-System-
A system to able employees manage their vacations easily 

# The Problem Domain 
In the past employees have to upply some papers to every manager they are working with ( because one employee can has many projects so they work on many projects ) 
but with VTS they can apply one time and all managers can know who is in vaction and who is working 

# System Vision 
A Vacation Tracking System (VTS) will provide individual employees with the 
capability to manage their own vacation time, sick leave, and personal time off, 
without having to be an expert in company policy or the local facility’s leave 
policies.

# The System Actors 
Normal employee , HR , Manager and System admin

# Functional Requirements 
 ■ Implements a flexible rules-based system for validating and verifying leave 
time requests
 ■ Enables manager approval (optional)
 ■ Provides access to requests for the previous calendar year, and allows 
requests to be made up to a year and a half in the future
 ■ Uses e-mail notification to request manager approval and notify employees 
of request status changes
 ■ Keeps activity logs for all transactions
 ■ Enables the HR and system administration personnel to override all actions 
restricted by rules, with logging of those overrides
 ■ Allows managers to directly award personal leave time (with system-set 
limits)
 ■ Provides a Web service interface for other internal systems to query any 
given employee’s vacation request summary
 ■ Interfaces with the HR department legacy systems to retrieve required 
employee information and changes

# Non Functional Requirements 
 ■ Uses existing hardware and middleware
 ■ Is implemented as an extension to the existing intranet portal system, and 
uses the portal’s single-sign-on mechanisms for all authentication

# Constrains 
The logged in employee must have some balance to send a new vaction requist 

# Assumptions 
The employee should have access to a visual calendar 
to help select and compare selected dates
# Psudocode 
![Diagram](https://raw.githubusercontent.com/Zahraa-Abdalnasser/Vacation-Tracking-System-/refs/heads/main/VTS%20Psudocode.drawio.svg)
# Sequence diagram
![Diagram](https://raw.githubusercontent.com/Zahraa-Abdalnasser/Vacation-Tracking-System-/refs/heads/main/VTS%20Sequence%20Diagram.drawio.svg)






