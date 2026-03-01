# Cisco-Config-Labs (EVE-NG)

A collection of high-level Cisco networking labs. This repository showcases functional configurations and topologies for **ENCOR**, **ENARSI**, and complex **CAPSTONE** projects, all built and validated in **EVE-NG**.

---

## 📂 Lab Tracks

### 🔹 ENCOR
Core enterprise technologies focusing on switching, routing basics, and virtualization.
* **Key Topics:** MST/RSTP, OSPFv2, EIGRP, and Layer 2 Security.

### 🔹 ENARSI
Advanced routing and services troubleshooting.
* **Key Topics:** EIGRP, OSPF, BGP, VRFs, DMVPN, Route Maps, MPLS, and Policy-Based Routing (PBR).

### 🔹 CAPSTONE
Large-scale integration projects that bridge multiple protocols into a single, cohesive enterprise network.

---

## 🛠 What's in Each Lab?

Every lab folder provides a complete package for instant replication:

1.  **Topology Diagram:** A clear map of the network architecture.
2.  **Config Files:** Ready-to-use `.txt` files. Just **copy and paste** into your EVE-NG nodes.
3.  **Lab README:** A quick breakdown of the objectives and tasks.
4.  **Verification Video:** A concise video of me recreating the lab from scratch using the text files and verifying full connectivity.

---

## 🚀 How to Use

1.  **Build:** Match your EVE-NG topology to the provided diagram.
2.  **Paste:** * Open the `.txt` file for a device (e.g., `R1.txt`).
    * On the EVE-NG console, **bypass the initial startup wizard** (type `no` and hit Enter).
    * **Paste** the configuration directly.
3.  **Test:** Check the included video to see the expected convergence and connectivity results, then verify them on your own nodes.

---

## 📝 Requirements

* **Platform:** EVE-NG (Community or Professional).
* **Images:** Cisco IOS-XE.

> **Note:** Interface IDs (e.g., `Gi0/1`) are based on my specific EVE-NG cabling. Ensure your physical connections match the config files or adjust the naming before pasting.
