# DNSrank

A Domain Name System server benchmarking/ranking script
![Preview](./preview/DNSrank-screen1.jpg)

# Requirements

The script needs the following commands to be available: bc, dig, traceroute, ping, curl and getent and will notify in case any are missing. All these commands should be available by default on most distros.<br/>
If you are intercepting DNS requests on your gateway, make sure to add an exception to the IP you are testing from.

# How to use

1. Run the following code to clone this repo and make the script executable.

`git clone https://github.com/Deepcuts/DNSrank && cd ./DNSrank && chmod u+x run-DNSrank`

2. Edit the file run-DNSrank to set up some parameters. Defaults should work out of the box.
3. Edit the file servers.txt to add or remove DNS servers. Some servers are already setup.
4. Edit the file domains.txt to add or remove test domains. Some domains are already setup.
5. Execute `./run-DNSrank` to start testing.
