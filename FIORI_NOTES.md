### **FIORI---**



**/UI2//FLP** - Fiori Launchpad

**/UI2/FLPD\_CUST** → Launchpad Designer (Client-specific)

**/UI2/FLPCM\_CUST -** Launchpad Content Manager - Single window for catalog to view copy and edit

**/UI2/FLC** → Launchpad Content Manager



**/UI2/RSP\_LIST** - transaction to analyze space/page assignments to roles.



**/UI2/SEMOBJ** - Custom semantic object creation

**/UI2/SEMOBJ\_SAP** - Display SAP Sematic Object



**SICF** - to activate required internet framework services

**/IWFND/MAINT\_SERVICE** - Activate and maintain OData services.

**/IWFND/ERROR\_LOG** → Gateway error log

\--------------------------------------------------------------------------------------------------------

**Business Catalog:**

A Business Catalog is a collection of related Fiori apps grouped by function. It can contains tiles and apps.



**Business Roles:**

A Business Role represents a job function and defines what a user can access in the system.

It is a combination of Business Catalogs + restrictions (like company code, plant).



**Tile:** Tile is a container that represents an app on the Fiori launchpad page. it is used to display and launch app on the Fiori launchpad.



**Spaces**: A logical container that holds one or more pages. It group apps by work are like finance, HR - Like folder or Main menu category.



**Pages**: A section within a space that contains apps as tiles. Users navigate between pages like tabs. - Tab or sub-page.



**Groups:** To groups related apps together for quick access, that appears on the launchpad, can be user customizable.



**Semantic Object:** Semantic object is a logic name that represents a business entity e.g. SalesOrder, PostPayments, Customer.

Used with action to build navigation intent e.g. SalesOrder-Display. Enables intent-based navigation.

Navigation between tiles and applications.



3 types of Fiori apps:



1. **Transactional apps:** these apps let you perform transactional apps such as creating purchase orders.
2. Analytical
3. Factsheet



**Front End Role:** Front role contains catalogs, group/spaces and UI related authorizations that drives what tile user can see in the launchpad.



**Back End Role:** Back-end role contain OData Services and Business authorizations (e.g. Appln and object authorizations) required to execute app logic and display Data.



**User Clicks on Tiles:** The launchpad reads the catalogs and groups/spaces via roles to the user and shows only those tiles that are allowed by user roles.

If the role includes the corresponding OData Services, then starting the tile triggers the service with necessary start and business authorizations.

\----------------------------------------------------------------------------------------------------------------------



How to create catalogs, spaces and pages in Fiori?

Technical Catalog - SAP\_TC\_FIN\_FO\_COMMON to create reference.



Catalog - ZCAT\_POST\_PAYMENTS



Space - ZSP\_ACC\_REC



Pages - ZPG\_ACC\_PAYMENTS



Execute /UI2/FLPD\_CUST tcode, you will see catalog collection screen,

on bottom click on + icon to create catalog, provide tittle and ID (catalog name) and save. catalog created now create reference.



To create search for reference catalog and then search for relevant tittle. once found, drag it to create reference.

Now search for your Z-Catalog and click on it.



Now create target mapping with semantic object.







































\------------------------------------------------------------------------------------------

**S4/HANA Public Cloud---**

Manage Journal Entries

→ App ID: F0717A





Manage Purchase Orders (Find/Manage POs)

→ App ID: F0842





Manage Sales Orders – Version 2 (Find/Admin Sales Orders)

→ App ID: F3893





Manage Fixed Assets (Fixed asset list type use case)

→ App ID: F1684





Display Journal Entries – Ledger View

→ App ID: FB03L

