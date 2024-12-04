# posh-gofile
A PowerShell function to download a single file from gofile.io.
Downloading folders and password protected files is not supported.

## Function usage example
```powershell
Invoke-GoFileDownload -URL 'https://gofile.io/d/aBc123' -LiteralPath 'C:\Download\MyFile.txt'
```

## Dependencies and requirements
Function was tested using PowerShell 7.4 only. It may not work correctly with older versions.
