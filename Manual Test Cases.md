Manual Test Cases

TC01   

Description : Ensure that new or first-time visitors who are not logged in are redirected to the login or signup page before they can view any profile information.

Steps:

1.Open a web browser in incognito/private mode (to simulate a first-time visitor).
2.Navigate to https://linqapp.com/welcome.

Expected Result

The visitor is shown the login or signup screen. The profile page should not load, and no user data (like photo, name, or contact info) should be visible without authentication.


TC02

Description: Ensure that the profile page opens correctly for a visitor.

Steps

1.Open a browser
2.Go to https://linqapp.com/welcome.	

Expected Results:

Profile page loads without errors, displaying user photo, name, and available contact options.


TC03	

Description: Ensure that the system prevents saving a contact when the phone number exceeds the standard 10-digit limit.
	
Steps

1.Navigate to the Linq welcome profile 
2.Click on “+” on the top(Create New Contact) 
3.Enter values for all required fields:
4.Name: John test, Phone Number: 123456789012345 (15 digits), Email, Company, etc.
5. Fill with valid sample values.
6.Click on save changes.

Expected Results :

Invalid phone number. Please enter a valid 10-digit number.”



TC04	

Description: Ensure that selecting a contact and exporting it to CSV results in a successful and correctly formatted CSV file download.
	
Steps

1.Navigate to the Contacts 
2.Click on the “Select” 
3.Click on the “Choose Action”  
4.Select the option “Export to CSV”.

Expected Results:

 A .csv file should be successfully downloaded to the default download location of the browser/device.



TC05	

Description : Validate saving contacts with international characters (e.g., Chinese, Arabic, accented characters).	

Steps:

1.Use a profile with non-English characters in name or company 
2.Save the contact and open the file in a contact app.	

Expected Results: 

All characters should render correctly in the saved contact without encoding issues.


