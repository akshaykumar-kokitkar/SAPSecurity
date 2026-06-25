# **ARA --------**



**Business risk:**



Business risk in SAP is the chance of negative impact on organizational objectives due to system, process, or compliance issues. A001 -risk, BS02, BS03 -Functions



**SOD:**



SOD (Segregation of Duties) in SAP means making sure that no single user has conflicting authorizations that could allow them to perform an entire critical process end-to-end without oversight. It’s a key control to prevent fraud and errors.





Step	Activity	Common SAP Tcodes	Risk if Same User Has Both

* 1	Create Vendor Master	XK01, FK01	User could create fake vendor
* 2	Create Purchase Order	ME21N	User could order goods/services for fake vendor
* 3	Goods Receipt	MIGO	User could confirm receipt of goods never delivered
* 4	Invoice Posting	MIRO	User could post invoice for fake goods
* 5	Payment Run	F110	User could pay themselves via fake vendor





**Mitigation Control:**



The mitigation allows you to mitigate certain risk violations that you want available for certain users or roles



###### **Remediation	- Removing the risk**

###### **Mitigation	- Allowing the risk to the user with some control.**





**Steps: ARA access risk analysis**

**Action** : T-codes

**Permission** : Authorizations

**Function** : Contains Actions and/or Permissions.

**SoD Risk** : Is a combination of 2 or more functions

**Rule** : Whenever we generate the Risk ID, rule will be created

**Ruleset** : Is a container of the rules.

**Risk Owner**:

A risk owner is the individual responsible for managing, mitigating, and monitoring a specific risk within an organization, ensuring accountability and alignment with organizational objectives.





\----------------------------------------------------------------------



###### **How to perform the risk analysis:**

###### **NWBC  Access Management  User level**



###### **How to create a Rule set?**

###### **NWBC  Setup  Rule sets  Create**



###### **How to create a Function?**

###### **NWBC  Setup Functions  Create**



###### **How to create a Access Risk? *Rule set is mandatory \& generate risk***

###### **NWBC  Setup Access Risks  Create**



###### **How to Maintain Access Control Owner?**

###### **NWBC  Setup Access Owners  Access Control. *Owners FF Cntrl \& owner***



###### **How to create a Mitigating Control? contain Approver \& Monitor**

###### **NWBC  Setup Mitigating Controls  Create MID**



###### **How to Maintain Firefighters and Controllers?**

###### **NWBC  Setup Emergency access Maintenance  Firefighters, Controllers**



###### **How to Map the FFIID's?**

###### **NWBC  Setup Emergency access Assignment  Owners, Firefighter IDs** 



###### **-------------------------------------------------------------**

###### **Mitigation Approver**:

###### Reviews and approves the assignment of a mitigation control to a risk or SoD conflict.

###### 

###### **Mitigation Monitor**:

###### Ensures that the approved mitigation control is actually executed and remains effective over time.



\--------------------------------------------------------------

**Synchronization jobs:**

**Batch jobs to keep Access Control Repository aligned with backend systems by syncing users, roles and profiles.**

12.1) Authorization Sync (GRAC\_PFCG\_AUTHORIZATION\_SYNC):

Synchronizes authorization objects from backend systems (via SU24)  BRM

12.2) Repository Object Sync (GRAC\_REP\_OBJ\_SYNC):

Synchronizes Users, Roles, and Profiles into the Access Control Repository.

12.3) Action Usage Sync (GRAC\_ACTION\_USAGE\_SYNC):

Updates action usage data from plugin systems.



12.4) Role Usage Sync (GRAC\_ROLE\_USAGE\_SYNC):

Synchronizes role usage data for better risk evaluation.

