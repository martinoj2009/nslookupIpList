# nslookupIpList
This is a Python3 script that will nslookup a list of IP addresses in a file provided

example: ./lookup ips.txt

This will then go through your list of IP's, ignoring blank lines, and save to output.txt in the following format:
IP ADDRESS = DNS NAME

If name can't be found it will place NOT FOUND as the DNS NAME.

You can change the list of DNS servers, it checks against 3 if the name isn't found, in the script.

REMINDER:
Add the ability to pass in up to 3 DNS servers to check against.
