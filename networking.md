# Commands for network-related tasks

## arp-scan
I was working on my Raspberry Pi when I found this command. I needed to know what IP my Pi had.

```bash
arp-scan --interface enp3s0 --localnet
```

*enp3s0* is the name of my local network interface. Check [here](##ip-link) to find out which one is yours.

## ip

### ip-link
Display all network interfaces in your system. Use `-o` option to display information in one line.

```bash
ip -o link
```
