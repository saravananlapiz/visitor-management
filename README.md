# visitor-management
Visitor Management System

# Running on Local Server
Make sure you have xampp 7.1.4+ installed.  

### Instructions for xampp (Apache):  
Clone the repository in your htdocs folder -
```bash
git clone https://github.com/nikramakrishnan/visitor-management.git
```
**OR**  
if you have already cloned the repository, run -
```bash
git pull
```

Switch to the `skeleton` branch -
```bash
git checkout skeleton
```

Now, start Apache and MySQL, and create a database named `vms`, if not already exists.  

Now import the `vms.sql` file in the database to create the required table(s).  

The default credentials are -  
**Username**: admin  
**Password**: password

# Contributing
Please note that all code must be readable and comments should be used wherever required.  
Database and table names must be generic easy to understand.

# Completion
This branch will be merged with `master` when the basic functionality (login + visitor add)
is completed and tested.
