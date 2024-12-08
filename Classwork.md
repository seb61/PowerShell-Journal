### Classwork 1:
This classwork served as an introduction to PowerShell. We configured the console by changing settings like font, colors, and window size, as well as configuring PowerShell to always run with elevated privileges. Basic PowerShell cmdlets were also used, such as Write-Host and Get-Service.
PowerShell cmdlets used: ``Write-Host``, ``Get-Service``, ``Where-Object``, ``Get-History``, ``Invoke-History``
### Classwork 2
In this classwork, I used the `Get-Help` cmdlet to explore various PowerShell commands, providing screenshots of the results and explaining what each command does. I used commands related to system processes, services, logs, and network adapters. 
PowerShell cmdlets used: ``Get-Help``, ``Set-ExecutionPolicy``, ``Export-CSV``, ``Select-Object``, ``Get-Process``, ``Stop-Process``, ``Get-Service``, ``Get-WMIObject``, ``Get-EventLog``, ``Get-Content``, ``Get-NetAdapter``
### Classwork 3
In this classwork, I worked with various PowerShell commands using pipelines to pass data between commands and manipulate files in different formats. I created CSV files and learned about how different commands handled data input and output, and examined how to produce HTML files using PowerShell. Additionally, I learned how to manage processes and service.
PowerShell cmdlets used:  ``Import-CSV``, ``Export-CSV``, ``Get-Content``, ``ConvertTo-HTML``, ``Out-File``, ``Get-Process``, ``Stop-Process``, ``Get-Service``, ``Export-CliXML``, ``ConvertTo-CSV`` 
### Classwork 4
In this classwork, I analyzed various PowerShell commands and evaluated whether they would work to retrieve services, processes, WMI data, and event logs from multiple computers in the domain. I considered the type of data sources (such as CSV and text files) and how commands like `Get-ADComputer`, `Get-Service`, and `Get-WmiObject` interact with them. 
PowerShell cmdlets used: ``Get-ADComputer``, ``Get-Service``, ``Select-Object``, ``Get-WmiObject``, ``Get-Process``, ``Get-EventLog``, ``Import-CSV``, ``Get-Content``
### Classwork 5
In this classwork, I enabled remoting on virtual machines, created remote sessions using `New-PSSession`, and sent commands to remote computers with `Invoke-Command`. I also worked with importing modules from remote sessions to interact with remote systems, as well as managing sessions using `Get-PSSession` and `Remove-PSSession`. Additionally, I explored common issues that arise during remote operations and how to address them.
PowerShell cmdlets used: ``Invoke-Command``, ``Enter-PSSession``, ``New-PSSession``, ``Import-Module``, ``Enable-PSRemoting``, ``Get-Module``, ``Get-PSSession``, ``Remove-PSSession``
### Classwork 6
In this classwork, I used CIM/WMI cmdlets to retrieve available classes, methods for network adapters, and details about DHCP services. The tasks helped me become more familiar with querying network information using WMI and CIM.
PowerShell cmdlets used: ``Get-CimClass``, ``Get-CimInstance``, ``Get-CimMethod``, ``Get-WmiObject``
### Classwork 7
In this classwork, I learned to work with PowerShell variables. I also wrote a custom profile script to set aliases and commands to execute at startup. I also practiced variable manipulation, including creating, modifying, and removing variables, as well as using PowerShell's built-in string formatter. Additionally, I explored handling running processes, modifying strings, and using the `-replace` operator.
PowerShell cmdlets used: ``New-Item``, ``Notepad``, ``Set-Location``, ``Clear-Host``, ``New-Alias``, ``New-Variable``, ``Get-Service``, ``Get-Process``
### Classwork 8
In this classwork, I created a PowerShell script to record and display bowling scores. The script prompted the user to input scores for 9 frames, validated the input, and stored the valid scores in an array. Finally, it displayed the scores with headings and saved them to a text file.
PowerShell cmdlets used: ``Read-Host``, ``ForEach-Object``, ``Out-File``
### Classwork 9
In this classwork, I created a PowerShell script that displayed all currently running services. I then attached the script to a scheduled task that ran automatically when the user logged in. This task was created and registered using PowerShell and I was able to verify that it worked through Task Manager. 
PowerShell cmdlets used: ``Get-Service``, ``New-ScheduledTaskTrigger``, ``Register-ScheduledTask``
### Classwork 10
In this classwork, I set up a shared folder system between two servers using PowerShell
PowerShell cmdlets used: ``New-SMBShare``

Summarize the following classwork in no more than 3 sentences. This is a reflection, so write the sentences in the past tense and in first-person. Also outline all powershell cmdlets used, without describing what they do, and list them like "PowerShell cmdlets used: ``Get-Help``, ``Set-ExecutionPolicy``, etc"