## **NOTIF-0001:** Notification testing - Receive  

> **Summary:** Verify that notification is received and displayed successfully when new updates occurs.  <br>

**Preconditions:** The user should be logged in.

Scenario 1 


 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.                                            | Verify that the homepage is shown.  | 
 |  2 |   Create a thread and have the other one comment on the thread.  | Verify that there will be notification received and is highlighted accordingly.  | 
 |  3 |   Go back to the homepage.                                       | Verify that the `Notification` icon button has a red dot with a number on it indicating the number of updates received.  |  
 |  4 |  Click the `Notification` icon button                            | Verify that the notifications are displayed properly starting from the most recent update.   |  

**Post-conditions:**  
The notification is received by the user from the system.