# Get-NewPublicFolders.ps1
Get all public folders created during the las X days

## Description
This script gathers all public folders created during the last X days and exportes the gathered data to a CSV file.

## Parameters
### Days
Number of last X days to filter newly created public folders. Default: 14 

### Legacy
Switch to define that you want to query legacy public folders

### ServerName
Name of Exchange server hostingl egacy public folders 

## Examples
```
.\Get-NewPublicFolders.ps1 -Days 31 -ServerName MYPFSERVER01 -Legacy
```
Query legacy public folder server MYPFSERVER01 for all public folders created during the last 31 days

```
.\Get-NewPublicFolders.ps1 -Days 31 
```
Query modern public folders for all public folders created during the last 31 days

## Note
THIS CODE IS MADE AVAILABLE AS IS, WITHOUT WARRANTY OF ANY KIND. THE ENTIRE  
RISK OF THE USE OR THE RESULTS FROM THE USE OF THIS CODE REMAINS WITH THE USER.

## TechNet Gallery
Find the script at TechNet Gallery
* https://gallery.technet.microsoft.com/Fetch-recently-created-635a7d98


## Credits
Written by: Thomas Stensitzki

Stay connected:

* My Blog: http://justcantgetenough.granikos.eu
* Twitter: https://twitter.com/stensitzki
* LinkedIn:	http://de.linkedin.com/in/thomasstensitzki
* Github: https://github.com/Apoc70

For more Office 365, Cloud Security and Exchange Server stuff checkout services provided by Granikos

* Blog: http://blog.granikos.eu/
* Website: https://www.granikos.eu/en/
* Twitter: https://twitter.com/granikos_de