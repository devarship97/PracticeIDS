# IoT Lab Capture
- Description:
- Model: Philips hue Bridge
- Duration: 

# Descripttion of Files

- .capinfos
    - Capinfos file
- .dnstop
    - DNS top file
- mitm.out
    - Mitm proxy interception file of http and https
- .mitm.weblog
    - This is the HTTP and HTTPS web log that includes Labels. This is the preferred file for web analysis.
    - This file includes a header with the columns names. There are two new columns defined by us:
        - Column id: This number is unique for all the weblogs generated __inside__ the same TCP connection. When a TCP connection is opened and several GET/POST, etc., requests are made inside it, all of them are assigned the same Id in this file.
        - Column timestamp_end: This is the timestamp when the weblog ended. If you use this with the id column you can compute the total duration of the TCP connection that generated __all__ the weblogs. Similar to the duration of a hypothetical CONNECT request if this would have been done using a proxy.
- .passivedns
    - Passive DNS file
- .pcap
    - Original pcap file
- .rrd
    - RRD file for graphs
- .weblogng
    - WEB log of http traffic only. Generated with justsniffer
- .exe.zip
    - Original malware file
- bro
    - Folder with all the bro output files
- .biargus
    - Argus binary file. Bidirectional flows, 3600s of report time.
- .binetflow
    - Argus text file with bidirectional flows. Report time 3600 secs.
- .uniargus
    - Argus binary file. Unidirectional flows, 5s of report time.
- .uninetflow
    - Argus text file with unidirectional flows. Report time 5 secs. TAB as column separator.

# IP Addresses
    - Infected device: 192.168.1.132
    - Default GW: 192.168.1.1

# Generic Dataset name: CTU-Honeypot-Capture-4
# Origin device: Philips Hue

# Timeline

## Start. 2018/10/25

## Thu Oct 25 14:16:00 CEST 2018
Capturing traffic again. The camera has new IP address

# Disclaimer 
These files were generated in the Stratosphere Laboratory as part of the Aposemat Project for collecting IoT malware captures Done in the CVUT University, Prague, Czech Republic.
The goal is to store long-lived real iot malware traffic and to generate labeled netflows files.
Any question feel free to contact us at:
Sebastian Garcia: sebastian.garcia@agents.fel.cvut.cz

You need authorization from the Stratosphere Lab to use these files.
