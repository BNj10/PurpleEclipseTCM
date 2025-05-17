## **THREAD-0001:** Thread testing - Create Thread  

> **Summary:** Verify that user can create thread/discussion within a subforum  <br>

**Preconditions:** The user must be logged in.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |   Visit the homepage                                        | Verify that the list of threads are shown             | 
 |  2 |   Click the `Post Thread` button                            | Verify that `Select a Subforum to Post` overlay and `Create New Thread` form is shown.   | 
 |  3 |   Check the `Select a Subforum to Post` overlay             | Verify that the forums and subforums are shown.  | 
 |  4 |   Click a subforum to post.                                 | Verify that the overlay is hidden.   |  
 |  5 |   Click the `Category` combobox.                            | Verify that the categories are shown.   |   
 |  6 |   Click a `Category`                                        | Verify that it the clicked category will be the value of the `Category` field. | 
 |  7 |   Set the textbox under the `Title` label as any description of the thread. | Verify that the input will be the value of the title textbox. | 
 |  8 |   Set the content related to the thread title or category.  | Verify that the content will be the same as inputted text. |
 |  9 |   Wait until the loading is complete.                       | Verify that the overlay will be hidden.|  
 |  10 |  Check the subforum’s list under the forum.                | Verify that the subforum created will be added on the list.|  

**Post-conditions:** 
The subforum will be added on the list.