# JSS-API-Instance-Replicator

### Introduction

This allows you to clone the API-capable properties of a JSS instance to another instance.  

### Attribution

This is a development of [JSS-Config-In-A-Box](https://github.com/franton/JSS-Config-In-A-Box)
by Richard Purves.

In turn, Richard's script is a development of Jeffrey Compton's
[JSS Migration Utility](https://github.com/igeekjsc/JSSAPIScripts/blob/master/jssMigrationUtility.bash):


### Getting started

The source and destination instances both require a valid API user.  
The source API user can be an auditor (or custom read-only permissions).  
The destination API user requires write access to each parameter that is wished to be copied.

Once you have those in place:

1. Run the script (root not required).
2. Follow the prompts.  
   You will be asked for a location to store xml data from the JSS API.  
   If data already exists, then you'll be asked if you wish to archive it. Otherwise the folders will be created.

3. You have two choices. Download or Upload.  
   Selecting either will prompt for server details and credentials.

### TO DO

* Automation capabilities using command-line flags.
