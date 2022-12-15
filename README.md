# sysctl-buffer-for-quic

File:  /etc/sysctl.conf

```shell
net.core.rmem_max=26214400
net.core.rmem_default=26214400
```

Or run (temporary)
```shell
sudo sysctl -w net.core.rmem_max=26214400
sudo sysctl -w net.core.rmem_default=26214400
```
