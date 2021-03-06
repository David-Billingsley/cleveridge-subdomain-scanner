![Cleveridge logo](https://cleveridge.org/images/logo.jpg)

Cleveridge Subdomain Scanner
======================
####IMPORTANT:
>This tool is for ethical testing purpose only.   
>Cleveridge and its owners can't be held responsible for misuse by users.   
>Users have to act as permitted by local law rules.

##What is the Cleveridge Subdomain Scanner ?
The Cleveridge Subdomain Scanner finds subdomains of a given domain and shows the list on screen and records all results in easy accessible log-files.

On the first run the tool creates a directory '/log' to store all results in.

##What are the requirements ?
This tool is tested in a Linux environment with Python 2.7 installed

##How does it work ?
In Linux, download the files in to the directory of your choice. BE sure the cl_subd_scan.py file is executeble (chmod 0766) and the other files are readable.
In Terminal go to directory your files are listed in and run the cl_subd_scan.py file.
The program will ask the target domain name (eg. google.com) and it will ask which subdomain list you want to use. The has 5 lists XS, S, M, L, XL. This are list from 500 up to +114.000 different subdomains.

##Warning
When you are using the XL list of +114.000 subdomains, the scan takes a while. For slow domains or when you are working over a VPN it can take more then 1 hour for each domain.    
The XS and S-list are much faster. This XS-list contains the most common subdomains but of course the list is not as complete as the full 'XL'-list. This means you can miss some, not so common, subdomains.


##Contact Info 
**Cleveridge** - Ethical Hacking Lab   
De Brulen 28   
2370 Arendonk   
Belgium   
https://cleveridge.org

##Developer
- **Erwin De Laat** [ redN00ws ]     
https://twitter.com/erwindelaat    
- Credits to TheRook for the initial files of Subbrute V1.0    
https://github.com/TheRook/subbrute
