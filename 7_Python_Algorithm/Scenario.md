# Scenario

Review the following scenario. Then complete the step-by-step instructions.

You are a security professional working at a health care company. As part of your job, you're required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees you must remove from this allow list.

Your task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, you should remove those IP addresses from the file containing the allow list.

Note: This scenario involves developing the same algorithm that is developed in Tasks 2-7 of the Create another algorithm lab. (You do not need to reference Task 1 and Tasks 8-10 of the lab to complete this portfolio activity.) You should revisit the lab to get screenshots to include in your portfolio document. 

## Step 1: Access the template

To use the template for this course item, click the link and select Use Template. (In this step, you will just open the template. More instructions for how to use the template will be included in later steps.)

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/7_Python_Algorithm/Supporting_Documents)

--------------------------------------------------------------------------------------------------------------------------------

## Step 2: Open the file that contains the allow list

The file that you want to open is called ```"allow_list.txt"```. Assign a string containing this file name to the ```import_file``` variable. Then, use a ```with``` statement to open it. Use the variable ```file``` to store the file while you work with it inside the ```with``` statement.

Describe the Python syntax, functions, and keywords you need to accomplish this in the Open the file that contains the allow list section of the Algorithm for file updates in Python template. In the Task 2 section of Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

--------------------------------------------------------------------------------------------------------------------------------

## Step 3: Read the file contents

Next, use the ```.read()``` method to convert the contents of the allow list file into a string so that you can read them. Store this string in a variable called ```ip_addresses```.

Describe the Python syntax, functions, and keywords you need to accomplish this in the Read the file contents section of the Algorithm for file updates in Python template. In the Task 3 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.


--------------------------------------------------------------------------------------------------------------------------------

## Step 4: Convert the string into a list

In order to remove individual IP addresses from the allow list, the IP addresses need to be in a list format. Therefore, use the ```.split()``` method to convert the ```ip_addresses``` string into a list.

Describe the Python syntax, functions, and keywords you need to accomplish this in the Convert the string into a list section of the Algorithm for file updates in Python template. In the Task 4 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.


--------------------------------------------------------------------------------------------------------------------------------

## Step 5: Iterate through the remove list

A second list called ```remove_list``` contains all of the IP addresses that should be removed from the ```ip_addresses``` list. Set up the header of a ```for``` loop that will iterate through the ```remove_list```. Use ```element``` as the loop variable.

Describe the Python syntax, functions, and keywords you need to accomplish this in the Iterate through the remove list section of the Algorithm for file updates in Python template. In the Task 5 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.


--------------------------------------------------------------------------------------------------------------------------------

## Step 6: Remove IP addresses that are on the remove list

In the body of your iterative statement, add code that will remove all the IP addresses from the allow list that are also on the remove list. First, create a conditional that evaluates if the loop variable ```element``` is part of the ```ip_addresses list```. Then, within that conditional, apply the ```.remove()``` method to the ```ip_addresses``` list and remove the IP addresses identified in the loop variable ```element```. 

Describe the Python syntax, functions, and keywords you need to accomplish this in the Remove IP addresses that are on the remove list section of the Algorithm for file updates in Python template. In the Task 6 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

In addition, include a sentence that explains that applying the ```.remove()``` method in this way is possible because there are no duplicates in the ```ip_addresses``` list. 


--------------------------------------------------------------------------------------------------------------------------------

## Step 7: Update the file with the revised list of IP addresses

Now that you have removed these IP addresses from the ```ip_address``` variable, you can complete the algorithm by updating the file with this revised list. To do this, you must first convert the ```ip_addresses``` list back into a string using the ```.join()``` method. Apply ```.join()``` to the string ```"\n"``` in order to separate the elements in the file by placing them on a new line.

Then, use another ```with``` statement and the ```.write()``` method to write over the file assigned to the ```import_file``` variable.

Describe the Python syntax, functions, and keywords you need to accomplish this in the Update the file with the revised list of IP addresses section of the Algorithm for file updates in Python template. In the Task 7 section of the Create another algorithm lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

--------------------------------------------------------------------------------------------------------------------------------

## Step 8: Finalize your document

To finalize the document and make its purpose clear to potential employers, be sure to complete the Project description and Summary sections of the Algorithm for file updates in Python template. 

In the Project description section, give a general overview of the scenario and what you accomplished in Python. Write three to five sentences.

In the Summary section, provide a short summary of the algorithm by highlighting its main components. Write four to six sentences.


Please refer the [Tafel Algorithm for file updates in Python](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/7_Python_Algorithm/Tafel_Algorithm_for_file_updates_in_Python.pdf) 






