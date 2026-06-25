Table	Purpose / Usage
USRACL	Stores system assignments for users in a CUA landscape. Defines which child systems a user belongs to.
USRCON	Contains connection information between the central system and child systems.
USRCUA	Holds CUA-specific user data, including distribution details.
USRDCF	Distribution model configuration for CUA (links to BD64).
USRLOG	Logs of user distribution activities (similar to SCUL transaction).
**USR02	Standard user master table (passwords, logon data) — replicated in CUA.
USR04	User to profile assignments — replicated across systems.**
USRACLEXT	Extended system assignment details for users.
USRSYSACT	Tracks active systems for a user in CUA.



Table	Purpose / Usage
AGR\_DEFINE	Stores role definitions (role name, description, creation details). Useful for identifying all roles in the system.

AGR\_USERS	Role-to-user assignments — distributed by CUA.
AGR\_USERT	Similar to AGR\_USERS, but includes time-dependent assignments.
AGR\_TCODES	Lists transaction codes assigned to roles. Helps in analyzing which transactions a role provides access to.
AGR\_1251	Contains authorization objects linked to a role. Key fields: AGR\_NAME, AUTH\_OBJECT, FIELDNAME. Used to see detailed authorization data.
AGR\_1252	Stores field values for authorization objects in roles. Provides granular control

