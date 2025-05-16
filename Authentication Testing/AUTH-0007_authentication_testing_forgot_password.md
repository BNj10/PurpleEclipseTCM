## **AUTH-0007:** Authentication testing - Forgot Password  

> **Summary:** Verify user can recover lost account.  <br>

**Preconditions:** User must have an account with a registered email address.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage                                     | Verify that the homepage is shown.             | 
 |  2 |   Click the `Login` button                               | Verify that the login form overlay is shown.   | 
 |  3 |   Click the `Forgot password` text link                  | Verify that the forgot password overlay is shown.  | 
 |  4 |   Provide the registered email address to the text box.  | Verify that the value of the text box reflects the actual inputted value.   |  
 |  5 |   Click `Send Reset Email` button.                       | Verify that the success message is shown.   |   
 |  6 |   Wait for response.                                     | Verify that an email request is received.| 
 |  7 |   Click `Reset Password` text link on email              | Verify that it will redirect you to the platform showing a update password overlay. | 
 |  8 |   Fill up the textboxes with new and secure password.    | Verify that the textbox’s value is the same as the secure password. |
 |  9 |   Click the `Update Password` button.                    | Verify that the user will be redirected to the homepage.|  

**Post-conditions:** 
The account password is updated successfully.	