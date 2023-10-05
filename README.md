# Local-Enumeration
This toolkit was conceived to perform tasks of Local Enumeration. Local Enumeration consisting of analysing a target host for different information that can be used a potential exploitable vulnerability.
## Features/ Usage
This program allows the user to gather information from a variety of options such as: 
1.	A general system information like the current user, host name, IP address
2.	A socket port scanner which allows the user to type in the IP address of the target host for a connection. Once the range of ports that the user wants to scan is inserted, each port will be tried for a connection of 0.5 seconds. If the port is opened, the latter will be printed out on the screen.
3.	A Domain functionality where the user is able to retrieve the IP address related to the domain entered by the user.
## Installation
```
import socket
```
```
import ipaddress
```
```
import re
```
```
import getpass
```
## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
None
