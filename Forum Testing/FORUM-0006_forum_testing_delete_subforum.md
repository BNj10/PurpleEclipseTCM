## **FORUM-0006:** Forum testing - Delete Subforum  

> **Summary:** Verify that subforum is deleted successfully   <br>

**Preconditions:** The user should be an admin. 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.                                           | Verify that the homepage is shown.   | 
 |  2 |   Click `Forums` button on the navigation bar.                  | Verify that forum list is displayed.   | 
 |  3 |  Click a subforum under a forum.                                |Verify that the subforum is shown along with the existing list of threads.   | 
 |  4 |   Click the `Delete` icon button beside the `Edit` icon button  | Verify that the ‘Delete Subforum’ overlay is shown.  | 
 |  5 | Wait until the loading is complete.                             | Verify that the overlay will be hidden. |  
 |  6 |  Check the forum’s list.                                        | Verify that the subforum is deleted and removed from the list.   |  

**Post-conditions:**  
The forum is removed from the forum list. 
