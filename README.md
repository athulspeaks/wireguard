# WireGuard | Personal use only .

WireGuard is a communication protocol and free and open-source software that implements encrypted virtual private networks, and was designed with the goals of ease of use, high speed performance, and low attack surface . 

Supported distributions :

- Ubuntu >= 16.04
- Debian >= 10
- Fedora
- CentOS
- Arch Linux
- Oracle Linux

## Usage

Download and execute the script. Answer the questions asked by the script and it will take care of the rest .

```bash
curl -O https://wireguard.athuljith.com/wireguard.sh
chmod +x wireguard.sh
./wireguard.sh
```

It will install WireGuard (kernel module and tools) on the server, configure it, create a systemd service and a client configuration file .

Run the script again to add or remove clients !
