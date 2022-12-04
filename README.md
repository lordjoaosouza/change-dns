# change-dns

Changes your Linux DNS server

## How it works

This script will change your DNS server in `/etc/resolv.conf` to the one you specify and set the file to be imuatable using `chttr`

## How to use

- Give the script executable permissions: `chmod +x change-dns`
- Run the script: `sudo ./change-dns`

## Pi-hole support

To add your Pi-hole to the list of DNS servers, edit in line 23 `(pihole_server)` to the IP address of your Pi-hole
