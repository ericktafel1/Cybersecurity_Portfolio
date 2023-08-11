# Entry 1 Scenario

Review the following scenario. Then complete the step-by-step instructions.

A small U.S. health care clinic specializing in delivering primary-care services experienced a security incident on a Tuesday morning, at approximately 9:00 a.m. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.

Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key. 

The attackers were able to gain access into the company's network by using targeted phishing emails, which were sent to several employees of the company. The phishing emails contained a malicious attachment that installed malware on the employee's computer once it was downloaded.

Once the attackers gained access, they deployed their ransomware, which encrypted critical files. The company was unable to access critical patient data, causing major disruptions in their business operations. The company was forced to shut down their computer systems and contact several organizations to report the incident and receive technical assistance.

## Step 1: Access the template

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/Incident_Handler_Journal/Supporting_Documents)

--------------------------------------------------------------------------------------------------------------------------------

## Step 2: Review the scenario

Review the details of the scenario. Consider the following key details:

- A small U.S. health care clinic experienced a security incident on Tuesday at 9:00 a.m. which severely disrupted their business operations.
- The cause of the security incident was a phishing email that contained a malicious attachment. Once it was downloaded, ransomware was deployed encrypting the organization's computer files.
- An organized group of unethical hackers left a ransom note stating that the company's files were encrypted and demanded money in exchange for the decryption key

--------------------------------------------------------------------------------------------------------------------------------

## Step 3: Record a journal entry

Use the incident handler's journal to document your first journal entry about the given scenario. Ensure that you fill in all of the fields:

- In the Date section, record the date of your journal entry. This should be the actual date that you record the entry, not a fictional date.
- In the Entry section, provide a journal entry number. For example, if it is your first journal entry, enter 1.
- In the Description section, provide a description about the entry.
- In the Tool(s) used section, if any cybersecurity tools were used, list them here. 
- In the The 5 W's section, record the details about the given scenario.
  - Who caused the incident?
  - What happened?
  - When did the incident occur?
  - Where did the incident happen?
  - Why did the incident happen?

In the Additional notes row, record any thoughts or questions you have about the given scenario.

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 2, 3, and 4 are labs. Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 5 Scenario

Review the scenario. Then complete the step-by-step instructions.

You are a level-one security operations center (SOC) analyst at a financial services company. Previously, you received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, the attachment has already been verified malicious. Now that you have this information, you must follow your organization's process to complete your investigation and resolve the alert.

Your organization's security policies and procedures describe how to respond to specific alerts, including what to do when you receive a phishing alert. 

In the playbook, there is a flowchart and written instructions to help you complete your investigation and resolve the alert. At the end of your investigation, you will update the alert ticket with your findings about the incident.

## Step 1: Access the template

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/Incident_Handler_Journal/Supporting_Documents)

--------------------------------------------------------------------------------------------------------------------------------

## Step 2: Review the playbook and flowchart

Before you begin investigating the alert, take a moment to review the playbook and flowchart because you'll be using them throughout the investigation.

The Phishing Playbook instructions provide detailed, written instructions about each step represented in the flowchart.

The Phishing Flowchart provides a high-level overview and visual representation of the sequence of steps and substeps you'll take to respond to a phishing alert.

Note: The steps in theis playbook are not a definitive guide to responding to a phishing incident. Organizations have their own sets of policies, standards, and procedures that determine the expected response actions to incidents.

--------------------------------------------------------------------------------------------------------------------------------

## Step 3: Update the alert ticket status

In the Alert ticket template, begin the investigation by updating the Ticket status dropdown list to Investigating.

--------------------------------------------------------------------------------------------------------------------------------

## Step 4: Evaluate the alert

For this exercise, begin with the second step in the playbook, Evaluate the alert, because you've already received and accessed the phishing alert ticket. 

As a security analyst, you'll want to gain a complete understanding of why the alert was triggered. Create a new entry in your incident handler's journal to record the details of this security incident and gather your thoughts. You'll refer to these notes as you progress through the steps in the playbook. 

Then, evaluate the contents of the Alert ticket, including the content in the Additional information section. Here are some examples of elements to examine when you are evaluating the alert ticket details:

- Alert severity: According to the playbook instructions, an alert severity of Medium or High is a good indication that a ticket might require escalation.
- Sender details: Analyzing the sender details of an email is important because it can reveal inconsistencies that can indicate a phishing attempt. Often, phishing emails try to impersonate trusted entities. For example, if there is a mismatch between the sender's email address and the sender's name, this is a good indication that the email might be a phishing email.
- Message body: It's important to analyze the message body (and subject line) of an email because phishing emails often contain grammatical errors, which can be an indication of a phishing attempt.
- Attachments or links: Phishing emails contain malicious links or attachments that are used to steal sensitive information or download malicious software or code on the recipient's device. Check to see whether a file has been attached to this email.

After you've evaluated the contents of the alert ticket, answer the 5 W's of this incident to gather the information you need to understand the nature of the alert. The 5 W's are:

- Who caused the incident?
- What happened?
- When did the incident take place?
- Where did the incident occur?
- Why did it happen?

At the end of this step, you should have 2-3 reasons on why you believe the phishing alert is or isn't legitimate.

--------------------------------------------------------------------------------------------------------------------------------

## Step 5: Determine whether the alert should be escalted

After evaluating the alert details, use the Phishing Playbook's Step 3.0 and Step 3.1 to determine whether the email contains links or attachments and whether these links or attachments are malicious. Remember you've already determined that the email contains an attachment that has been verified as malicious through its file hash. 

Proceed to the Phishing Playbook's Step 3.2 if you've determined that the alert should be escalated. If you've determined that the alert should not be escalated, proceed to the Phishing Playbook's Step 4.

--------------------------------------------------------------------------------------------------------------------------------

## Step 6: Update the alert ticket status

Now that you've examined the email details, complete the final step of the playbook and update the alert ticket in the activity template. Depending on whether you want to escalate or close the alert:

- Under the Ticket status column of the alert ticket template, update the status of the ticket to either Closed or Escalated.
- Under the Ticket comments column of the alert ticket template, use the details you've found to explain the steps taken and why you chose to escalate or close the ticket. Include 2-3 reasons as to why you believe this alert should be escalated or closed.

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 6 Scenario

Review the following scenario. Then complete the step-by-step instructions.

You recently joined the security team as a level-one security operation center (SOC) analyst at a mid-sized retail company. Along with its physical store locations, your company also conducts operations in e-commerce, which account for 80% of its sales.

You are spending your first week of training becoming familiar with the company's security processes and procedures. Recently, the company experienced a major security incident involving a data breach of over one million users. Because this was a recent and major security incident, your team is working to prevent incidents like this from happening again. This breach happened before you began working at the company. You have been asked to review the final report.

To gain an understanding of the incident's life cycle, your goals for your review are as follows:

- Goal 1: Identify exactly what happened.
- Goal 2: Identify when it happened. 
- Goal 3: Identify the response actions that the company took.
- Goal 4: Identify future recommendations.

## Step 1: Access the supporting materials

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/Incident_Handler_Journal/Supporting_Documents)

--------------------------------------------------------------------------------------------------------------------------------

## Step 2: Answer the questions about the final report

1. What type of security incident was the organization affected by?
   
   _Data theft_

3. Which section of the report includes an explanation of the root cause of the incident?
   
   _Investigation_

5. What did the attacker use to exploit the e-commerce web application vulnerability?
   
   _Forced browsing_

7. What recommendations did the organization implement to prevent future recurrences? Select two answers.
   
   _Implemented access control mechanisms_
   
   _Implemented routine vulnerability scans_

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 7 is a lab. Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 8 Scenario

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst working at the e-commerce store Buttercup Games. You've been tasked with identifying whether there are any possible security issues with the mail server. To do so, you must explore any failed SSH logins for the root account.  

## Step 1: Access supporting materials

The following supporting materials will help you complete this activity. The data contains log and event information from Buttercup Games' mail servers and web accounts. This includes information like access and authentication logs, email logs, and more.

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/Incident_Handler_Journal/Supporting_Documents)

--------------------------------------------------------------------------------------------------------------------------------

## Step 2: Create a Splunk Cloud account and sign up for the free Splunk Cloud trial

To use Splunk Cloud, you must create an account. Follow Part 1 - Create a Splunk Cloud account and Part 2 - Verify your email in the Follow-along guide for Splunk sign-up to create an account. After you've created your Splunk account, you'll need to sign up for a free Splunk Cloud trial. Follow Part 3 - Activate a Splunk Cloud trial in the Follow-along guide for Splunk sign-up.

--------------------------------------------------------------------------------------------------------------------------------

## Step 3: Upload data into Splunk

To operate effectively, it's essential that SIEM tools ingest and index data. SIEM tools collect and process data so that it becomes searchable events that can be queried, viewed, and analyzed.

So far, you've created a Splunk account and activated and accessed the Splunk Cloud free trial, but your Splunk Cloud instance does not contain any data. Next, you'll need to upload data into Splunk to start querying. Complete the following steps to upload data into Splunk:

1. If you haven't already, download the data file from Step 1:  tutorialdata.zip. Click the link then click the download icon. Do not uncompress the file.

2. Navigate to Splunk Home from your Splunk Cloud free trial instance. You might need to log in again using your credentials from Step 3.

3. On the Splunk bar, click Settings. Then click the Add Data icon.

4. Click Upload.

5. Click the Select File button.

6. Upload the ```tutorialdata.zip``` file, and click Open.

7. Click the Next button to continue to Input Settings.
  
8. By the Host section, select Segment in path and enter 1 as the segment number.

9. Click the Review button and review the details of the upload before you submit. The details should be as follows: 


Input Type: Uploaded File

File Name: tutorialdata.zip

Source Type: Automatic

Host: Source path segment number: 1 

Index: Default


10. Click Submit. Once Splunk has ingested the data, you will receive confirmation that the file was successfully uploaded.

--------------------------------------------------------------------------------------------------------------------------------

## Step 4: Perform a basic search

Take a moment to examine the Splunk Cloud interface by locating the app panel, the Explore Splunk panel, and the Splunk bar.
The Splunk home page for Splunk Cloud Platform displays the Apps panel, the Splunk bar and the Explore Splunk panel

Now that you've uploaded the data into Splunk, perform your first query to confirm that the data has been ingested, indexed, and is searchable. Follow these steps to perform a query:

1. Navigate to Splunk Home. (To return to Splunk Home, click the Splunk Cloud logo on the Splunk Cloud page.)

2. Click Search & Reporting. You may close any pop ups that appear.

3. In the search bar,  enter your search query:
    ```index=main```
    This search term specifies the index. An index is a repository for data. Here, the index is a single dataset containing events from an index named main.

4. Select All Time from the time range dropdown to search for all the events across all time.

5. Click the search button. Note that the search button is represented by the magnifying glass icon. Your search should retrieve thousands of events.

The Splunk Cloud search page displays the search bar and the time range drop down

--------------------------------------------------------------------------------------------------------------------------------

## Step 5: Evaluate the fields

When Splunk indexes data, it attaches fields to each event. These fields become part of the searchable index event data. This helps security analysts easily search for and find the specific data they need. Now that you've run your first query, examine the search results and the fields.

For each event the fields are host, source, and sourcetype. Under SELECTED FIELDS, examine the same fields.
Splunk search results with the host, source, and sourcetype fields highlighted in red box

Examine the field values by clicking on the field under SELECTED FIELDS. You should observe the following:

- host: The host field specifies the name of the network host from which the event originated. In this search there are five hosts:

 - ```mailsv``` - Buttercup Games' mail server. Examine events generated from this host.

 - ```www1``` - This is one of Buttercup Games' web applications.

 - ```www2``` - This is one of Buttercup Games' web applications.

 - ```www3``` - This is one of Buttercup Games' web applications.

 - ```vendor_sales``` - Information about Buttercup Games' retail sales.

- source: The source field indicates the file name from which the event originates. You should identify eight sources. Notice ```/mailsv/secure.log```, which is a log file that contains information related to authentication and authorization attempts on the mail server.

- sourcetype: The sourcetype determines how data is formatted. You should observe three sourcetypes. Examine ```secure-2```.

--------------------------------------------------------------------------------------------------------------------------------

## Step 6: Narrow your search

Because you've been tasked with exploring any failed SSH logins for the root account on the mail server, you'll need to narrow the search results for events from the mail server.

Under SELECTED FIELDS, click host and click mailsv.

Notice that a new term has been added to the search bar: ```index=main host=mailsv```. The search results have narrowed to over 9000 events that are generated by the mail server.

--------------------------------------------------------------------------------------------------------------------------------

## Step 7: Search for a failed login for root

Now that you've narrowed your search results to events generated by the mail server, continue to narrow the search to locate any failed SSH logins for the root account. 

1. Clear the search bar.

2. Enter ```index=main host=mailsv fail* root``` into the search bar.
   
    This search expands on the search from the previous task and searches for the keyword ```fail*```. The wildcard tells Splunk to expand the search term to find other terms that contain the word fail such as failure, failed, etc. Lastly, the keyword root searches for any event that contains the term ```root```.

3. Click search.

--------------------------------------------------------------------------------------------------------------------------------

## Step 8: Evaluate the search results

Your search from the previous task should have retrieved search results for over 300 events. Navigate to other pages of the search results to observe the events not listed on the first page of results.


--------------------------------------------------------------------------------------------------------------------------------

## Step 9: Answer questions about the search results

1. How many events are contained in the main index across all time?

   _Over 100,000_

2. Which field identifies the name of a network device or system from which an event originates?

   _```host```_

3. Which of the following hosts used by Buttercup Games contains log information relevant to financial transactions?

   _```vendor_sales```_

4. How many failed SSH logins are there for the root account on the mail server?

   _More than 100_

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 8 Scenario

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst at a financial services company. You receive an alert that an employee received a phishing email in their inbox. You review the alert and identify a suspicious domain name contained in the email's body: signin.office365x24.com. You need to determine whether any other employees have received phishing emails containing this domain and whether they have visited the domain. You will use Chronicle to investigate this domain.





