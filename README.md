# Host a WCF Service Instation

# Install and run the service

1 - Build the solution to create the Service.exe executable. \n
2- Open the Visual Studio  command prompt as administrator and navigate to the project directory.\n
3- In Bin/Debug Folder Type installutil WCF_Installation_Sample.exe at the command prompt to install the Windows service.\n
4- If you make changes to the service, you must first stop it and uninstall it. \n
To stop the service, right-click the service in the SCM and select "Stop",\n
or type net stop WCF_Installation_Sample at the command prompt.\n
Note that if you stop the Windows service and then run a client,\n
an EndpointNotFoundException exception occurs when a client attempts to access the service. To uninstall the Windows service\n
type installutil /u bin\service.exe at the command prompt.\n



