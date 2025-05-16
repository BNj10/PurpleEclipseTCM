## **FORUM-0003:** Forum testing - Delete Forum  

> **Summary:** Verify that forum is deleted successfully  <br>

**Preconditions:** The user should be an admin  

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.                           | Verify that the homepage is shown.  | 
 |  2 |   Click `Forums` button on the navigation bar.  | Verify that forum list is displayed.   | 
 |  3 |   Click the trash icon of a specific forum.     | Verify that the delete forum overlay is shown.   |
 |  4 |   Click the `Delete Forum` button.              | Verify that the buttons are clickable and disabled.   |
 |  5 |   Wait until the loading is complete.           | Verify that the overlay will be hidden.   |
 |  6 |   Check the forum’s list.                       | Verify that the forum deleted is removed from the forums list.  |

**Post-conditions:**  
The forum is removed from the forum list.
