# Proxy-Server
Proxy Server Using Squid Service and E2 Guardian Package with MySar Report

## Notes

A proxy server acts as a gateway between you and the internet. It is an intermediary server separating
end users from the websites they browse.
First, we must install SQUID SERVICE
  ➢ Because We cannot configure the Packages without squid services.
For Proxy Packages
  ➢ We can Use Packages like - e2 guardian or dans guardian.
  ➢ e2 guardian only in Debian Version (UBUNTU) not in RPM.
E2 GUARDIAN and DANSGUARDIAN USED FOR WEB CONTENT FILTERING
  ➢ Filtering based on filetypes, download bandwidth, search patterns and much
more.
SQUID SERVICES USED FOR WEB PAGE FILTERING
  ➢ Using ACL, we can restrict and allow based on source, dst, domain and much
more.
MYSAR / SARG USED FOR REPORT SERVICES
  ➢ IP based and USER based.
To Verify
Debian Base OS Centos
----------------------- -----------------------
 apt-cache search squid rpm -qi squid
Configuring On
Ubuntu Version 20.10 in Virtual Machine Workstation 16 Pro.
Network Bridged from Host pc to Ubuntu VM.
