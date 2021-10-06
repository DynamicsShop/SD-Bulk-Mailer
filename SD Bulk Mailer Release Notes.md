## SD Bulk Mailer Releases

### 9.1.10

#### Enhancements

- BCv18 App - The file structure of the Zip file generated of a Job with Delivery Method of Print was changed from to Job Name folder and Files folder. 

- BCv18 App - In the History Print Page the Resend Action for Drafts with Delivery Type of Print was disabled.

- BCv18 App - The SD Bulk Mailer XML file permissions of Admin, User and View were converted to permission set objects. Permission set extensions were created for Exten. Mgt. - Admin" to include SD Bulk Mailer Admin permissions, "D365 BUS FULL ACCESS" to include SD Bulk Mailer User permissions and "D365 BASIC" to include SD Bulk Mailer View permissions.

- BCv18 App - The latest ISV Licence Controller changes were added to SD Bulk Mailer.

#### Bug Fixes

- BCv18 App - Fixed an issue where SD Bulk Mailer Jobs of Delivery Type Print were only downloading the last pdf report printed when drafts were issued. 

- BCv18 App - Fixed an issue where specific text was being stamped on computer name on registration of licence in the ISV Licence Controller.

### 9.1.9

#### Enhancements

- BCv18 App - The Import Assisted Setup File action was removed from the SD Bulk Mailer Setup.

- BCv18 App - The ISV Licence Controller message that is displayed when a user tries to activate a second licence trial for the product on the same site was updated.

- BCv18 App - An unused blank page was included in the product. This page was removed from the product build.

#### Bug Fixes

- BCv18 App - When resending drafts from history, html text was inserted into the email body. 

### 9.1.8

#### Enhancements

- BCv17 Public App - The code was updated to use the latest standard smtp emailing functionality in D365 which has been moved to a separate App. 

### 9.1.6

#### Enhancements

- BCv14 Private App - The Licence Expiry Date when prompting with 5 days to go until expiry was stopping Drafts from generating - the logic around this was changed to prompt that the licence was expiring soon but not to stop the drafts from generating until the licence had actually expired.

- BCv14 Private App - The ISV Licence Controller was added to the product.

### 9.1.5

#### Enhancements

- BCv17 App - Throttling was added to the History Page.

- BCv17 App - The recipients are now revalidated when choosing to "Recreate Draft from History Entry" on the Draft History page. 

- BCv17 App - Visual changes were made to the Setup Card. Actions were renamed. The Key Index ID FastTab was renamed and the fields in the FastTab were changed to drop down lists.

- BCv17 App - Permissions Sets were created for the SD Bulk Mailer product.

- BCv17 App - Usage Category for Tell Me Search was updated to show the SD Bulk Mailer History.

- BCv17 App - Changes were made to the About page. A new link was added to the Product Page.

- BCv17 App - The configuration setup for SD Bulk Mailer was added to the product. This is accessible from the Assisted Setup page. When chosen, an xml file with setup data is imported from GitHub into SD Bulk Mailer.

- BCV17 App - The latest licensing control functionality was added to SD Bulk Mailer.

- BCv17 App - The product was readied for AppSource submission.

- BCv17 App - A minor typo was fixed on the Assisted Setup prompt.

- BCv17 App - Updated the Customer Statement Job to allow the option to print the Statement with the Aging Band.

- BCv17 App - BCv17 App - The URL for the Learn More in SD Bulk Mailer Pages was changed from pointing to the Fact Sheet page to point to the Product page.

- BCv17 App - A change was made to the Product Page URL in the About page.

- BCv17 App - The URL for the Learn More in SD Bulk Mailer Pages was changed.

- BCv17 App - When generating Drafts from the Job Card, the user receives a prompt to say that Drafts have been generated successfully. 

- BCv17 App - The application area was set on the Role Centre activity pages.

- BCv17 App - Functionality was rewritten to allow a user to change the Template on a generated Draft.

- BCv17 App - The Default SMTP Settings Action were removed from the SD Bulk Mailer Setup.

- BCv17 App - Added a prompt so the user knows that the drafts have generated successfully.

- BCv17 App - A minor typo fix was made to the Assisted Setup message prompt.

- BCv17 App - Made a change to SD Bulk Mailer Setup where the SMTP mail setup details are now flowfields off the standard SMTP Mail Setup table.

- BCV17 App - The Object Name was added to the Report ID lookup in the Job Card page. 

- BCv17 App - The Job Card page is refreshed after assigning and un-assigning Security User Groups.

- BCV17 App - Changes were made to the descriptions of the SD Bulk Mailer permission sets.

- BCv17 App - Changes were made to the Licence Activation page.

- BCv17 App - Visual changes were made to the Licence Activation page,

- BCv17 App - A change was made to show the SD Bulk Mailer pages in the Tell ME when the user types in SD or bulk.

- BCv17 App - A fix was made to a small typo on the Activate your product page.

- BCv17 App - A codeunit with an Object ID but no Object Name was removed from the SD Bulk Mailer permission sets.

- BCv17 App - Changes were made to the URLs on the About page.

- BCv17 App - A change was made on the SD Bulk Mailer Setup Card to change the FastTab name from Key Index ID to Default Keys.

- BCv17 App - A change was made to show the Draft and History pages when searched for in the Tell Me.

- BCv17 App - A change was made to allow users search for the SD Bulk Mailer Role Centre Activities in the Tell Me.

- BCv17 App - The Display Name of the SD Bulk Mailer Role was updated to reflect the naming conventions that we use for our other products.

#### Bug Fixes

- BCV17 App - Fixed an issue where a message was displayed that drafts were generated successfully if user selects cancel on prompt to generate drafts.

- BCv17 App - Fixed an issue with the Customer Payment Receipt Job where the search from Entry No. was not allowing the user to enter a value.

- BCv17 App - From the Email History when user chooses to Recreate a Draft from History the Template on the record was blank and the Delivery Method of Web Service was not removed from the option list.

- BCv17 App - Fixed an issue where Emails were not being sent when resent from History.

- BCv17 App - Fixed an issue where resending from History didn't increment the Deliveries count.

- BCv17 App - Fixed an issue where an error was raised that the Start Date must have a value when running the Customer Statement Job with the standard Statement Report.

- BCv17 App - Fixed an issue where when generating drafts from the Job list, users can generate drafts by selecting the Job Code without pressing the OK button.

- BCv17 App - Fixed an issue where if there was more than one To Recipient on the Draft, the Draft was issued only to the first To Recipient on the list.

- BCv17 App - Fixed an issue where more than one Recipient as a Type of To could not be added on the Job Card.

- BCv17 App - Fixed an issue where the lookups on the Recipients list on the Job Card weren't working.

- BCv17 App - A date format error, related to the licensing functionality, that was raised when the SD Bulk Mailer Setup card was opened was fixed. 

- BCv17 App - A date format information message, related to the licensing functionality, that was raised when the SD Bulk Mailer Setup card was opened was fixed. 

- BCv17 App - A date format error, related to the licensing functionality, that was raised when generating Drafts was fixed. 

- BCv17 App - Fixed an issue where adding a Specific Recipient to a Job incorrectly forced the Address Field No. field on the record to be entered.

### 9.1.4

#### Enhancements

- BCv16 Public App - Removed assisted setup pages/objects.

- BCv16 Public App - Added Email Throttling add User Interface Message in the Draft Issue.

- BCv14 Private App - Added Email Throttling add User Interface Message in the Draft Issue.

### 9.1.3

#### Enhancements

- BCv13 - Created a CAL to AL data uplift routine.

- BCv13 - Made a change to allow selection of To Email Address in SD Bulk Mailer SMTP setup when testing SMTP setup.

- BCv13 - A change was made to make Statement date range fields mandatory on the Bulk Mailer Job card for a Type of Statement.

- BCv13 - The visual property of mandatory fields on Job Card were reviewed and mandatory fields were marked as such.

- BCv13 - Added a tooltip to the Type "For Office 365 users use Exchange Web Services as using SMTP may cause errors due to a limitation in Office 365 to reject email streams of over 30 mails per minute".

- BCv13 - Added User Group Security filters to limit what Jobs, Drafts and History a user can access based on their assigned User Group.

- BCv13 - Changes were made to re-create a Draft Document from History.

#### Bug Fixes

- BCv13 - Updated a caption and tool tip on the SD-BM Job table.

### 9.1.2

#### Enhancements

- BCv13 C/AL - Added an Enforce Email Throttling flag to SD Bulk Mailer Setup.

### 9.1.1

#### Enhancements

- BCv16 Public App - The length of description and name fields was increased from 50 to 100 characters as per standard D365BC.

- BCv14 Private App - The length of description and name fields was increased from 50 to 100 characters as per standard D365BC.

### 9.1.0

#### Enhancements

- A change was made to make Statement date range fields mandatory on the Bulk Mailer Job card for a Type of Statement.

- The visual property of mandatory fields on Job Card were reviewed and mandatory fields were marked as such.

- Made a change to allow selection of To Email Address in SD Bulk Mailer SMTP setup when testing SMTP setup.

- Added the Usage Report Category to Bulk Mailer Pages and updated the Caption in BC365 code base.

- Changes were made to re-create a Draft Document from History.

- Added User Group Security filters to limit what Jobs, Drafts and History a user can access based on their assigned User Group.

- Added a tooltip to the Type "For Office 365 users use Exchange Web Services as using SMTP may cause errors due to a limitation in Office 365 to reject email streams of over 30 mails per minute".

- BCv14 Private App - Added table changes made in C/AL code base to AL code base.

- BCv14 Private App - The look up on the Job Code field in the SD-BM Job Queue was enabled.

- BCv14 Private App - The Role Center Page cues are now updated when Drafts are created.

- BCv14 Private App - Made a change to the Job Card to mark Recipients as a mandatory field.

- BCv14 Private App - A change was made to make Statement date range fields mandatory on the Bulk Mailer Job card for a Type of Statement.

- BCv14 Private App - The Job Queues Action was added to the Setup Page.

- BCv14 Private App - The Setup and Job Queue Actions were added to the Draft Activities Panel.

- BCv14 Private App - Added a tooltip to the Type "For Office 365 users use Exchange Web Services as using SMTP may cause errors due to a limitation in Office 365 to reject email streams of over 30 mails per minute".

- BCv14 Private App - Added User Group Security filters to limit what Jobs, Drafts and History a user can access based on their assigned User Group.

- BCv14 Private App - Changes were made to re-create a Draft Document from History.

- BCv14 Private App - Reviewed icon images on cues and actions.

- BCv14 Private App - Visual changes were made to the Job Card.

- BCv14 Private App - Removed the extra password check on SD Bulk Mailer Setup from the BC365 AL/Extension code base.

- BCv14 Private App - Removed the SD Charts from the AL Extensions code release.

- BCv14 Private App - Created and surfaced a KPI FactBox on the Role Centre to indicate the amount of mails sent by Job Type - a count of this month, last month, last 6 months, last 12 months.

- BCv14 Private App - Updated the validation on email addresses in the Job Card page.

- BCv14 Private App - Added functionality to allow users to view the draft attachments from the FactBox in the Draft List page.

- BCv14 Private App - The details shown on the About Page were updated.

- BCv14 Private App - Visual changes were made to the Ribbon in the Setup Card.

- BCv14 Private App - Visual changes were made to the Job Card.

- BCv14 Private App - Visual changes were made to the Count of Mails sent by Job Type KPI FactBox.

- BCv14 Private App - Visual changes were made to the Job Card for Job Type of Sales Invoice.

- BCv14 Public App - The Role Center Page cues are now updated when Drafts are created.

- BCv14 Public App - AppSource Certification code cleanup.

- BCv14 Public App - Removed the Attention Activity Panel from the the standard Sales Order Processer Role Centre.

- BCv14 Public App - Added a native PDF viewer to the product.

- BCv14 Public App - Changes were made to the SD Bulk Mailer Setup Card and functionality.

- BCv14 Public App - Surfaced the SD Bulk Mailer Role Centre Activity Panels in the standard Sales Order Processer Role Centre.

- BCv14 Public App - A fix was made to the Job Code lookup field in the SD-BM Job Queue.

- BCv14 Public App - Converted the Bulk Mailer code base to extensions for deployment on Public Cloud.

- BCv14 Public App - Added Licence Key Validation.

#### Bug Fixes

- Updated a caption and tool tip on the SD-BM Job table.

- BCv14 Public App - An issue was fixed in the History List when choosing to Resend an incorrect recipient was being issued with the draft.

- BCv14 Public App - The Job Type KPI was not updating correctly.

- BCv14 Public App - Fixed an issue where the draft was sent to an incorrect recipient.

- BCv14 Public App - Fixed an issue in the Draft Card where a recipient was removed from the list but the mail was then sent to a different recipient.

- BCv14 Private App - Fixed an issue where an error raised when generating Purchase Order drafts.

- BCv14 Public App - Fixed an error raised when generating Drafts.

- BCv14 Private App - Added the Service Order and Customer Payment Receipt Job Types to Job Type KPI.

- BCv14 Private App - Made a visual change to the Job Type KPI to line up the count of issued Drafts to the Job Type description.

- BCv14 Private App (Windows Client) - Fixed an issue where the View Email Action was not working on the Draft List page in a Windows Client.

- BCv14 Private App - A change was made to attach the Actual Document first, and then the Attached Document, to the Draft Card/Email.

- BCv14 Private App - The visual property of mandatory fields on Job Card were reviewed and mandatory fields were marked as such.

- BCv14 Private App - Fixed an issue where the option to Update File and Export File were not enabled in the Additional Attachments FastTab on the Job Card.

### 9.0.5

#### Enhancements

- Ported code to a BC365 CU03 on premise environment.

- Merged changes in SD Bulk Mailer - Nav.13.0.W1 - v9.0.5 to the Bulk Mailer BC365 Extension code base.

- Made changes to the SD Bulk Mailer Assisted Setup to allow for re-run of the Assisted Setup.

- The Assisted Setup pages were re-ordered.

- Removed the extra password check on SD Bulk Mailer Setup.

- Removed the extra password check on SD Bulk Mailer Setup on the BC365 on prem code base.

- Made changes to the new SD Bulk Mailer Assisted Setup.

- Ported code base to BC365 on prem environment.

- Re-wrote functionality in Codeunit SD-BM Utility for the BC365 on prem release.

- Made changes to the SD Bulk Mailer Assisted Setup.

- Created SD Bulk Mailer Assisted Setup functionality.

#### Bug Fixes

- Fixed an issue where users were getting a web service already exists error when creating a new job.

### 9.0.4

#### Enhancements

- Removed the Filters Start and End CLE from the Drafts List Page.

- Minor UI changes were made to the Draft Card.

- Moved the Skip Issue of Job Queue Drafts checkbox on the Job Card.

- Minor user interface changes made to the Job List and Job Card.

### 9.0.3

#### Enhancements

- Minor user interface changes were made to the SD Bulk Mailer Jobs List Page and Job Card.

- Minor user interface changes were made to the SD Bulk Mailer History page.

- Minor user interface changes were made to the Drafts List Page.

- Minor user interfacechanges were made to the SD Bulk Mailer Setup Card.

- Made a change to allow users to choose to process drafts automatically and then send the drafts manually as a two step process when using Job Queues.

- Made a change to allow users to mark a draft as Skipped and Archived, so the draft won't appear in the draft list when a job is run for a second time.

#### Bug Fixes

- Fixed an issue where drafts were created for all jobs when the user selects "No" to the "Create Drafts?" prompt in the Job List Page.

### 9.0.2

#### Enhancements

- Granted express permission to standard NAV table 1261 in the SD-BM Setup table.

### 9.0.1

#### Enhancements

- Updated the HTMLEditor control to the latest version in the Simply Dynamics Control Suite.

- Deployed the new Add-In Installer.

- Refactored the Add-Ins to use the Simply Dynamics namespace.

#### Bug Fixes

- Fixed an issue where when adding new placeholders to the email subject in the Template Card the placeholder was not displaying correctly in the subject field on the card nor in the email.

- Fixed an issue where the  Search from Entry No. was not being stamped on the Customer Payment Receipt Job when the Bulk Mailer Drafts were delivered.

### 9.0.0

#### Enhancements

- Created a new function to allow users to upload and attach a file to multiple Drafts.

- Split the Activities Cue in the Role Centre out into individual pages - one per activity cue.

- Updated and reviewed Readme.md file.

- Updated the About Page.

- Refactored Cebuella to SimplyD for dotNet AddIn.

- Updated the Chart component in SD Bulk Mailer.

- Added an Action in the Draft Card to remove Attachments from the Draft.

- Refactored the dotnet Add-in to simplify the API.

- Created a NAV 2016 release of SD Bulk Mailer 9.0.0.

- Renumbered the SD Bulk Mailer objects.

- Created functionality to allow users to copy a Job of type Email to a Job of Type Web Service.

- Created data upgrade ports to upgrade from version 8 to version 9 of SD Bulk Mailer.

- Added functionality to SD Bulk Mailer Templates to provide a Field Place holder lookup for the Template Subject Line.

- Reviewed and cleaned up all SD Bulk Mailer Pages.

- Created an SD Bulk Mailer Visualizer to allow users to view the SD Bulk Mailer charts outside of the SD Bulk Mailer Role Centre.

- Improvements made to Preview Email functionality.

- Fixed an issue with Vendor Remittances, whereby deleting generated Drafts resulted in always including the previous ledger entries in the Vendor Remittances.

- Added Factboxes to History List Page.

- Restructured the History Card and List.

- Restructured the Draft Card and List.

- Restructured the Setup Card.

- Implemented our ISV modular window handler for the progress bars in Bulk Mailer.

- Made changes to the Web Service Logic.

- Removed storage options from the Bulk Mailer Setup.

- Implemented our standard Simply Dynamics ISV charts on the SD Bulk Mailer Role Centre.

- Implemented our new Simply Dynamics ISV data import/export module.

- Implemented our Simply Dynamics ISV HTML Editor in the Template Card.

- Enhanced security.

- Created functionality to allow a double click on the recipient FactBox, in the Drafts List, to allow Users to easily open and edit the Message recipients.

- Created a new Job to enable the Customer - Payment Receipt to be generated and sent through Bulk Mailer.

- Created Events for Draft Creation and Draft Delivery.

- Added functionality to allow Users to Deliver Selected Drafts from History from the Draft List Page.

- Made the History re-send functionality more prominent and intuitive to use.

- Added the facility to allow Users to attach multiple documents to generated Drafts.

- Added the standard NAV Test Email Setup to the SD Bulk Mailer Setup Page.

- Extended Office 365 to use Exchange Web Services.

- Added functionality to mimic standard NAV SMTP Setup in the SD Bulk Mailer Setup.

- Added the ability to specify BCC Recipients.

#### Bug Fixes

- Fixed an issue in the SD-BM Job List page where drafts were created for all Jobs when the user selected No to the "Create Drafts" Action prompt.

- Fixes and changes made to the upgrade routine.

- Fixed an issue when uploading attachments to Print Drafts.

- Fixed an issue where processing a Draft from the Drafts List Page with a Delivery Method of Print raised a Try Function Error.

- Fixed an issue where the Subject Body entered on the Template Card is not saved if you create a new Template Record by accessing the Card from a drop down list.

- Fixed a type conversion error in an SD Bulk Mailer Codeunit.

- Updated the functionality in the Refresh Action on the Template Card - to retain the Body if Refresh is chosen before the record is saved.

- Fixed an issue in the new dll where an error was raised when sending a Draft.

- Fixed a NAV 2017 Compatibility issue in an SD Bulk Mailer Codeunit.

### 8.2.1

#### Bug Fixes

- Allow users to mass delete Pending Messages (currently you must delete one by one). 

- When re-sending a document from history the document is attached to the email without the file extension or with a .dat extension.

### 8.2.0

#### Enhancements

- Refactored Report code to use RecordRef instead of Record. 

- Added generic Customer and Vendor Job Types that would run from the Customer and Vendor Tables. 

- Developed an option to add Recipients based on a "Mailing Group".

#### Bug Fixes

- Error when using Document or Document Contact Source Recipients. 

- Null reference error when viewing a Document with an unknown file extension.

### 8.1.3

#### Bug Fixes

- Ensure Exchange compatible is 2010 and above.

### 8.1.2

#### Enhancements

- Re-structure and update the Readme.txt file.

#### Bug Fixes

- Job and Template on the Role Centre have the wrong RunPageMode. 

- SALES-ORDER Job Description spelling mistake.

### 8.1.1

#### Enhancements

- Provided Version Info and URL in the About dialog box. 

- Moved strings into Text Constants. 

- Improvements to Role Centre - Cues and Chart.

### 8.1.0

#### Enhancements

- Changes made to the SD Bulk Mailer MSI. 

- Renumbered the objects.

### 8.0.0

#### Enhancements

- Provided a Web Service API for running a Job with filters. 

- Added a History Import/Export XMLPort to allow import/export of History. 

- Created an EMail Wrapper for SMTP/EWS. 

- Created a Version 7 SD Bulk Mailer Configuration and History import XMLPort. 

- Provided an example field in the Statement Job Card containing the result of the Date Range formulas for the Statement.

- Added a ReadMe.txt file containing installation notes.

- Refactored the SD-Bulk Mailer Engine Codeunit. 

- Added an option to choose the Entity Code used in a function to apply the document details. 

- Blank Start and End Date Formula (signifying the current date) are now allowed in Jobs, as this would be a valid entry. 

- Allow for unlimited recipients for a Job. 

- Allow for multiple, comma separated, Email addresses in the one field. 

- Integration of Bulk Mailer Jobs with Job Queues. 

- Use a custom selected field on the Entity table for recipient Email address. 

- Use a BLOB field for the Message Template body.

### 7.1.0

#### Enhancements

- Created an XMLPort to export and import History.

### 7.0.1

#### Enhancements

- Initial Build.

