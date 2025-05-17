## **THREAD-0007:** Thread testing - Filter  

> **Summary:** Verify that search filters work successfully  <br>

**Preconditions:**  
1. The user must be logged in.
2. The user must be on the platform’s homepage.

Scenario 1 

 | \# | Step | Expected Behavior | 
 |----|------|-------------------| 
 |  1 |  Click the `search bar`.                    | Verify that the search bar is highlighted. |
 |  2 | Set the search text field value to ‘GALENG’ | Verify that the text field value reflects the inputted text |  
 |  3 | Click the `By Username` filter              | Verify that the thread created by the user is shown. |  
 |  4 | Click the `Content` filter                  | Verify that there is no thread displayed |  
 |  5 | Click the `All` filter                      | Verify that all the results from both filters are shown. |  

**Post-conditions:**  
None
