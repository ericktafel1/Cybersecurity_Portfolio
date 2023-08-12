# Entry 1 Scenario

Review the following scenario. Then complete the step-by-step instructions.

A small U.S. health care clinic specializing in delivering primary-care services experienced a security incident on a Tuesday morning, at approximately 9:00 a.m. Several employees reported that they were unable to use their computers to access files like medical records. Business operations shut down because employees were unable to access the files and software needed to do their job.

Additionally, employees also reported that a ransom note was displayed on their computers. The ransom note stated that all the company's files were encrypted by an organized group of unethical hackers who are known to target organizations in healthcare and transportation industries. In exchange for restoring access to the encrypted files, the ransom note demanded a large sum of money in exchange for the decryption key. 

The attackers were able to gain access into the company's network by using targeted phishing emails, which were sent to several employees of the company. The phishing emails contained a malicious attachment that installed malware on the employee's computer once it was downloaded.

Once the attackers gained access, they deployed their ransomware, which encrypted critical files. The company was unable to access critical patient data, causing major disruptions in their business operations. The company was forced to shut down their computer systems and contact several organizations to report the incident and receive technical assistance.

## Step 1: Access the template

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/9_Incident_Handler_Journal/Supporting_Documents)

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

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/9_Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 2, 3, and 4 are labs.

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/9_Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 5 Scenario

Review the scenario. Then complete the step-by-step instructions.

You are a level-one security operations center (SOC) analyst at a financial services company. Previously, you received a phishing alert about a suspicious file being downloaded on an employee's computer. After investigating the email attachment file's hash, the attachment has already been verified malicious. Now that you have this information, you must follow your organization's process to complete your investigation and resolve the alert.

Your organization's security policies and procedures describe how to respond to specific alerts, including what to do when you receive a phishing alert. 

In the playbook, there is a flowchart and written instructions to help you complete your investigation and resolve the alert. At the end of your investigation, you will update the alert ticket with your findings about the incident.

## Step 1: Access the template

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/9_Incident_Handler_Journal/Supporting_Documents)

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

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/9_Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

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

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/9_Incident_Handler_Journal/Supporting_Documents)

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

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/9_Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 7 is a lab.

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/9_Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 8 Scenario

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst working at the e-commerce store Buttercup Games. You've been tasked with identifying whether there are any possible security issues with the mail server. To do so, you must explore any failed SSH logins for the root account.  

## Step 1: Access supporting materials

The following supporting materials will help you complete this activity. The data contains log and event information from Buttercup Games' mail servers and web accounts. This includes information like access and authentication logs, email logs, and more.

Please refer to [Supporting Documents](https://github.com/ericktafel1/Cybersecurity_Portfolio/tree/main/9_Incident_Handler_Journal/Supporting_Documents)

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

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/9_Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)

--------------------------------------------------------------------------------------------------------------------------------

# Entry 9 Scenario

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst at a financial services company. You receive an alert that an employee received a phishing email in their inbox. You review the alert and identify a suspicious domain name contained in the email's body: ```signin.office365x24.com```. You need to determine whether any other employees have received phishing emails containing this domain and whether they have visited the domain. You will use Chronicle to investigate this domain.

## Step 1: Launch Chronicle

Click the link to launch Chronicle.

On the Chronicle home page, you’ll find the current date and time, a search bar, and details about the total number of log entries. There are already a significant number of log events ingested into the Chronicle instance.

--------------------------------------------------------------------------------------------------------------------------------

## Step 2: Perform a domain search

To begin, complete these steps to perform a domain search for the domain contained in the phishing email. Then, search for events using information like hostnames, domains, IP addresses, URLs, email addresses, usernames, and file hashes. 

1. In the search bar, type ```signin.office365x24.com``` and click Search. Under DOMAINS, ```signin.office365x24.com``` will be listed. This tells you that the domain exists in the ingested data. 

2. Click ```signin.office365x24.com``` to complete the search.

--------------------------------------------------------------------------------------------------------------------------------

## Step 3: Evaluate the search results

After performing a domain search, you'll be in the domain view. Evaluate the search results and observe the following:

1. VT CONTEXT: This section provides the VirusTotal information available for the domain. 

2. WHOIS: This section provides a summary of information about the domain using WHOIS, a free and publicly available directory that includes information about registered domain names, such as the name and contact information of the domain owner. In cybersecurity, this information is helpful in assessing a domain's reputation and determining the origin of malicious websites. 

3. Prevalence: This section provides a graph which outlines the historical prevalence of the domain. This can be helpful when you need to determine whether the domain has been accessed previously. Usually, less prevalent domains may indicate a greater threat. 

4. RESOLVED IPS: This insight card provides additional context about the domain, such as the IP address that maps to ```signin.office365x24.com```, which is ```40.100.174.34```. Clicking on this IP will run a new search for the IP address in Chronicle. Insight cards can be helpful in expanding the domain investigation and further investigating an indicator to determine whether there is a broader compromise.

5. SIBLING DOMAINS: This insight card provides additional context about the domain. Sibling domains share a common top or parent domain. For example, here the sibling domain is listed as ```login.office365x24.com```, which shares the same top domain ```office365x24.com``` with the domain you're investigating: ```signin.office365x24.com```.

6. ET INTELLIGENCE REP LIST: This insight card includes additional context on the domain. It provides threat intelligence information, such as other known threats related to the domains using ProofPoint's Emerging Threats (ET) Intelligence Rep List.

7. Click TIMELINE. This tab provides information about the events and interactions made with this domain. Click EXPAND ALL to reveal the details about the HTTP requests made including ```GET``` and ```POST``` requests.  A GET request retrieves data from a server while a POST request submits data to a server.

8. Click ASSETS. This tab provides a list of the assets that have accessed the domain.

--------------------------------------------------------------------------------------------------------------------------------

## Step 4: Investigate the threat intelligence data

Now that you've retrieved results for the domain name, the next step is to determine whether the domain is malicious. Chronicle provides quick access to threat intelligence data from the search results that you can use to help your investigation. Follow these steps to analyze the threat intelligence data and use your incident handler's journal to record interesting data:

1. Click on VT CONTEXT to analyze the available VirusTotal information about this domain. There is no VirusTotal information about this domain. To exit the VT CONTEXT window, click the X.

2. By Top Private Domain, click ```office365x24.com``` to access the domain view for ```office365x24.com```. Click VT CONTEXT to assess the VirusTotal information about this domain. In the pop up, you can observe that one vendor has flagged this domain as malicious. Exit the VT CONTEXT window. Click the back button in your browser to go back to the domain view for the ```signin.office365x24.com``` search.

3. Click on the ET INTELLIGENCE REP LIST insight card to expand it, if needed. Take note of the category.

--------------------------------------------------------------------------------------------------------------------------------

## Step 5: Investigate the affected assets and events

Information about the events and assets relating to the domain are separated into the two tabs: TIMELINE and ASSETS. TIMELINE shows the timeline of events that includes when each asset accessed the domain. ASSETS list hostnames, IP addresses, MAC addresses, or devices that have accessed the domain. 

Investigate the affected assets and events by exploring the tabs:

1. ASSETS: There are several different assets that have accessed the domain, along with the date and time of access. Using your incident handler's journal, record the name and number of assets that have accessed the domain. 

2. TIMELINE: Click EXPAND ALL to reveal the details about the HTTP requests made, including ```GET``` and ```POST``` requests. The ```POST``` information is especially useful because it means that data was sent to the domain. It also suggests a possible successful phish. Using your incident handler's journal, take note of the ```POST``` requests to the ```/login.php``` page. For more details about the connections, open the raw log viewer by clicking the open icon.

--------------------------------------------------------------------------------------------------------------------------------

## Step 6: Investigate the resolved IP address

So far, you have collected information about the domain's reputation using threat intelligence, and you've identified the assets and events associated with the domain. Based on this information, it's clear that this domain is suspicious and most likely malicious. But before you can confirm that it is malicious, there's one last thing to investigate.

Attackers sometimes reuse infrastructure for multiple attacks. In these cases, multiple domain names resolve to the same IP address.

Investigate the IP address found under the RESOLVED IPS insight card to identify if the ```signin.office365x24.com``` domain uses another domain. Follow these steps: 

1. Under RESOLVED IPS, click the IP address ```40.100.174.34```.

2. Evaluate the search results for this IP address and use your incident handler's journal to take note of the following:

  a. TIMELINE: Take note of the additional ```POST``` request. A new ```POST``` suggests that an asset may have been phished.

  b. ASSETS: Take note of the additional affected assets.

  c. DOMAINS: Take note of the additional domains associated with this IP address.

--------------------------------------------------------------------------------------------------------------------------------

## Step 7: Answer questions about the domain investigation

1. According to available ET Intelligence Rep list, how is ```signin.office365x24.com```

   _Drop site for logs or stolen credentials_

2. Which assets accessed the ```signin.office365x24.com``` domain? Select three answers

   _```roger-spence-pc```_

   _```coral-alvarez-pc```_

   _```emil-palmer-pc```_

3. Which IP address does the ```signin.office365x24.com``` domain resolve to?

   _```40.100.174.34```_

4. How many ```POST``` requests were made to the ```signin.office365x24.com``` domain?

  _6_

5. Some ```POST``` requests were made to ```signin.office365x24.com```. What is the target URL of the web page that the ```POST``` requests were made to?

   _```http://signin.office364x24.com/login.php```_

6. Which domains does the IP address ```40.100.174.34``` resolve to? Select two answers?

   _```signin.accounts-google.com```_

   _```signin.office365x24.com```_

Please refer to [Tafel Incident handler's journal](https://github.com/ericktafel1/Cybersecurity_Portfolio/blob/main/9_Incident_Handler_Journal/Tafel_Incident_handler's_journal.pdf)
