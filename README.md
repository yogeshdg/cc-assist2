cc-assist

cc-assist is a command line tool to perform data collection from the postgres tables as well as fetch relavent service logs.This tool has mainly been written to aid in quick log collection for issues related to sda provisioning failures.

The tool mainly does read only operations apart from the pool release functionality that will remove data from the database.This feature has been coded in a very safe way and its a safe operation as well but should be used under BU guidance.This is why it's password protected.

For Escalation/TAC teams: This will help to collect logs faster.There is no need to search for commands to collect the logs and the tables.

#Usage Example:

This tool needs to be downloaded onto Catalyst Center.
Easiest way is to use clone the repo

https_proxy=http://<>:80 git clone https://github.com/yogeshdg/cc-assist2

$ ./cc-assist2

*****************************************************************************
*****************************************************************************
*****                                                                   *****
*****                            CC-Assist                              *****
*****                         Version 2.0.0                            *****
*****                                                                   *****
*****************************************************************************
*****************************************************************************

             Main Menu:
                     1 -> Log Collection 
                     2 -> Utilities 
                     3 -> Exit 

    Select an Option : 

