>_Forked from https://github.com/mikebanks/AbuseIPdbSCAN_

# AbuseIP DB Scanner

This is a python script that will parse IP addresses from files and interact with AbuseIPDB API. It will return the information about the IP into standard out in tab separated values in standard out.

## Requirements (Setup)


- Python3 (2.7 may have errors)
- Requests
```
pip3 install Requests
```
- Requests[security]
```
pip3 install requests[security]
```
- AbuseIP DB API Key
In order to use the script you will need an API key and place it in the scrip under the "api_key" variable. API key information can be found here: (https://www.abuseipdb.com/api.html)

## Usage

```
python3 AbuseIPDB.py -f file_to_parse.txt
```

 The options are as follows:

```
-t      outputs items in tab seperated values (Default)

-c      outputs items in comma seperated values
```

## Troubleshooting

- If you are receiving errors, please look at the Issues queue and see if there is already an issue open.

- If you have a unique issue, please create a new Issue, and include the output of your terminal from the bootstrap script down until the error.

## Backlog

- Parse for IPs recursively through directories
- Create an option to output data in JSON
- Create an option to output data to a file

## Completed (After Launch)

- ~~Create an option to output data in TSV or CSV~~
