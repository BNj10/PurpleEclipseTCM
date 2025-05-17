## **THREAD-0004:** Thread testing - Post Comment  

> **Summary:** Verify that user can post a comment on any thread/discussion  <br>

**Preconditions:** The user should be logged in.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Visit the homepage.                | Verify that the homepage is shown.  | 
 |  2 |  Click a `Thread`                   | Verify that the comments and the thread is shown. | 
 |  3 |  Write a comment.                   | Verify that the text field value reflects the inputted text. |  
 |  4 | Click the `Post Comment` button     | Verify that the `toast notification` is shown.  |  
 |  5 | Wait until the loading is complete. | Verify that the comment created will be displayed on the list as comments for the paticular thread.  |  

**Post-conditions:**  
The thread will gain another comment from a user.
