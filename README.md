
This two folders are two collections of requests created and exported from Postman (Collection v2.1). All links and authorizations key are valid

Each folder represents the tests for MAIN TASK and BONUS TASK.

In the MAIN TASK folder you can find all created tests according to the MAIN TASK. For better understading this collection the requests are represented as a tree with following structure:
MAIN TASKS
   Create New Pet
     Positive testing cases
     Negative testing cases
     Validation
       Form fields validation
          Positive testing cases
          Negative testing cases
       Fields validation
          Numeric fields (int64)
              Type of entered data
                  Valid data
                  Invalid data
              Format of entered data
                  Valid format
                  Invalid format
          Text fields (string)
              Valid data
                  Format of entered data
                  Type of entered data
                      Text
              Invalid data
     Tag sorting
   Update Pet
     Positive testing
        Update the name of existing pet
        Update all fields
        Update only required fields
        Update only non-required fields
        Update empty "Tag" field
        Update empty "Category" field
        Update "Status" field
        Update "Tag" field (add one more tag)
        Update "Tag" field (delete added tags)
        Update "Tag" field (delete one tag when several tags were added)
        Update "URL" field (add one more URL)
        Update "URL" field (delete one URL when several URLs were added)
     Negative testing
        Update non-existing Pet
        Update "URL" field (delete all added)
        Update "URL" field (the first URL was saved as empty)
        Update "URL" field (the last URL was saved as empty)
        Update "URL" field (the middle URL was saved as empty)
        Update "Name" field (save empty)
        Update "Status" field with non-existing status
        Update "Tag" field (the first tag was saved as empty)
        Update "Tag" field (the last tag was saved as empty)
        Update "Tag" field (the middle tag was saved as empty)
   Delete Pet
     Positive testing cases
        Delete existing pet
     Negative testing cases
        Delete non-existing pet
   Search
   Security testing
     SQL injections
     XSS injections

All mentioned folders contain created request. In order to execute testing send request one by one from up to down. All needed values are specified in them.

Also these requests are mentioned in the created defect reports so you can use them in order to reproduce the found defects.


In the BONUS TASK folder you can find all created tests according to the BONUS TASK. For better understading this collection the requests are represented as a tree with following structure:
BONUS TASKS
   Create Purchase
     Create purchase with existing pet
     Create purchase with non-existing pet
     Validation
        Invalid data
        Valid data
   Delete Purchase
     Delete existing order
     Delete non-existing order


All mentioned folders contain created request. In order to execute testing send request one by one from up to down. All needed values are specified in them.

Also these requests can be used during test run of created test cases according to BONUS TASK