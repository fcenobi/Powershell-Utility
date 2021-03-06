##Description :

This module contains 1 cmdlet : **New-ReadmeFromHelp**.  
It requires PowerShell version 3 (or later).

##New-ReadmeFromHelp :


Generates a README.md file from the help contained in the specified Powershell module file.
The generated README.md file's purpose is to serve as a brief documentation for the module on 
GitHub.  
This README file is created in the same directory as the module file.  
It uses GitHub Flavored Markdown, so the GitHub website will format it nicely.

This works with any PowerShell module (script or compiled) and any help (comment-based or 
XML-based) as long as it is accessible via Get-Help.

###Parameters :

**ModuleFile :** To specify the path to the module file you wish to create a README file for.  

###Examples :

-------------------------- EXAMPLE 1 --------------------------

C:\PS>New-ReadmeFromHelp -ModuleFile ".\Example.psm1"


Creates a README file for the script module Example.psm1, in the same directory.










