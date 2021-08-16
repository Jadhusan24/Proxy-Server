# Proxy-Server
  Proxy Server Using Squid Service and E2 Guardian Package with MySar Report.
  A proxy server acts as a gateway between you and the internet. It is an intermediary server separating end users from the websites they browse.

[![LinkedIN](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jadhusan24/)

## _Notes_

### First, we must install SQUID SERVICE. <br/>

    Because We cannot configure the Packages without squid services. 
    For Proxy Packages
        - We can Use Packages like - e2 guardian or dans guardian.
        - e2 guardian only in Debian Version (UBUNTU) not in RPM.
    E2 GUARDIAN and DANSGUARDIAN USED FOR WEB CONTENT FILTERING
        - Filtering based on filetypes, download bandwidth, search patterns and much more.

#### **Squid Services** Used For Web Page Filtering. <br/>

    Using ACL, we can restrict and allow based on source, dst, domain and much more.

#### **Mysar** / **Sarg** Used For Report Services. <br/>

    IP based and USER based.

#### To Verify

    Debian Base OS 
    apt-cache search squid 
    apt-cache search E2Guardian 
    
    Centos
    squid rpm -qi squid 
    squid rpm -qi E2Guardian 

#### Configuring On

    Ubuntu Version 20.10 Running in Virtual Machine Workstation 16 Pro. <br/>
    Network Bridged from Host pc to Ubuntu VM.

## _THEROY_
 - [E2Guardian-Package](./document/E2Guardian-Package.pdf)
 - [Squid-Service](./document/Squid-Service.pdf)


 - [WinVer](./1.jpg)


