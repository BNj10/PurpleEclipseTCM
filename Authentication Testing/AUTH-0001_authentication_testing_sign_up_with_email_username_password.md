## **AUTH-0001:** Authentication testing - Sign Up with Email/Username/Password  

> **Summary:** Verify user can sign up with email, username, and password.  <br>

**Preconditions:**
Verify user can sign up with username and password. 

Scenario 1 

 | \# | Step                                                                                     | Expected Behavior | 
 |----|------------------------------------------------------------------------------------------|-------------------| 
 |  1 | Visit the homepage.                                                                      | Verify that the homepage is shown.   | 
 |  2 | Click ‘Register’ button.                                                                  | Verify that the registration form overlay is shown.   | 
 |  3 | Set the value of the text box with the placeholder ‘Enter Username’ as “Tester Team”.     |Verify that the text field value of the text box is “Tester Team”.| 
 |  4 | Set the value of the text box with the placeholder ‘Enter Email’ with an active email.   |Verify that the text field value reflects the inputted text.| 
 |  5 | Set the value of the text box with the placeholder ‘Enter Password’ with an intented password.|Verify that the text field value reflects the inputted text.| 
 |  6 | Click ‘Create Account’                                                                   |Verify that the confirmation overlay is shown.| 
 |  7 | Wait for email verification.                                                             |Verify that the email verification will be sent to your active email.|  

**Post-conditions:**  
The account will be registered in the system after email confirmation.
