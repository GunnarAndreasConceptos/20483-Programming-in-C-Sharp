# MS20483 Programming in C-Sharp
This is lab material for the official course from Microsoft Learning. The fork is an adaptation so it runs out of the box on Visual Studio 2017 Community Edition without having sql server express on the machine. 

## Changes
* Change connection string data source in all `App.Config` files from `.\sqlexpress` to `(localdb)\MSSQLLocalDB`
* Remove paths from CREATE DATABASE in setup
* Deleted all the db setup cmd files

## Setting up the databases
Throughout the labs, you are instructed to run CMD files which use sqlcmd.exe to execute an sql file. Instead of running the CMD file (which won't work unless you have sqlcmd on the PATH), open the sql file in VS2017 and execute it.