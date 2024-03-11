# ica0006

[catapult]: https://github.com/ClarifiedSecurity/catapult

username: student
password: student1234

| TEAM | ILO | SERVER OS IP | VM IP |
|---|---|---|---|
| Tiim5 | 192.168.161.133 192.168.161.134 192.168.161.135 | 192.168.161.153 192.168.161.154 192.168.161.155 | 192.168.180.64 |

## Plan

RAID type: tba<br>
OS: ubuntu server 22.xx<br>
Software: k8s

k8s workers on 3 servers (2 on bare metal, 1 on vm). k8s control plone will be ran on bare metal as well.

services on k8s:
    - s3
    - some webservice
    - ...(?)

We'll use [catapult] to deploy k8s.
