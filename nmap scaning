#Nmap Scanning Techniques
#The script offers nmap scan techniques also as python function/methods

#Nmap_fin_scan
    import nmap3
    nmap = nmap3.NmapScanTechniques()
    result = nmap.nmap_fin_scan("192.168.178.1")
    
#Nmap_idle_scan
   import nmap3
   nmap = nmap3.NmapScanTechniques()
   result = nmap.nmap_idle_scan("192.168.178.1")
   
#Nmap_ping_scan
   import nmap3
   nmap = nmap3.NmapScanTechniques()
   result = nmap.nmap_ping_scan("192.168.178.1")
   
#nmap_syn_scan
   import nmap3
   nmap = nmap3.NmapScanTechniques()
   result = nmap.nmap_syn_scan("192.168.178.1")
   
#Nmap_tcp_scan
   import nmap3
   nmap = nmap3.NmapScanTechniques()
   result = nmap.nmap_tcp_scan("192.168.178.1")
   
#Nmap_udp_scan
   import nmap3
   nmap = nmap3.NmapScanTechniques()
   result = nmap.nmap_udp_scan("192.168.178.1")
   
#Supporting the nmap host discovery
#Only port scan (-Pn): def nmap_no_portscan(self, host, args=None):
   import nmap3
   nmap = nmap3.NmapHostDiscovery()
   results = nmap.nmap_portscan_only("your-host")

#Only host discover (-sn) : def nmap_portscan_only(self, host, args=None)
   import nmap3
   nmap = nmap3.NmapHostDiscovery()
   results = nmap.nmap_portscan_only("your-host")
   
#Arp discovery on a local network (-PR) : def nmap_arp_discovery(self, host, args=None):
  import nmap3
  nmap = nmap3.NmapHostDiscovery()
  results = nmap.nmap_arp_discovery("your-host")
  
#Disable DNS resolution (-n): def nmap_disable_dns(self, host, args=None):
  import nmap3
  nmap = nmap3.NmapHostDiscovery()
  results = nmap.nmap_disable_dns("your-host")
  
#for more customisation: 
#scan top ports and perform version detection: 
   import nmap3
   nmap = nmap3.Nmap()
   results = nmap.scan_top_ports("host", args="-sV")

#Using the nmap vulners script to identify vulnerabilities (CVE's)
   import nmap3
   nmap = nmap3.Nmap()
   ressults = nmap_version_detection("host", args="--script vulners --script-args mincvss+5.0")
