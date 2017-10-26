ja3.py is a python tool for generating JA3 fingerprints from pcaps.

## Installation
```
$ pip install dpkt
```
Ensure dpkt is >= v1.9.0

## Usage
```
$ python ja3.py [pcap]
```

## Example
```
$ python ja3.py example.pcap  
{"src_port": 61644, "timestamp": "2017-07-30 17:59:31.577926", "ja3": "4923a265be4d81c68ecda45bb89cdf6a", "src_ip": "172.19.63.193", "dest_ip": "172.22.188.54", "dest_port": 993}
{"src_port": 61644, "timestamp": "2017-07-30 17:59:31.577927", "ja3": "4923a265be4d81c68ecda45bb89cdf6a", "src_ip": "172.19.63.193", "dest_ip": "172.23.1.52", "dest_port": 993}
```

___  
### Python Script Written by
[Tommy Stallings](mailto:tommy.stallings@salesforce.com)

### JA3 Created by

[John B. Althouse](mailto:jalthouse@salesforce.com)  
[Jeff Atkinson](mailto:jatkinson@salesforce.com)  
[Josh Atkins](mailto:j.atkins@salesforce.com)  

Please send questions and comments to **[John B. Althouse](mailto:jalthouse@salesforce.com)**.
