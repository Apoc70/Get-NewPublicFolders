# Get-NewPublicFolders.ps1

Get all public folders created during the last X days

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

``` PowerShell
.\Get-NewPublicFolders.ps1 -Days 31 -ServerName MYPFSERVER01 -Legacy
```

Query legacy public folder server MYPFSERVER01 for all public folders created during the last 31 days

``` PowerShell
.\Get-NewPublicFolders.ps1 -Days 31
```

Query modern public folders for all public folders created during the last 31 days

## Note

THIS CODE IS MADE AVAILABLE AS IS, WITHOUT WARRANTY OF ANY KIND. THE ENTIRE
RISK OF THE USE OR THE RESULTS FROM THE USE OF THIS CODE REMAINS WITH THE USER.

## Credits

Written by: Thomas Stensitzki

## Stay connected

- My Blog: [http://justcantgetenough.granikos.eu](http://justcantgetenough.granikos.eu)
- Twitter: [https://twitter.com/stensitzki](https://twitter.com/stensitzki)
- LinkedIn: [http://de.linkedin.com/in/thomasstensitzki](http://de.linkedin.com/in/thomasstensitzki)
- Github: [https://github.com/Apoc70](https://github.com/Apoc70)
- MVP Blog: [https://blogs.msmvps.com/thomastechtalk/](https://blogs.msmvps.com/thomastechtalk/)
- Tech Talk YouTube Channel (DE): [http://techtalk.granikos.eu](http://techtalk.granikos.eu)

For more Office 365, Cloud Security, and Exchange Server stuff checkout services provided by Granikos

- Blog: [http://blog.granikos.eu](http://blog.granikos.eu)
- Website: [https://www.granikos.eu/en/](https://www.granikos.eu/en/)
- Twitter: [https://twitter.com/granikos_de](https://twitter.com/granikos_de)