# FortiGate MicroVM installation on K8s KubeVirt

## Usage:
```
chmod+x ufgt-install
./ufgt-install -h <hostname> -i <fgt-qcow2-image> -u <uploadproxy-url> -c <cpu> -m <memory> -p <fmg-ip> -s <fmg-sn>
```

## Example:
```
chmod+x ufgt-install
./ufgt-install -h ufgt1 -i ../Images/fos-v723f-b1262.qcow2 -u https://uploadproxy.k8s.lab:8443 -c 2 -m 4G -p 172.31.254.4 -s FMG-VMTM00000000

```
