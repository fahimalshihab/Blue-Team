From csv file collect all the unique ip 

```cat InteractiveSignIns_Domain_spray_logs.csv | cut -d "," -f20 | sort | uniq -c```

```     12 "137.184.112.155"
    211 "20.25.46.88"
    121 "4.227.136.189"
      3 "66.115.255.162"
      1 "IP address"```
