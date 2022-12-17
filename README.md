# smsc95xx-esbpf
Raspberry PI 3 ethernet driver with esBPF framework.

# How to
Use [filter_icmp](https://github.com/memnoth/esbpf/blob/master/tools/filter_icmp.c) to test blocking incoming ICMP packets,
```sh
$ filter_icmp /proc/smsc95xx/esbpf/rx_hooks
$ echo 1 > /proc/smsc95xx/esbpf/rx_enable
```

# Stress-test
[esBPF: Stress-Testing compares Software-Offload with iptables](https://www.ooseel.net/me/2022/11/esbpf-stress-testing-compares-software-offload-with-iptables/)
