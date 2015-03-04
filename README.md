sudo python nmap2ness.py -h
usage: nmap2ness.py [-h] [-s HOSTIP] [-n SCANID] [-u USERNAME] [-p PASSWORD]
                    [-i INFILE] [-o OUTFILE]
```
optional arguments:
  -h, --help   show this help message and exit
  -s HOSTIP    [nessus server IP]
  -n SCANID    [lookup job based on scan_id]
  -u USERNAME  [username]
  -p PASSWORD  [password]
  -i INFILE    [nmap xml file]
  -o OUTFILE   [nessus report (csv)]
```  
    
sudo python nmap2ness.py -u root -p 1234 -i nmapt_target.xml -s 127.0.0.1  
```
- Launching new Nessus scan
- Extracting ports from nmapt_target.xml
- Modifying Nessus policy
- Logging into Nessus
- Uploading Policy
- Starting Nessus Scan
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : canceled

- Summary of Results (Critical/High/Medium)
Critical   176.28.50.165:80                                                PHP Unsupported Version Detection
High       176.28.50.165:80                                      PHP 5.3.x < 5.3.29 Multiple Vulnerabilities
Medium     176.28.50.165:110                                                           SSL Certificate Expiry
Medium     176.28.50.165:110                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:110                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:143                                                           SSL Certificate Expiry
Medium     176.28.50.165:143                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:143                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:25                                                           SSL Certificate Expiry
Medium     176.28.50.165:25                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:25                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:465                                                           SSL Certificate Expiry
Medium     176.28.50.165:465                                           SSL Version 2 and 3 Protocol Detection
Medium     176.28.50.165:465                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:465                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:465      SSLv3 Padding Oracle On Downgraded Legacy Encryption Vulnerability (POODLE)
Medium     176.28.50.165:993                                                           SSL Certificate Expiry
Medium     176.28.50.165:993                                           SSL Version 2 and 3 Protocol Detection
Medium     176.28.50.165:993                                                 SSL Weak Cipher Suites Supported
Medium     176.28.50.165:993                                      SSL Medium Strength Cipher Suites Supported
Medium     176.28.50.165:993                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:993                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:993      SSLv3 Padding Oracle On Downgraded Legacy Encryption Vulnerability (POODLE)
Medium     176.28.50.165:995                                                           SSL Certificate Expiry
Medium     176.28.50.165:995                                           SSL Version 2 and 3 Protocol Detection
Medium     176.28.50.165:995                                                 SSL Weak Cipher Suites Supported
Medium     176.28.50.165:995                                      SSL Medium Strength Cipher Suites Supported
Medium     176.28.50.165:995                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:995                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:995      SSLv3 Padding Oracle On Downgraded Legacy Encryption Vulnerability (POODLE)

- Nessus report has been saved to: report.csv
```
<<<<<<< HEAD
  
  
sudo python nmap2ness.py -u root -p 1234 -n 224  
```
- Logging into Nessus
=======

sudo python nmap2ness.py -u root -p 1234 -n 224
```
- Logging into Nessus
- Starting Nessus Scan
>>>>>>> 53cf76949a950ccccfbfdaebfd06ed84d71d4946
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : running
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : paused
- Checking Job Status: 224 : canceled
<<<<<<< HEAD

- Summary of Results (Critical/High/Medium)
Critical   176.28.50.165:80                                                PHP Unsupported Version Detection
High       176.28.50.165:80                                      PHP 5.3.x < 5.3.29 Multiple Vulnerabilities
Medium     176.28.50.165:110                                                           SSL Certificate Expiry
Medium     176.28.50.165:110                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:110                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:143                                                           SSL Certificate Expiry
Medium     176.28.50.165:143                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:143                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:25                                                           SSL Certificate Expiry
Medium     176.28.50.165:25                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:25                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:465                                                           SSL Certificate Expiry
Medium     176.28.50.165:465                                           SSL Version 2 and 3 Protocol Detection
Medium     176.28.50.165:465                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:465                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:465      SSLv3 Padding Oracle On Downgraded Legacy Encryption Vulnerability (POODLE)
Medium     176.28.50.165:993                                                           SSL Certificate Expiry
Medium     176.28.50.165:993                                           SSL Version 2 and 3 Protocol Detection
Medium     176.28.50.165:993                                                 SSL Weak Cipher Suites Supported
Medium     176.28.50.165:993                                      SSL Medium Strength Cipher Suites Supported
Medium     176.28.50.165:993                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:993                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:993      SSLv3 Padding Oracle On Downgraded Legacy Encryption Vulnerability (POODLE)
Medium     176.28.50.165:995                                                           SSL Certificate Expiry
Medium     176.28.50.165:995                                           SSL Version 2 and 3 Protocol Detection
Medium     176.28.50.165:995                                                 SSL Weak Cipher Suites Supported
Medium     176.28.50.165:995                                      SSL Medium Strength Cipher Suites Supported
Medium     176.28.50.165:995                                                SSL Certificate Cannot Be Trusted
Medium     176.28.50.165:995                                                      SSL Self-Signed Certificate
Medium     176.28.50.165:995      SSLv3 Padding Oracle On Downgraded Legacy Encryption Vulnerability (POODLE)

- Nessus report has been saved to: report.csv
```

=======
- Nessus report has been saved to: report.
```
>>>>>>> 53cf76949a950ccccfbfdaebfd06ed84d71d4946
