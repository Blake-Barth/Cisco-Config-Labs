# Cisco-Config-Labs (EVE-NG)

A collection of high-level Cisco networking labs. This repository showcases functional configurations and topologies for **ENCOR**, **ENARSI**, and complex **CAPSTONE** projects, all built and validated in **EVE-NG**.

---

## 📂 Lab Collection

Each folder below contains a standalone project with all necessary assets for replication.

* **OSPFv3 Multi-Area**: Implementation of a multi-area OSPFv3 topology supporting a **dual-stack** (IPv4/IPv6) environment. This lab focuses on advanced LSA types and securing the control plane with **IPsec authentication**.
* **MPLS L3VPN**: A Service Provider core configuration utilizing **Multiprotocol BGP (MP-BGP)** and Label Distribution Protocol (LDP). It demonstrates traffic segmentation for multiple customers using **VRFs** and route targets to maintain end-to-end isolation.

---

## 🛠 What's in Each Lab?

Every lab folder provides a complete package for instant replication:

1.  **Topology Diagram:** A clear map of the network architecture (`./topology.png`).
2.  **Config Files:** Ready-to-use `.txt` files. Just **copy and paste** into your EVE-NG nodes.
3.  **Lab README:** A quick breakdown of the objectives and verification steps.
4.  **Verification Video:** A concise video of the lab being built from scratch and verifying connectivity (`./verification.mp4`).

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
* **Images:** Cisco IOS-XE (vIOS).

> **Note:** Interface IDs (e.g., `Gi0/1`) are based on specific EVE-NG cabling. Ensure your virtual connections match the config files or adjust the naming before pasting.
