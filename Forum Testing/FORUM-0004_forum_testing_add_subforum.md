## **FORUM-0004:** Forum testing - Add Subforum  

> **Summary:** Verify that subforum is added and displayed successfully  <br>

**Preconditions:** The user should be an admin
 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.   | Verify that the homepage is shown.   | 
 |  2 |   Click `Forums` button on the navigation bar.   | Verify that forum list is displayed.   | 
 |  3 |   On an existing forum, click the `+` button   | Verify that `Create Subforum in "Forum Name"` overlay is shown.   |
 |  4 |   Set the textbox with `Enter subforum name` placeholder to any subforum name you want.   | Verify that the textbox’s value is the same as what you have inputted.   |  
 |  5 |   Set the textbox with `Describe this subforum` placeholder to any description of the subforum you created.   | Verify that the textbox’s value is the same as what you have inputted.   |    
 |  6 |  Click the combobox.    | Verify that it will show the icons.  |  
 |  7 |  Click an icon that relates to the subforum.    | Verify that `Select an icon` combobox’s value is the same as what you have clicked.  |  
 |  8 |   Click `Create Subforum` button.   | Verify that the buttons are disabled.  |  
 |  9 |   Wait until the loading is complete.   | Verify that the overlay will be hidden.  |  
 |  10|   Check the subforum’s list under the forum.  | Verify that the subforum created will be added on the list.   |  

**Post-conditions:**  
The subforum will be added to the subforum list under the forum.

Scenario 2

**Preconditions:** The user should be an admin

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.   | Verify that the homepage is shown.   | 
 |  2 |   Click `Forums` button on the navigation bar.   | Verify that forum list is displayed.   | 
 |  3 |   On an existing forum, click the `+` button.   |Verify that `Create Subforum in "Forum Name"` overlay is shown.   | 
 |  4 |   Click the `Create Subforum` button   | Verify that the buttons are disabled.  | 
 |  5 |   Wait until the loading is complete.      | Verify that it will force you to put a name of the subforum.   |  

**Post-conditions:**  
None


