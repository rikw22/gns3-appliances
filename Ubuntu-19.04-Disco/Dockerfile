FROM ubuntu:disco

RUN DEBIAN_FRONTEND=noninteractive apt-get update
RUN DEBIAN_FRONTEND=noninteractive apt-get -y --no-install-recommends install net-tools tcpdump ngrep telnet traceroute curl iperf3 knot-host openssh-client mtr-tiny socat nano vim nmap iputils-ping iproute2 isc-dhcp-client
RUN rm -rf /var/lib/apt/lists/* 
