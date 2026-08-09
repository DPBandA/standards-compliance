# NB: Enter incomplete issues into GH when online

## JMTSv5 SC Module (August). Seek clarification on issues via phone call.

### 2.	We will send you an updated service contract form to be added to JMTS. 
        - [ ] Follow up.
### a.	Create signing authority for both inspector and customer service representative.
        - [ ] Get clarification on signing authority for what.
### b.	Create job numbers for both NCRA and the respective lab where sample will be sent.
        - [ ] Get clarification but inform that this already implemented.
### 3.	TAT bug in job costing
        - [ ] Ask to explain.
### 4.	Category validation there is a bug.
        - [ ] Ask to explain.
### 5.	Standard listing to be updated
        - [ ] Follow up.
### 6.	View of records are not being seen in this version. For example, complaints database, 
###     factory database, products database, etc. However, if a search is done stored information 
###     can be found.
        - [ ] Inform that a search has to be done to display records. This is done for 
        consistency with job search.
### 7.	Look Up is required for databases such as blocks, aggregates, hand sanitizer. 
###     A form must also be created so that the respective databases could be updated 
###     when test reports have been issued and when there are new clients. 
###     Certificates must be populated and created from the database.
        - [X] Associate certificates with factories/manufacturers using the OWNERID field. 
        - [X] Set the client dialog title to Applicant when an applicant is being created/edited.
        - [X] Create Certification dialog. 
        - [X] Add job number autocomplete as in survey dialog.
        - [ ] Add more columns to the certificates table.
        - [ ] Disable New certificate button if the manufacturer id is null.
        - [ ] Add Certificates tab to Manufacturer dialog. 
        - [ ] Get certificate form info from WR.
        - [ ] Point out the factories the database for this.
        - [ ] Build JMTS and test job creation and editing. 
### 8.	Product inspection – drop down list for standards is required. 
###     Not only when there is a breach it is required. Products are inspected 
###     against a standard.
        - [X] Implement autocomplete with list of standards in PI dialog.
        The autocomplete was already there.
### 9.	Label Print to be linked to the JMTS
        - [X] This was done. 
### 10.	Local Manufacturer and importer registration to be linked to JMTS
        - [ ] Get the forms that were implemented in WP website. Check email sent
        by WR on Jul 17.
### 11.	Domestic Sample Form does not require authorization
        - [ ] Remove authorization requirement from survey dialog. Check if this 
        relates to the "POE Sample Request" tab. In the mean time, check the button
        is grayed out. "Unrender" it for now. 
### 12.	Consignments – several consignments may be in a container. The consignments 
###     must be recorded and tallied.
        - [ ] Implement assigning multiple consignments to a container. Seek guidance. 
### 13.	Updated forms to be uploaded.
        - [ ] Follow up.
### 14.	Reason for detention is being repeated and entered manually. Update.
        - [ ] Ask how to address this. Seek clarification.
### 15.	Port of Entry Detention form was blank. Updated form in attachments.
        - [ ] Look for form and do the update. Ask for it if not found.
### 16.	I have not seen the reporting templates.
        - [ ] Clarify what is reporting templates.
### 17.     Signing/Authorizing
        - [ ] Change button label to "Unsign/Unauthorize" appropriately. 
## LabelPrint and Compliance Settings
- [X] Put settings under the respective menu/tools in JMTS.
- [ ] Add "Market Products" and "Manufacturers" to the Compliance menu bar.  
- [ ] Implement default search and button on the Compliance Settings tab.
- [ ] Add Compliance Settings to the Compliance Tools menu button. 
## WR located the reporting templates 
- [ ] The options for Type of Establishment in the Compliance Survey for Domestic Market 
must be consistent with the report template. Fields from the report template such 
as Bar & Grocery, Depot & Suprette, Hotel, Pharmacy are missing from the report template. 
Other terms in the template such as Grocery and Hardware must state Grocery Store and 
Hardware Store to be consistent with the software.
- [ ] Ask for clarification. 
- [ ] Update on #11 below, the sample request form and withdrawal forms were missing for 
market surveys and there is no authorization tab here.
- [ ] Ask for clarification. Review in SC first.
## Create SC doc on DPB&A website
- [ ] Update website.

## JMTS Release Notes
- [ ] This release contains updates to the Standards Compliance (SC), Food Factories (FI)
and Legal Metrology (LM) modules.
### Configuration
- [ ] Deactivate privileges: AddEnergyEfficiencyOption, AddLabelPrintOption
### Database
- [ ] Add OWNERID (BigInt) to companyregistration, ... tables.
