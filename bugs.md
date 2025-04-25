# Bugs

Platform: Web

Browser:  Mozilla Firefox 137.0.2 (64-bit)

URL: https://linqapp.com/welcome


Bug 001- Phone number field accepts more than 10 digits without validation error

Steps to Reproduce:

1.Navigate to  https://linqapp.com/welcome

2.Click on Edit Contact

3.Scroll down to bottom of the page

4.click add contact information

5.click on phone number field

6.Enter a value with more than 10 digits (e.g., 123456789012)

7.click on save

Expected result: The system should reject phone numbers exceeding 10 digits and display a validation error message (e.g., "Invalid phone number length").

Actual result: The system saves the phone number without any validation error, allowing invalid input. 



Bug 002 - "Manage Page" options remain unclickable after dismissing the duplicate page dialog

Steps to Reproduce:

1.Navigate to https://linqapp.com/welcome

2.click on the three dot ellipsis at top of the page

3.Select duplicate page

4.When the dialog appears, click "Dismiss"

Expected Results: After dismissing the "Duplicate Page" dialog, the "Manage Page" options are disabled or unclickabl

Actual Results: The "Manage Page" options remain clickable, allowing unintended actions despite the modal being dismissed.


Bug 003 - Deleted contact field remains visible until page refresh

Steps to Reproduce:

1. Navigate to https://linqapp.com/welcome
   
2.Click on Edit Contact

3.Select any field (e.g., phone number )

4.Click on Edit/Delete

5. Click Delete
   
6. Click Delete on the dialogue box

7.Form field removed successfully 

Expected Result: The selected contact field should be immediately removed from the UI after deletion, without requiring a page refresh.

Actual Result: The field remains visible in the form until the page is manually refreshed
