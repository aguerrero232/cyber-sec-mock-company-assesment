### Contributors - Ariel Guerrero, Jasmine Beale

___

## ***NARO Cyber Security Model***  

___

## ***Model Background***

The **Information Technology Laboratory** at the National Institute of Standards and
Technology promotes the U.S. economy and public welfare by providing technical
leadership for the Nation’s measurement and standards infrastructure. <sup>1</sup> Information Technology Laboratory develops tests, test methods, reference data, proof of concept implementations, and technical analyses to advance the
development and productive use of information technology. Information Technology Laboratory’s responsibilities include the development of management, administrative, technical, and physical standards and guidelines for
the cost-effective security and privacy of other than national security-related information in Federal information systems. ***This Security framework is based on NIST SP800-53 revision 5 and the NISTIR 7621 revision 1*** published by The Information Technology Laboratory, with the purpose of serving a concise yet robust and easy to understand security model for small business who may not have the expertise or understanding to answer many of the items found in detailed checklists,
may not have a lot of time to dedicate to the process, or may not have the funding to bring in a 3rd party to conduct the audit.

___

## ***Information Security***

Organizations must exercise ***due diligence*** in managing information and privacy risk. Employing effective risk-based
processes, procedures, methods, and technologies ensures that information systems and organizations have the necessary trustworthiness to support business functions.

* Identify what information your business stores and uses
  * It is unreasonable to protect every piece of information against all threats so it is important to identify only the most valuable information
* Determine the value of your information and after identifying each information type, ask these three key questions:
  * What would happen to my business if this information was made public?
  * What would happen to my business if this information was incorrect?
  * What would happen to my business if I/my customers couldn’t access this information?

    Note that it may be easier to assign information to a scale when dealing with a large amount of information. i.e.
  * 0 to 3
  * “none,” “low,” “moderate,” and “high.”

___

# Framework for Information Security

___

### **Safeguard your information**

* Concurrent Session Control:
  A small business should take care of how many concurrent sessions its employees have access to based on the role of the employee. By closely monitoring the attempts that an employee has made in having various sessions open, a small business can use this as a detection measure to see if high levels of attempts are caused by a compromised user, this also limits the attackers window of operation as it would be easy to trigger such a detection measure.

* Remote Access:
  As more and more employers have shifted to remote work, it can be deduced that an attacker will attempt to compromise a user’s account using the employee’s personal computer, as a personal device has less security than that of an enterprise device. We can further strengthen this control by implementing enhancement 10 (Authenticate remote commands) by implementing a two-factor authentication process that requires an employee to input a pin and a token so that specific commands and logins can be verified; this provides strong protection in assuring that an employee and not an attacker is the individual that is logging in.

* Access Control for Mobile Devices:
  Personal handheld devices are the most prevalent form of communication, and if an attacker was to compromise an employee’s mobile device, the attacker would have an array of sensors and tools that could be used to spy and further advance their attempts of intrusion. Implementing policies that limits mobile device usage can further enhance the security of a small business the rationale behind such policies is due to the possibility of employees not having the lates security patches updated to their mobile devices, such lack of patches can cause an attacker to exploit the employee’s mobile device and use it to compromise any system an employee connects their device to.

* 21 Information Sharing:
  Information sharing can be an easy oversight, if an employee has the privilege to send emails with sensitive information outside of the organization, this can cause huge regulatory issues, along with providing attackers the ability to send mass amounts of information outside of the business without raising suspicion. This can further be enhanced to include the restriction of external communication, only specified users can have access to send out external emails which would require that the emails sent out along with the users account have extra scrutiny in case the account is ever compromised.

* Policy and Procedure:
  This control falls under the category of awareness and training, and the purpose of such a control is to build policies that reduce the possibility of an attacker compromising a system or network. Management can create awareness information and develop training materials that users can learn upon.

* Literacy Training and Awareness:
  The purpose of such a control is to raise employee awareness of disguised cybersecurity threats. Human error is usually the biggest weakness, and for a small business, it can be easier to assure that most if not all employees are aware of the tactics used to compromise a network. By having quarterly training sessions and knowledge checks along with mock attack, the human error can be greatly reduced.

* Identify and control who has access to your business information
  * Do not allow unauthorized persons to have access to any business hardware
  * Be aware of anyone who has access to computers
  * Physically lock up business electronics when not in use
    * Laptops
    * Mobile Phones
    * other mobile electronic devices

* Conduct Background Checks
  * Make sure the person you may employ does not have a history of
* Require individual user accounts for each employee.
  * Require strong unique passwords
  * Without individual accounts it will be harder to investigate data loss or manipulation

* Create policies and procedures for information security
  * Outline acceptable practices
  * Clearly define your expectations
  * All employees should sign a statement of agreement
  * Review policies annually and as changes to the company and technologies used occur

* Least Privilege
  * Limit employee access to data and information
  * Only allow employees to access what they need
  * Prevent non-privileged users from executing privileged functions.
  * Users should only be allowed to use privileged software based on their role in the business.
  
        By limiting the amount of privilege that a user has access to, if, theoretically, the user’s account was compromised, it would limit the number of systems that are impacted and could be used for malicious purposes. Within the least privilege control, we could also employ enhancement 3 which includes authorizing network access commands for certain operational needs while also documenting the reasoning behind such needs.

* ***Train your employees***
  * According to the cybersecurity education company, Cybint, 95% of breaches are caused by human error.
  * What Topics Should My Security Awareness Efforts Focus On?
    * **Phishing Attacks and Social Engineering**

        Phishing is a hacking practice to fool employees into turning over private data and system access credentials. Generally, phishing comes in emails modified to appear as if they came from people in the organization. 43% of cyber attacks target small business, 62% of which experienced phishing & social engineering attacks.  
      * Employees must identify false messaging and understand how to report them to IT.
      * Human intelligence and comprehension is the best defense against phishing attacks.
    * **Passwords**

        One of the weakest points of an IT system is the authentication system, mostly due to the fact that many users will disregard best practices. Training in this scenario should include creating and maintaining a strong secure password and how to use different passwords for each account the employee may posses.

    * **Remote Work Tools and Practices**

        Remote work is more common, and interactions with outside forces can threaten the security of a professional network. Employees should have information and other resources on how to manage their devices and connect to business networks.
  * Continually reinforce the training in everyday conversations or meetings

* Patch your operating systems and applications
  * Only install what is needed to run your business
  * When a new device is purchased check for updates right away
  * Assign a day to check for updates.
    * Monthly or every two weeks depending on circumstances.

* Install and activate software and hardware firewalls on all your business networks
  * Firewalls are used to block malicious communications or browsing of inappropriate websites
  * Confirm there is antivirus software installed on the firewall.
  * regularly update a software firewall on each computer system
  * Enable logging
    * Useful in investigation of an event by providing evidence

* Secure your wireless access point and networks
  * Change the administrative password that was on the device when you received it.
  * Set the wireless access point so that it does not broadcast its Service Set Identifier (SSID).
  * Set your router to use WiFi Protected Access 2 (WPA-2), with the Advanced Encryption Standard (AES) for encryption. Do not use WEP (Wired-Equivalent Privacy) as it is not considered secure.
  * **If your business provides wireless internet access to customers, ensure that it is separated
from your business network.**

* Set up web and email filters
  * Helps remove emails known to have malware attached
  * Prevents inbox from being cluttered by unsolicited and undesired emails.
    * i.e. spam
  * If available enable web filtering

* Encrypt sensitive business information

    Encryption is the process of encoding information. This process converts the original representation of the information, known as plaintext, into an alternative where only authorized parties can decipher a the encrypted plaintext back and access the original information.
  * Use full disk encryption
    * Encrypts all information on the storage media

    **Why use full disk encryption?**

      When every drive on the system has full disk encryption enabled, your security is stronger. A stolen laptop is no longer an existential security threat. The data simply won’t be accessible to the thief without another form of attack.

* Install and update anti-virus, -spyware, and other –malware programs

* Maintain and monitor logs

* Make full backups of important business data
  * Make a full, encrypted backup of the data on each device used in your system at least once a month
  * Backups will let you restore your data in case a computer breaks, an employee makes a mistake, or a malicious program infects your system.
  * Data that you should backup includes, but is not limited to, spreadsheets, databases, financial records, human resources files, customer accounts account information and system logs.

___

# Audit Checklist

___

## ***Least Privilege***

* What kind of privileges are given for each role?
* Have roles privileges been established?
* What employees currently have the most amount of access privilege?

### ***Concurrent session control***

* Is it crucial for every employee to have more than one session open?
* What is the maximum amount of session an individual employee is able to open?

### ***Remote access***

* Can work be done on site without the need for remote sessions?
* Are remote sessions based on employee job role?

### ***Access control for mobile devices***

* Is any type of device able to connect to the network?
* Has device connection type been divided so that only specific types of employees can connect with specific devices?
* How often are network passwords changed?

### ***Information Sharing***

* Are employees allowed to email external contacts?
* Will third party vendors be an exception to emailing external contacts?
* What type of information is being shared?
* Does the information being shared contain PI (Private information)?

### ***Policy and Procedure***

* What are your currently policies and procedures for any cyber related work?

### ***Literacy training and awareness***

* How often are your employees trained on cyber security threats?
* How often does testing occur?
* How knowledgeable are your employees on the different types of cyber security attacks?

## ***Protect***

* What do you currently use in the way of protection against cyber security threats?
* Is your business and customer’s private information properly encrypted?"

## ***Detect***

* What type of anti-virus protection does your business run?
* How often is your network checked for any intrusions?
* Are there logs that record any suspicious activity?

## ***Respond***

* What step by step process does your business currently have if an intrusion was to be detected?
* Who is your current point of contact when an intrusion occurs?

## ***Recover***

* What is your current state of information and systems backup?
* How often are systems backed up?
* Where are your backups stored?
* Are your backups encrypted?

___

# References

* Small Business Information Security, Paulsen and Toth. (NISTIR 7621 REV. 1)
  * <https://nvlpubs.nist.gov/nistpubs/ir/2016/NIST.IR.7621r1.pdf>
  
* Security and privacy control for information systems and organizations (NIST SP 800-53, REV. 5)
  * <https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-53r5.pdf>
  
* Reasons to require full disk encryption
  * <https://jumpcloud.com/blog/reasons-require-full-disk-encryption>
  
* SOC2 Type 1 and 2 Audits
  * <https://socreports.com/soc-2-services/soc-2-audits>
  
* 15 Alarming Cyber Security Facts and Stats
  * <https://www.cybintsolutions.com/cyber-security-facts-stats/>
  
* Employee Security Awareness Training: Why it's important
  * <https://www.cisostreet.com/employee-security-awareness-training-why-its-important/>
