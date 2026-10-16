# Virtualization & Isolated Testbeds

## Executive Summary
Overview of hypervisors and virtual machine setup to construct isolated testing environments (sandboxes) for running vulnerable applications and testing exploits safely.

## Key Concepts
- **Hypervisors:** Type-1 (bare-metal) vs. Type-2 (hosted, e.g., VirtualBox, VMware Workstation).
- **Network Adapter Modes:**
  - *NAT:* VM gets internet access through the host IP; hidden from external host network.
  - *Host-Only:* Completely isolated network between host and guest VMs; no external internet access.
  - *Bridged:* VM acts as an independent device directly on the physical network.
- **State Preservation:** Creating and restoring VM snapshots prior to running malicious commands or testing exploits.

## Practical Takeaway
Using Host-Only or isolated virtual networks ensures that web exploitation tests (like DVWA) do not expose vulnerable endpoints to external networks or local Wi-Fi environments.
