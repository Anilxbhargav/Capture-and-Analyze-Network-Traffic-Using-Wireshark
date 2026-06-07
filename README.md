# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective

The objective of this task was to capture live network traffic and analyze different network protocols using Wireshark in Kali Linux. The task helped in understanding packet capture, protocol filtering, and basic network troubleshooting concepts.

---

# Tools Used

* Kali Linux
* Wireshark

---

# Procedure Followed

## Step 1: Installing Wireshark

Wireshark was installed in Kali Linux using the terminal package manager.

Command used:

```bash
sudo apt update
sudo apt install wireshark -y
```

---

## Step 2: Starting Packet Capture

Wireshark was launched and the active network interface was selected for capturing live packets.

The capture process was started on the active interface connected to the internet.

---

## Step 3: Generating Network Traffic

To generate traffic for analysis:

* Websites such as Google and GitHub were opened in the browser.
* Network communication packets were generated automatically during browsing.

---

## Step 4: Stopping the Capture

After approximately one minute of capturing traffic, the packet capture process was stopped.

---

# Protocol Analysis

Different protocols were identified and filtered using Wireshark filters.

---

## 1. DNS Protocol

### Filter Used:

```bash
dns
```

### Observation:

DNS packets were observed during website access. These packets were responsible for converting domain names into IP addresses.

### Purpose:

DNS helps devices locate websites on the internet.

---

## 2. TCP Protocol

### Filter Used:

```bash
tcp
```

### Observation:

TCP packets were captured showing reliable communication between the system and remote servers.

### Purpose:

TCP ensures proper and reliable data transfer between devices.

---

## 3. TLS / HTTPS Protocol

### Filter Used:

```bash
tls
```

### Observation:

Encrypted web traffic packets were captured while browsing websites.

### Purpose:

TLS provides secure encrypted communication over the internet.

---

# Packet Details Observed

The following information was visible in captured packets:

* Source IP Address
* Destination IP Address
* Protocol Type
* Packet Length
* Port Numbers

---

# Key Concepts Learned

* Packet Capturing
* Protocol Analysis
* TCP/IP Communication
* DNS Resolution
* Secure Web Traffic
* Network Troubleshooting

---

# Conclusion

This task successfully demonstrated how live network traffic can be captured and analyzed using Wireshark in Kali Linux. Multiple protocols such as DNS, TCP, and TLS were identified and filtered successfully. The task improved understanding of packet analysis and network communication processes.

---
