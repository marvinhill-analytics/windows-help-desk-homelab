Ticket Number: 003
Title: Unable to Access Sales Department Folder
User: Jasmine Reed
Username: jreed
Department: Sales
Priority: Medium
Status: Open

Problem Reported:
Jasmine Reed can sign in to her Windows account, but she receives an Access Denied message when attempting to open the Sales department folder.

Business Impact:
The user cannot access or update files required for her Sales duties.

Manager Approval:
The Sales manager confirmed that Jasmine Reed requires access to the Sales department folder.

Requested Access:
Read, create, edit, and save files inside the Sales department folder.

Security Requirement:
The user must receive only the permissions required for her job. The jreed account must remain a standard user and must not be added to the Administrators group.

Steps Performed:
1. Signed in using the HTSAdmin administrator account.
2. Opened the Security properties for the Sales folder.
3. Reviewed the permissions assigned to the jreed account.
4. Identified an explicit Deny permission that blocked access.
5. Removed the Deny permission.
6. Granted Modify permission to Jasmine Reed.
7. Signed in using the jreed account.
8. Opened the Sales folder.
9. Edited Customer_List.txt.
10. Created and saved Sales_Test_File.txt.

Root Cause:
The jreed account had an explicit Deny permission on the Sales folder. Deny permissions override allowed permissions and prevented Jasmine Reed from accessing the folder.

Verification:
Jasmine Reed successfully opened the Sales folder, edited an existing file, and created a new file.

Resolution:
Removed the incorrect Deny permission and granted Modify access to the jreed account.

Final Status:
Closed