# STANDARD OPERATING PROCEDURE 

Accessing Scripts in Excel 
==========================

Click “Automate” 

Click “View Scripts” then “Recent Scripts” if you want to view an already created script, or “New Script” then “Create in Code Editor” if you want to create a new one. 

 

 

Adding New Script 
==================

Go to the following link to gain access to the Donor Care Scripts (https://github.com/rhoadarmernt/donor-care-scripts) 

Select the script that you want to add to Excel. Copy the entire block of code. 

Return to Excel. Delete any base code in the new script that you created. Paste the new code into the script. 

It will be most helpful to re-title the script name so that in future reference you can easily know which script is the one you need. You should go back to the GitHub link and copy/paste the title of that script into the Excel script title. 

Make sure to save the script. 

 

Editing Previous Script 
========================

If the script has been edited/updated, it will have been changed in the GitHub link (https://github.com/rhoadarmernt/donor-care-scripts). Always double check to see if the script has been updated recently. If it has, it is recommended that you update the script in Excel. 

After selecting ‘Recent Scripts’, select the ‘Edit’ icon next to the script that you would like to edit. 

Delete the current script and replace the script that you copy and paste from GitHub. Select ‘Save’ 

 

Using Scripts for TY Report Tasks 
==================================

TY Task 1: 
--------------

Within Excel, select the ‘Edit’ icon next to the “Identify Different Campaigns (TY Report)” script.  

Select the ‘Run’ button. It will output a list of phrases. Copy the list. 

Go back to all scripts and select the ‘Edit’ icon next to the “Find and Replace (TY Report)” script. 

If the current month range is not accurately displayed in Line 20, change the value within the quotations to the correct month range. 

Click at the end of the comment on line 23 and hit enter on your keyboard. This will take you to a new line. Paste the list that you copied from “Identify Different Campaigns” here. 

If any of the campaigns listed from your copy/paste are NOT general campaigns, delete that single line of code. For those, you will need to go through the sheet and manually assign a value. 

Click ‘Run’ to execute the script. Once it is complete, it is recommended that you delete the list that you had just copied from the code in “Find and Replace (TY Report)”. 

Lastly, go back to all scripts, and select the ‘Run’ icon next to the “TY Task 1 (TY Report)” script. Your spreadsheet should now be ready, however, quickly double-check to make sure everything looks right. 

 

TY Task 2: 
--------------------

Within Excel, select the ‘Run’ icon next to the “TY Task 2 (TY Report)” script. 

Any highlights on the spreadsheet need your attention, as they are likely accounts with international addresses. 

If there are no highlights, your spreadsheet should be ready! 

 

Using Script for Soft Credits 
=================================

Within Excel, select the ‘Edit’ icon next to the “Data Clean-Up (Soft Credits)” script. 

In the code, underneath “Edit these headers as needed”, you must change the values between the quotations for EMAIL_HEADER, NAME_HEADER, & AMOUNT_HEADER to match the column names in the current spreadsheet (EMAIL_HEADER is the Email column, NAME_HEADER is either Full Name or First Name column, AMOUNT_HEADER is the column with the monetary totals that you must input). 

Click ‘Run’ to execute the script. If you want to still see the transactions pre-merge, however, you can simply show hidden rows in the spreadsheet. 

 

 
