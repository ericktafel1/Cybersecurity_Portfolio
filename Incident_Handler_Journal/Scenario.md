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

