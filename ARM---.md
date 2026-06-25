## **ARM---**

###### 

###### SPRO  GRC  Access Control  User Provisioning  Maintain/define number range  define request and provisioning settings



###### SPRO  GRC  Access Control  User Provisioning  User Personalization  Mandatory/editable/visible fields for user



\------------------------------------------------------------------------------



## **MSMP ---**



###### **11 process ids by default** SAP\_GRAC\_, ACCESS\_REQUEST, FUNC\_APPR, RISK\_APPR, ROLE\_APPR, CONTROL\_AGN, CONTROL\_MAINT





###### **Every MSMP process ID contains one Rule ID. (Initiator rule)**

###### 

###### We have 4 rule types:

1. ###### ABAP class
2. ###### Function module based rule
3. ###### BRF plus rule
4. ###### BRF plus flat rule



###### **We have 4 rule kinds**

1. ###### Agent Rule
2. ###### Initiator Rule
3. ###### Routing rule
4. ###### Notification variables rule



###### The purpose of agent is to Approve/Reject or notification.



###### We can create templates for alerts using:

###### 

###### SE61  select General texts  Enter document object from MSMP screen  Execute



###### **T-code to open MSMP screen: GRFNMW\_CONFIGURE\_WD**

###### 1\)	Process Global Settings

###### 2\)	Maintain Rules

###### 3\)	Maintain Agents

###### 4\)	Variable and templates

###### 5\)	Maintain Paths

###### 6\)	Maintain Route mapping

###### 7\)	Generate versions



###### Suppose user raised an access request, 

###### Step 1) Rule ID 

######  Step 2) We can see the rule results

###### 	Step 6) depends on the rule ID \& rule results, system will choose the path.

###### 	Step 5) Request will go the specified path and the respective stages.

###### Stages contains agents, which are defined in the step 4. (maintain Agents)





