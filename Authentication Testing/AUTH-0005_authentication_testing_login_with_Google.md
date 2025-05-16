## **AUTH-0005:** Authentication testing - Login with Google

> **Summary:** Verify user can login account through email.  <br>

**Preconditions:**
User must not be logged in and must have a verified email 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage   | Verify that the homepage is shown.   | 
 |  2 |   Click `Login` button.   | Verify that the login form overlay is shown.   | 
 |  3 |   Click `Continue with Google` button   | Verify that the Google login popup appears.  |  
 |  3 |   Select a valid and registered Google account   | Verify popup closes and request is sent.   |  
 |  3 |   Wait for response   | Verify user is logged in and redirected appropriately.   |   


**Post-conditions:**  
The user is logged into their account using Google account.	 
