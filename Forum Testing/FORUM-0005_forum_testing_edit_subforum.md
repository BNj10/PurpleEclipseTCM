## **FORUM-0005:** Forum testing - Edit Subforum  

> **Summary:** Verify that subforum is edited and displayed successfully  <br>

**Preconditions:** The user should be an admin
 

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.   | Verify that the homepage is shown.   | 
 |  2 |   Click `Forums` button on the navigation bar.   | Verify that forum list is displayed.   | 
 |  3 |  Click a subforum under a forum   | Verify that the subforum is shown along with the existing list of threads.   |
 |  4 |   Click the `Edit` button beside the `Delete` button.   | Verify that the ‘Edit Subforum’ overlay is shown.   |  
 |  5 |   Set the ‘Enter subforum title’ textbox to any subforum name you want.   | Verify that the ‘Enter subforum name’ textbox’s value is the same as what you have inputted.   |    
 |  6 | Set the ‘Describe this subforum’ textbox to any description of the subforum you created.    | Verify that the ‘Describe this subforum’ textbox’s value is the same as what you have inputted.  |  
 |  7 | Click the combobox.   | Verify that it will show the icons.  |  
 |  8 |   Click an icon that relates to the subforum.  | Verify that `Select an icon` combobox’s value is the same as what you have clicked.  |  
 |  9 |   Click `Create Subforum` button.   | Verify that the buttons are disabled.  |  
 |  10|   Wait until the loading is complete.  | Verify that the overlay will be hidden.  |  

**Post-conditions:**  
The subforum will be added to the subforum list under the forum.

Scenario 2

**Preconditions:** The user should be an admin

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage.   | Verify that the homepage is shown.   | 
 |  2 |   Click `Forums` button on the navigation bar.   | Verify that forum list is displayed.   | 
 |  3 |  Click a subforum under a forum.   |Verify that the subforum is shown along with the existing list of threads.   | 
 |  4 |   Click the `Edit` icon button beside the `delete` icon button   | Verify that the 'Edit Subforum' overlay is shown.  | 
 |  5 |  Remove the default value of the textbox   | Verify that the textbox will be empty.  |  
 |  6 |  Click `Save Changes` button.     | Verify that it will force you to put a name of the subforum.   |  

**Post-conditions:**  
None
