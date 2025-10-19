# Cloud Exercise 01 – Virtual Machine and Ping Test (Google Cloud)

This project demonstrates how to create a virtual machine (VM) on **Google Cloud Skills Boost**
and perform a ping test from a local computer to verify network connectivity.

---

## Objective
Create a simple cloud-based virtual machine and verify its connection
by performing a ping test from a local computer.

---

## Platform Details
- **Cloud Provider:** Google Cloud Platform (via Skills Boost Sandbox)
- **Lab Used:** Compute Engine: Qwik Start – Windows
- **Instance Name:** ping-vm
- **Region:** us-central1
- **Machine Type:** e2-micro
- **OS Image:** Ubuntu 22.04 LTS

---

## Steps Performed

1. Logged into [Google Cloud Skills Boost](https://www.cloudskillsboost.google)
2. Started the lab **Compute Engine: Qwik Start – Windows**
3. Created a new VM instance:
   - Name: `ping-vm`
   - Region: `us-central1`
   - Firewall: Enabled HTTP & HTTPS
4. Waited for instance to reach **RUNNING** state
5. Copied the **External IP** → `34.168.99.51`
6. Opened local terminal and executed the ping test:
   ```bash
   ping 34.168.99.51
