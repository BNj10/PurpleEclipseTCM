## **AUTH-0004:** Authentication testing - Signup with Google  

> **Summary:** Verify user can sign up through email.  <br>

**Preconditions:**  User must not be logged in. 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage   | Verify that the homepage is shown.   | 
 |  2 |   Click `Login` button.   | Verify that the login form overlay is shown.   | 
 |  3 |   Click `Continue with Google` button.   | Verify that the Google login popup appears.  |  
 |  4 |   Select a valid Google account.   | Verify popup closes and request is sent.   |  
 |  5 |   Wait for response.   | Verify that the set username overlay is shown.   |  
 |  6 |   Set the username to any username you want. | Verify that the text box value is equal to the username you want.   |  
 |  7 |   Click `Set Username` button.   | Verify that username is set accordingly.   |  

**Post-conditions:**  
 A new user account is created using their Google email.
