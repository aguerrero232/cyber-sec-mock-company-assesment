# Notes for Overview of NARO, Inc

## Staff

* 20 full time members
  * in cubicles

* CEO
  * has own office
* Manager
  * has own office
* 3 Accounting Team Members
  * shared large office

* 1 receptionist
  * reception desk
    * occupies desk 9am - 5pm

## Facility

### Access And Hours

    unlocked from 6:00am to 10:00pm

* access can also be gained by using a proximity card (proxy card) that all building tenants have
  * to access NARO office space proxy card is always required.

* Receptionist can hit an unlock button to unlock the door to the NARO office
  * door is held by magnetic lock

* To exit, there is a motion sensor which will unlock the doors when someone is leaving.

* kitchen storage and restrooms are located in common areas on office floor, NOT IN OFFICE

### Location

* 13th Floor of high-rise building downtown San Antonio, TX
  * corner of the floor they are on

* Neighbors
  * large real estate development firm,
    * takes up over half the floor
  * oil and gas services firm
  * empty space
    * ***was formerly leased to an investment firm that had several of their executives charged with fraud***
  
### Additional Spaces

* 2 small conference rooms
  * how are these accessed?

#### Computer Closet

* ***small*** “computer closet”
* contents:
  * company’s three servers
  * router provided by isp
  * Ubiquiti Unifi U6LR WAP
  * Netgear 8-port switch
    * connects the servers
    * connects WAP to router

___

## Company Technology

### Workstations

    each employee has their own workstation

* Windows OS
  * what version of windows though?
  * are they updating?

* additional software is installed based on the specific need of the employee

* Connected to the internet using via wireless network (Wi-Fi) distributed by NARO
  * is this the only method of connecting to the company’s network?

### Laptops

* total of ***4 laptops***
  * can be taken home temporarily
    * are they being used properly?
    * are the employees securing them when they are not in use?

* employee's are required to install software prior to taking them home
  * ex.) accountant installed quickbooks software and copied over all of their data before taking them home
    * how is the copied data stored, and handled?
      * read only? or is the data read and write?
      * can they copy data over from the work laptop?

### Printers

* Two HP printers
  * connected to the internet via wireless network (Wi-Fi) distributed by NARO
    * are they on the public or private network?

### Servers

    3 Servers in computer closet

* 2 of the 3 are running Windows Server 2019
  * 1 is a Windows domain COntroller, Data Base Server, and everything else needed for the Windows network
  * the other is a server that runs applications necessary to connect to various partners.
    * applications to book trucks directly from source
    * file leases with government organizations
    * etc.
* 1 is Windows Server 2016, used for files
  * file server software does not work on Windows Server 2019
  * location for employees to store files
  * location for archived files
    * some files need to be stored for an extended period of time
    * is there rendundant storage?
    * are there backups?

___

## Company Network

### Remote Access

* NARO network is accessible over vpn if paired with usage of company laptops
* Remote Access to the company network is available through installed software and providing the necessary credentials
  * NARO username and password

* Employees are also able to access their email, calendar, and Office 365 account through their smart devices using the proprietary Office365 application
  * ***Is the office 365 application secure, and what credentials are necessary to access it?***

### Wireless Network

* split into two parts
  * NARO Business network
    * protected by the password: “N4RObus1ne$$N3t”
    * uses WPA2 for encryption.
  * NARO Public network (guest network)
    * does not require a password

### IT Support

    Company is not large enough for dedicated IT specialists

* contracts IT support
  * contracted from local service provider of all IT needs
  * consultant stops by every 2 months to update systems and software that require it
    * is this a best practice?
  * consultant will stop by incase of specific faults in hardware or software
