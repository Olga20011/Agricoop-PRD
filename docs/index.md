<!-- # Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files. -->
# AGRICOOP 

##Objectives/goals of agricoop project

Agricoop is a group that aims to ensure Rwandan farmers who deal with the plantation of beans get paid on time by the cooperatives. Our solution is to create a web platform that will help cooperatives keep records and make payments since after conducting our research we realized that payments get delayed due to a lack of digitized systems that help them process details in a faster way.

**What problems this product solves**.

Since there are no digital systems that promote a faster way of processing information, the project is dedicated to helping cooperatives process details of different groups of farmers who grow beans. The product will enable the cooperatives to make payments in time which will enable farmers to benefit from their farm produce.

**Who will use the product?**

The product will be used by the cooperatives in Rwanda that have registered to use the product and are dealing with buying and selling different beans from farmers.

**Why is it important?**

A big percentage of farmers in Rwanda do not get to benefit from their hard work since they do not have access to their money at the exact time that they want it. Agricoop will help farmers get their money in time and since there will be no delay in the process of taking in their products and getting paid since it will be done digitally compared to how it was being done manually hence take a lot of time.

## Features of the product

**Making payments**

The most important feature is the payments feature. It is enabled by some prior like taking off the group leader and farmer’s details. The payment system in use is the mtn mobile money which involves the use of API like the debit API which is responsible for sending money to the individual contact.
 
**Group List**

Another important feature of the platform is the group list. It enables the cooperative to view the list of groups that have been registered and also has the functionality of adding a new group. The cooperative is able to view the group because their information is stored in the database. Under group name, the drop-down seen displays the date of delivery, the quantity delivered and the variety of beans delivered.
 
**The Beans page**

This section is only viewed by the admin. It enables the tracking of deliveries in terms of variety, the total quantity purchased, the total amount paid for the beans.
 
**User role management**

Another critical feature of a professional dashboard application is the opportunity to assign different user roles and adjust various forms of access and data exploration. There are 4 main pillars you should look for: admin, viewer, power viewer, and user. Each of these roles has different workflow possibilities that make the analysis even easier:
Admin: As in many other software and tools, the admin is the highest level of administration capability where s/he has the ultimate power to add other users, restrict data access or adjust the account in any way that s/he sees fit, e.g. assign filters for dashboard viewers, or add, delete and edit data sources and dashboards.

Editor: The editor is one level lower than the admin; the difference is that s/he cannot delete data sources, but has access to dashboards, which s/he can edit or assign viewers’ access.

Power viewer: This type of a viewer has access to a chart library that the admin assigned and s/he can edit the charts’ appearances, but can’t create a new chart on his/her own. The power viewer cannot manage the data source but can add other viewers, e.g. in bulk, if you have multiple sales managers or departments and bigger teams.

## Development requirements

**Languages**

* Python
* HTML/CSS
* Bootstrap
 
**Framework**

**Django**

 It can work with any client-side framework and can deliver content in almost any format (HTML, JSON, XML, etc) Django provides a secure way to manage user accounts and passwords, donor information is really sensitive and needs to be secure from unauthorized users.

**Heroku**

Heroku is a platform as a service (Paas) that enables developers to build, run and operate applications entirely in the cloud. Heroku offers a free plan to experiment and find out what works best for you. Heroku supports the Python programming language.
 
**PostgreSQL database**

Postgres is a free and open-source database management system that is extensible and SQL compliant Postgresql source code is freely available under an open-source license Postgres has a filter clause that can be used to aggregate data based on certain criteria.
 USER FLOW AND DESIGN NOTES

## Flow Outline

Entry  point
The user will have to search for the platform on google and download it on their system to be able to use it.

**Steps to completion**

The cooperative will have to signUp into the platform in case he/she is a new user by entering the user name, email, and password to access the platform and for a who is already a member will have to login by just entering the email and password to continue accessing the platform. After entering all that information to access the platform, they will go to the home page.

**The final Interaction**

The cooperative will have access to the group where he/she can see the groups of farmers available in the list, and add the group of new farmers by registering their group names, members in the group, group leader, and the number of the group leader. The cooperative will also be able to see the available types of beans and their prices per kg to help guide them on the products they’re collecting, they will also be able to add the new categories of beans that have entered the market.
They will be able to record data of the beans brought by each group and send a notification to the group leader of the kgs of beans brought and the amount then make payment either in bulk by paying the groups at once or paying the group individually and finalizing everything.

![alt text for screen readers](/images/userflow.png "Text to show on mouseover").


## System and environmental requirements

This is a general term used to describe which end-user environment will be supported. Such as browsers, operating systems, memory, and processing power, etc. 
The system environment requirements for using agricoop are as follows:

**Hardware**

* Smartphone
* Computer

**Software**

* Web browser
* Operating system 

The operating system is the software that controls all the resources of a computer system. For example it:

* Assigns the needed hardware to programs
* Schedules programs for execution on the processor
* Allocates the memory required for each program
* Assigns the necessary input and output devices
* Manages the data and program files stored in secondary storage
* Maintains file directories and provides access to the data in the files
* Interacts with the users

|  **Item**  |   **Specification**|
| --------   |  :-------------:| 
|Operating system|Windows XP Home Edition (SP1 or later)*1, Windows XP Professional (SP1 or later) *1, Windows Server 2003 Standard Edition (SP1 or later)Windows Server 2003 Enterprise Edition (SP1 or later), Windows Server 2003 R2 Standard Edition, Windows Server 2003 R2 Enterprise Edition, Windows XP Professional 64 Edition|   
| **CPU** |   Any processor of the same or higher specifications as recommended for your operating system,1.3 GHz or higher |       
| **Web Browser**         |   In order to authenticate the license for Desktop as well as to read HTML-format manuals, one of the following Web browsers needs to be installed on the system.Microsoft Internet Explorer Version 6.0/7.0/8.0/9.0/10.0/11.0 |  
|   **Memory**       |Memory capacity as recommended for your operating system The memory space must be enough for the OS and applications used.2 GB or higher| 






##Assumptions, Constraints, and Dependencies

**Assumptions**

* Project member’s availability
* Project member’s performance
* Project member’s skills
* Procurements
* Delivery times
* Performance issues

**Constraints**

**Results**: The final product will be a web platform that will help the cooperatives be able to keep records of the groups of farmers who deal with the plantation of beans and make fast payments.
Time frame: The requirement is that the project should be completed before November 12th.

**Resources**:  As a group, we will require tools such as Github which will enable us to merge our code, and Zenhub which will guide us to allocate tasks to different individuals.

**Activity performance**: we'll be working in a group of 5 people and each individual will have tasks to work on. This will enable us to finish the task on time and the final product will be more effective.

**Dependencies**
The first task must be completed before the second task can start.
The second task cannot be finished before the first task is completely done.
The second task doesn't start until the first task is started and completed.
The first task must start before the second task is done.


