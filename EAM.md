**EAM ----**



**GRAC\_EAM** --> tcode to invoke FF ID --> Centralized system



**/n/GRCPI/GRIA\_EAM** --> invoke FF in backend system --> Decentralized system



**EAM:**

Emergency access management is used to provide privileged access to the users by separating the most critical authorizations from regular user access.



**How to Maintain Firefighters and Controllers?**

**NWBC  Setup Emergency access Maintenance  Firefighters, Controllers**



**How to Map the FFIID's?**

**NWBC  Setup Emergency access Assignment  Owners, Firefighter IDs**





EAM: Emergency Access Management

FFID: Will contain the additional access which is needed to complete the activity. SAP\_GRAC\_SPM\_FFID



FF: Firefighter user who needs access to FFID. SAP\_GRAC\_SUPER\_USER\_MGMT\_USER



FF Owner: Is the responsible to approve this access. SAP\_GRAC\_SUPER\_USER\_MGMT\_OWNER



FF Controller: Is the responsible person to review the logs of FFID. SAP\_GRAC\_SUPER\_USER\_MGMT\_CNTLR



Pre-requisites to use EAM:

1\)	Activate the BC-Sets

2\)	Set the parameter

3\)	Audit logs needs to be activated in the backend system.



EAM types/Application types:

1\)	ID -Based	: FFID

2\)	Role-Based 	: Directly the role will be assigned to the user.



We have two types in ID based EAM:

1\)	Centralized 

2\)	De-Centralized



Firefighter, FF owner, FF Controller have to be created in GRC system with user type: Dialog.

FFID will be created in the backend system with user type: Service.



What are the important parameters for EAM?

4000 – Application type: 1 (ID Based)

4010  - FFID role name: 





