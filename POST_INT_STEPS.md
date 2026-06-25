#### **--------------------------------------------------**

#### **Steps : Overview / Post Installation Steps**



###### client copy \& config - BD54 \& SCC4 \& SCCL SALE - (BASIS)

###### 

###### 1\. NWBC - NetWeaver web app server login - business client for HTML

###### 

###### 2\. SPRO >> General settings >> Activate application in client >> GRC AC

###### 

###### 3\. SCIF - to activate required internet framework services

###### 

###### **4. SCPR20 - Activate BC Sets >> Business Configuration Sets >> \*RULSET\* , \*REQUEST\*, \*ROLE\_MANAGEMENT\*, \*SPM\***

###### 

###### 5\. /n/iwfnd/maint\_service - Activate and Maintain Services

###### 

###### 5\. Creating initial user in SU01 and assign below role

###### 

###### SAP\_GRC\_FN\_BASE - access GRC apps such as AC

###### SAP\_GRC\_FN\_ALL - person doing customization of the product

###### SAP\_GRC\_FN\_BUSINESS\_USER - assign to business user

###### SAP\_GRC\_NWBC - NWBC as frontend

###### 

###### \----------------------------------------------------------------------------

###### 6\. Perform automatic workflow customizing : (BASIS) --> Activate common workflow

###### SPRO  SAP IMG Ref  GRC  General Settings  Workflow  Perform automatic workflow customizing >> Perform all steps \& sub steps

###### GRC >> GRC-AC

###### 

###### 7\. Perform task specific customizing : (BASIS)

###### SPRO  IMG  GRC  General settings  Workflow  Perform task specific customizing

###### 

###### 8\. SWE2 - Event type linkage : GRAC \& GRC

###### 

###### 9\. SM59 - RFC creation (BASIS) >> SPRO define connector settings

###### 

###### **10. Integration Scenario - 1) Auth 2) PROV 3)ROLEMG 4) SUPMG**



1. ###### **Access Control:**
2. ###### **Authorization  Auth  ARA**
3. ###### **provisioning  PROV  ARM**
4. ###### **Role management  ROLEMG  BRM**
5. ###### **Super user privilege management  SUPMG  EAM**

Automatic Monitoring  Process Control



###### 11\. SPRO  IMG GRC  AC  Maintain Configuration settings

###### &#x20;40\* Parameter series is for EAM.

###### &#x20;20\* Parameter series is for ARM.

###### 

###### &#x20;SPRO  IMG  GRC  AC  Define environment for the connector:

