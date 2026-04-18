# Config-Config-Labs (EVE-NG)

A collection of high-level Cisco networking labs. This repository showcases functional configurations and topologies for **ENCOR**, **ENARSI**, and complex **Enterprise** projects, all built and validated in **EVE-NG**.

---

## 📂 Lab Collection

Each folder below contains a standalone project with all necessary assets for replication. 

> **Note:** A link to the virtual images are **not included** in this repository as they are proprietary and require valid licensing from the vendor.

---

## 🛠 What's in Each Lab?

Every lab folder provides a complete package for instant replication:
1.  **Topology Diagram:** A clear map of the network architecture (`./topology.png`).
2.  **Baseline Configurations:** Reference `.txt` files containing the validated logic for each node. These are intended to be used as a template for your own implementation.
3.  **Lab README:** A breakdown of the technical objectives, protocols involved, and specific verification commands.

---

## 🚀 How to Use

1.  **Build:** Match your EVE-NG topology to the provided diagram.
2.  **Implementation:** * Open the baseline configuration file for a device (e.g., `R1.txt`).
    * On the EVE-NG console, enter configuration mode (`edit`).
    * **Audit the interface IDs:** Ensure the interfaces in the text file (e.g., `ge-0/0/0`) match the physical cabling in your EVE-NG lab.
    * Use the configuration text as a guide to apply the logic to your nodes.
3.  **Verification:** Check the included video for expected results, then use **Ping** and **Traceroute** to validate end-to-end reachability across the data plane.

---

## 📝 Requirements

* **Platform:** EVE-NG (Community or Professional).
* **Images:** * **Routing:** vMX or vJunos-router images.
    * **Switching:** vQFX or vJunos-EX images.
